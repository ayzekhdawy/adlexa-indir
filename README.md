# Adlexa indirme

Bu depo yalnız **Adlexa kurulum dosyalarını** dağıtır. Kaynak kod burada yoktur.

- Windows (10 / 11, 64 bit): `Adlexa_x64_tr-TR.msi`
- Android (8 ve üstü): `adlexa.apk`
- Her sürümde `SHA256SUMS.txt`: indirdiğiniz dosyanın özetini bununla karşılaştırın.

En son sürüm: [Sürümler](../../releases/latest) · Web: [adlexa.com](https://adlexa.com) · Katalog: [indir.noniux.com](https://indir.noniux.com)

## Deneme sürümü

Şu anki sürümler **deneme sürümüdür** ve kod imzası taşımaz.

- **Windows:** "Windows kişisel bilgisayarınızı korudu" uyarısı çıkarsa **Ek bilgi → Yine de çalıştır**. Veriler bilgisayarınızda `%APPDATA%\noniux\adlexa` altında şifreli durur; program kaldırılınca silinmez.
- **Android:** Play Store'dan önce doğrudan kurulum içindir. Telefon "bilinmeyen kaynaklardan yükleme" izni ister; kurulumdan sonra bu izni kapatabilirsiniz.

## Özet doğrulama

Windows PowerShell:

```powershell
Get-FileHash .\Adlexa_x64_tr-TR.msi -Algorithm SHA256
```

Çıkan değer `SHA256SUMS.txt` içindekiyle aynı olmalı.

Adlexa bağımsız bir yazılımdır; T.C. Adalet Bakanlığı veya UYAP'ın resmî uygulaması değildir. Geliştirici: Noniux.
