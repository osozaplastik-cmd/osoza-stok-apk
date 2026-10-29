# Osoza Stok – APK oluşturma

Bu klasör, uygulamayı Android APK'sına çeviren hazır bir projedir.
Uygulama **boş** gelir: içinde hiç ürün veya kayıt yoktur. Bilgileri telefona kurduktan sonra siz girersiniz.

## APK'yı ücretsiz almak için (yaklaşık 10 dakika)

1. https://github.com adresinde ücretsiz hesap açın / giriş yapın.
2. Sağ üstten **+ → New repository** deyin. Adı: `osoza-stok`. **Private** seçebilirsiniz. Create deyin.
3. Açılan sayfada **uploading an existing file** bağlantısına tıklayın.
4. Bu zip'i bilgisayarınızda açın; içindeki **tüm dosya ve klasörleri** (`.github` klasörü dahil) sayfaya sürükleyin. **Commit changes** deyin.
   - `.github` klasörü gizli görünebilir. Windows'ta Görünüm → Gizli öğeler'i açın.
5. Üstteki **Actions** sekmesine gidin. "APK olustur" çalışmaya başlar (5–8 dakika). Başlamazsa soldan **APK olustur → Run workflow** deyin.
6. Yeşil tik çıkınca tamamlanan çalışmaya tıklayın, en altta **Artifacts** bölümündeki **Osoza-Stok-APK** dosyasını indirin.
7. İnen zip'in içinden **app-debug.apk** çıkar. Telefona gönderin (WhatsApp, e-posta, kablo) ve dokunup kurun.
   - Telefon "bilinmeyen kaynaklardan yükleme" izni isteyebilir; izin verin.

## Notlar
- Veriler telefonun içinde saklanır. Telefon değiştirmeden veya uygulamayı silmeden önce **Rapor → Yedek dosyası kaydet / paylaş** ile yedek alın.
- Güncelleme yaparsanız aynı depodaki `www/` dosyalarını değiştirin; Actions yeni APK üretir. Aynı APK üzerine kurunca veriler korunur.
