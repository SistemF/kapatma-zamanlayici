<p align="center">
  <b>Kapatma Zamanlayıcısı</b><br>
  Bilgisayarınızı tam zamanında kapatan, uyutan ya da kilitleyen; telefondan, Siri'den ve Telegram'dan yönetilen ücretsiz Windows programı.
</p>

<p align="center">
  <a href="https://github.com/SistemF/kapatma-zamanlayici/releases/latest/download/KapatmaZamanlayici-Kurulum.exe"><b>⬇ İndir (Windows 10 / 11)</b></a>
  · tek dosya, yaklaşık 13 MB · yönetici izni gerekmez · Türkçe
</p>

---

## Ne işe yarar?

- 🎬 Film izlerken uyuyakalırsanız bilgisayar kendini kapatır.
- 🎮 Steam'deki oyun indirmesi ya da güncellemesi bitince kapanır.
- ⬇️ Gece büyük bir indirme ya da render bitince kapanır, sabaha kadar boşuna açık kalmaz.
- 📱 Kanepeden kalkmadan telefondan erteler, durdurur ya da yeni süre başlatırsınız.
- 🏠 Evden çıkınca (telefonunuz ev Wi-Fi'ından ayrılınca) bilgisayar kendini kapatır.

## Nasıl zamanlanır?

| Yol | Örnek |
|---|---|
| **Süre sonra** | 1 saat 30 dakika sonra kapat |
| **Belirli saatte** | 23:30'da kapat |
| **Koşul olunca** | İndirme bitince · **Steam indirmesi bitince** · boşta kalınca · işlemci yükü düşünce · bir program kapanınca · pil azalınca · **kulaklık ayrılınca** · **telefon evden çıkınca** |
| **Koşulları birleştir** | Steam indirmesi bitince **VE** 30 dakika boşta kalınca kapat |
| **Her hafta** | Hafta içi her gece 01:00'de kapat, sabah 07:00'de uykudan uyandır |

Yapabildikleri: **kapat, yeniden başlat, uyut, hazırda beklet, oturumu kapat, ekranı kilitle, monitörü kapat, sesi kapat, bir programı kapat.**
Sık kullandıklarınızı **hazır ayar** olarak kaydedip tek tıkla başlatabilirsiniz.

## Telefondan kontrol

- Programdaki **QR kodu okutun**: telefonda kalan süreyi görün, **+5 / +15 dk** erteleyin, durdurun ya da saat, dakika, saniyeyi elle girerek yeni geri sayım başlatın. Ayrı uygulama gerekmez.
- **iPhone:** "Hey Siri, Bilgisayar" → *"1 saat sonra kapat"*, *"indirme bitince kapat"*, *"ne kadar kaldı"*, *"durdur"*. Evden çıkınca ya da uyku moduna geçince kendiliğinden çalışan otomasyonlar.
- **Sesle komut (Android ve iPhone):** paneldeki kutuya klavyenin mikrofonuyla *"1 saat sonra kapat"*, *"steam indirmesi bitince kapat"*, *"durdur"* deyin.
- **Telegram botu:** evin dışından bile yazarak ya da sesle yönetin.

## Haberiniz olsun

- Kapanmadan **10, 5 ve 1 dakika önce** telefona bildirim gelir (ntfy ya da Telegram).
- Son dakikada ekranı kaplayan büyük bir uyarı çıkar: **ertele** ya da **iptal**.
- Bilgisayar uykudayken süre dolduysa, uyanınca hemen kapatmaz; önce uyarır.

## Dahası

- 🖥️ Ağdaki **diğer bilgisayarları** uyandırma (Wake-on-LAN) ve uzaktan kapatma.
- 👪 **Ebeveyn kilidi** ve **günlük kullanım sınırı**.
- ⌨️ Klavye kısayolları: Ctrl+Alt+Shift+E ertele, +X iptal.
- 🌗 Açık/koyu tema · Windows ile birlikte başlama · geçmiş kaydı.
- 🔄 **Kendiliğinden güncellenir:** yeni sürüm çıkınca ne değiştiğini gösterir, tek tıkla kurar.

## Kurulum

1. **[KapatmaZamanlayici-Kurulum.exe](https://github.com/SistemF/kapatma-zamanlayici/releases/latest/download/KapatmaZamanlayici-Kurulum.exe)** dosyasını indirip açın.
2. Windows *"Kişisel bilgisayarınız korundu"* derse: **Ek bilgi → Yine de çalıştır**. Program henüz dijital imzalı olmadığı için bu uyarı çıkar.
3. **Kur ve başlat**'a basın. Kısa bir tanıtım sizi karşılar.
4. Telefondan kontrolü açtığınızda Windows Güvenlik Duvarı sorarsa **Özel ağlar**'a izin verin.

Kaldırmak için: programda **Ayarlar → Programı kaldır** ya da Windows **Ayarlar → Uygulamalar**.

## Gizlilik ve güvenlik

- **Hesap, reklam, izleme yok.** Program kullanım verisi toplamaz. İnternete yalnızca güncelleme denetimi için (GitHub) ve sizin açtığınız ntfy/Telegram bildirimleri için bağlanır.
- Ayarlarınız yalnızca sizin bilgisayarınızda, `%APPDATA%\KapatmaZamanlayici` klasöründe durur.
- Telefon paneli yalnızca ev ağınızda çalışır ve her kuruluma özel rastgele bir bağlantı koduyla korunur. Kodu programdan istediğiniz an yenileyebilirsiniz.
- ntfy ve Telegram bildirimleri **isteğe bağlıdır** ve siz açmadıkça kullanılmaz.
- Güncellemeler yalnızca bu GitHub sayfasından indirilir ve kurulmadan önce **SHA-256 özetiyle doğrulanır**.
- Yönetici izni istemez; Windows'un yalnızca kendi kullanıcınıza ait bölümlerine kurulur.

## Sık sorulanlar

**Kulaklık ayrılınca koşulu kulaklığımı görmüyor.** Bu koşul Bluetooth, USB ve kablolu kulaklıklarla çalışır. Kablosuz alıcısı (dongle) olan kulaklıklarda kulaklık kapansa da alıcı bilgisayarda "bağlı" kaldığı için Windows bunu fark etmez.

**Telefon evden çıkınca koşulunda telefonumu nasıl seçerim?** **Bul** düğmesi ev ağındaki telefonları listeler. Evde birden çok telefon varsa, telefonunuzda kontrol panelini bir kez açın; telefonunuz listede en üstte görünür. Adresin yanına bir ad yazarsanız (ör. *192.168.1.20 · Ayşe'nin iPhone'u*) program onu hatırlar.

**Antivirüs uyarı veriyor.** Program Python ile yazılıp tek dosya halinde paketlendiği için bazı antivirüsler emin olamayıp uyarabilir. Programı yalnızca bu sayfadaki resmi bağlantıdan indirin.

## Sorun bildirimi

Hata ya da öneri için bu sayfadaki **Issues** bölümünü kullanabilir ya da [sistemf.com.tr](https://www.sistemf.com.tr/) üzerinden bize ulaşabilirsiniz. Bir güvenlik açığı bulduysanız lütfen herkese açık yazmak yerine web sitemizdeki iletişim kanalından bildirin.

## Lisans

© 2026 Sistem F. Tüm hakları saklıdır. Program ücretsiz kullanılabilir ve değiştirilmeden, ücretsiz olarak paylaşılabilir. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.

---

<p align="center"><a href="https://www.sistemf.com.tr/">Powered by <b>Sistem F</b></a></p>
