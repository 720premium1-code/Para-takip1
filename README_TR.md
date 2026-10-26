# Para Takip Android APK projesi

Bu proje, mevcut Para Takip web arayüzünü Android WebView içinde açar. İşlemler cihazdaki WebView yerel depolamasında saklanır; internet/banka bağlantısı gerekmez. Euro kuru uygulamada sabit 55 TL'dir.

## APK oluşturma (GitHub Actions ile)
1. Bu klasördeki dosyaları yeni bir GitHub deposuna yükle.
2. GitHub'da **Actions** sekmesini aç.
3. **Build Para Takip APK** iş akışını seçip **Run workflow** düğmesine bas.
4. İşlem tamamlanınca `para-takip-apk` adlı artifact'i indir.
5. ZIP içindeki `app-debug.apk` dosyasını Android telefonuna gönderip aç. Gerekirse Android ayarlarından bu kaynağa uygulama yükleme izni ver.

## Android Studio ile
Projeyi Android Studio'da aç, Gradle eşitlemesini tamamla ve **Build > Build APK(s)** seçeneğini kullan.
