# Değişiklikler

Her sürümün notları burada tutulur. Yayınlanırken ilgili bölüm güncelleme penceresinde gösterilir.
Başlıklar: **Eklendi**, **İyileştirildi**, **Düzeltildi**, **Kaldırıldı**.

## 2.5.1

### Eklendi
- **Önce kapatılacaklar (Ayarlar):** Kapat, Yeniden başlat ve Oturumu kapat'tan hemen önce seçtiğiniz programlar düzgünce kapatılır; 5 saniye içinde kapanmayanlar zorlanır. Virgülle ayrılır, `*` kullanılabilir. Bilgisayar açılınca programlar yine kendiliğinden başlar.

### Düzeltildi
- HyperX NGENUITY yüklü bilgisayarlarda kapanırken çıkan **"hxn-srv-audio-engine.exe – Uygulama düzgün olarak başlatılamadı (0xc0000142)"** penceresi. NGENUITY artık varsayılan olarak kapanıştan önce kapatılır.
- Windows'un çalışması için gerekli süreçler bu listeye yazılsa bile kapatılmaz.

## 2.5.0

### Eklendi
- **Telefonu bulma:** "Telefon evden çıkınca" koşulundaki **Bul** düğmesi ev ağındaki iPhone ve Android telefonları listeler. Telefon panelini açtığınız telefon en üstte görünür; adresin yanına yazdığınız adı (ör. "Ayşe'nin iPhone'u") program hatırlar.
- **Android desteği:** Android telefonlar da bulunur; telefon panelini açınca modeli listede görünür. Telefonun evde olup olmadığı iPhone ve Android için ayrı yöntemlerle denetlenir.
- Programda, telefon panelinde ve kurulum penceresinde **Powered by Sistem F** bağlantısı; Ayarlar'da telif bilgisi.
- Program dosyasında şirket, sürüm ve telif bilgisi (Windows'ta dosya özelliklerinde görünür).

### İyileştirildi
- Evde birden çok telefon varsa program kendiliğinden birini seçmez; yanlış telefona göre kapatmamak için seçimi size bırakır.
- Telegram botunun yardım mesajına Steam komutu eklendi.

## 2.4.0

### Eklendi
- **Steam indirmesi bitince:** Steam'deki oyun indirmeleri ve güncellemeleri bitince kapatır. Ağ hızına değil Steam'in kendi kayıtlarına bakılır; indirilen oyunun adı ve yüzdesi ekranda görünür. Sıradaki oyun inmeye başlarsa beklemeye devam edilir, duraklatılan indirme bitmiş sayılmaz. Telefondan ve Telegram'dan "steam indirmesi bitince kapat" da denebilir.
- **VE koşulları:** Koşul ekranındaki "+ VE koşulu ekle" ile en çok iki koşul daha eklenir; işlem hepsi sağlanınca yapılır. Örnek: "Steam indirmesi bitince VE 30 dk boşta kalınca kapat".
- **Telefon evden çıkınca:** Telefon belirlenen süre boyunca ev Wi-Fi'ında görünmezse işlem yapılır. Telefon panelini açan telefonlar listede kendiliğinden çıkar.
- **Kulaklık ayrılınca:** Seçilen kulaklık ya da hoparlör kapatılır veya çıkarılırsa ve süre içinde geri bağlanmazsa işlem yapılır (Bluetooth, USB ve kablolu cihazlar; dongle'lı kablosuz kulaklıklarda dongle bağlı kaldığı için çalışmayabilir).
- Hazır ayarlara "Steam indirmesi" eklendi (yeni kurulumlarda).

## 2.3

### Eklendi
- Telefon panelinde süreyi elle girebilirsiniz: Saat, Dakika ve Saniye kutularına doğrudan yazın ya da ▲ ▼ ile ayarlayın. Hazır süre düğmeleri de duruyor.

### İyileştirildi
- Telefondan başlatılan geri sayım artık saniye hassasiyetinde. "90" dakika yazarsanız kendiliğinden 1:30:00'a çevrilir.

## 2.2

### Eklendi
- Telefon panelinde "Komut söyle" kutusu: klavyedeki mikrofona dokunup "1 saat sonra kapat", "indirme bitince kapat", "durdur" gibi cümleleri söyleyin. Android ve iPhone'da ek uygulama gerekmez.
- Komut kutusunun altında tek dokunuşla kullanılan örnek komutlar (geri sayım varken ertele / durdur seçenekleri).

### İyileştirildi
- Android'de panelin ana ekrana nasıl ekleneceği Chrome'a göre anlatılıyor.

## 2.1

### Eklendi
- Kendiliğinden güncelleme: yeni sürüm çıkınca bildirim gelir, ne değiştiği gösterilir, tek tıkla indirilip kurulur.
- Güncelleme sırasında çalışan geri sayım kaybolmaz; yeni sürümde kaldığı yerden devam eder.
- Ayarlar sayfasında "Güncellemeleri denetle" düğmesi ve otomatik denetim seçeneği.

### İyileştirildi
- Güncellemeden sonra ilk açılışta "Yenilikler" penceresi gösterilir.
