İLİM — KİŞİSEL TAKİP | İLK ÇALIŞAN PROTOTİP

DOSYALAR
- index.html: Uygulamanın ekranları ve işlevleri
- manifest.webmanifest, icon.svg: Ana ekrana kurulabilir uygulama tanımı ve simge
- sw.js: İlk açılıştan sonra uygulama dosyalarını çevrimdışı önbellekte tutar

İÇERİK
- Haftalık ders programı ve katılım durumu
- Günlük/haftalık görevler ve kişisel alışkanlıklar
- Kitaplık ve sayfa ilerlemesi
- Kronometre ve manuel çalışma kaydı
- Anlaşılmayan meseleler defteri
- İlmî hedefler
- Gün sonu muhasebesi
- Çalışma raporları
- Açık/koyu tema
- JSON yedekleme ve geri yükleme

ÇEVRİMDIŞI KULLANIM
Uygulama hiçbir harici font, resim, kütüphane veya API çağrısı kullanmaz. PWA olarak kurulumda ilk açılış için HTTPS üzerinden bir kez yüklenmesi gerekir; uygulama dosyaları önbelleğe alındıktan sonra internet olmadan açılabilir.

VERİ GÜVENLİĞİ
Veriler bu tarayıcıdaki yerel depoda saklanır; buluta gönderilmez ve cihazlar arasında eşitlenmez. Tarayıcı/site verilerinin silinmesi kayıtları silebilir. Ayarlar bölümünden düzenli olarak JSON yedeği indir.

ÖNEMLİ TEST NOTU
index.html tek başına prototipi görüntülemek için kullanılabilir. Service worker ve ana ekrana kurulum yalnızca HTTPS veya localhost gibi güvenli bir kaynaktan çalışır. Uzun süreli kullanımdan önce Samsung tablette açılış, yerel veri saklama ve çevrimdışı açılma testleri yapılmalıdır.
