# Speech to Text 

**Dil:** C#  
**IDE:** Visual Studio (2019 / 2022 önerilir)  
**Target:** .NET Framework 4.7.2 veya 4.8 (Windows)

## Açıklama
Bu proje, Windows üzerinde çalışan basit bir konuşma tanıma (speech-to-text) uygulamasıdır.  
`System.Speech.Recognition` kütüphanesi kullanılarak mikrofon girişinden gelen sesin yazıya dönüştürülmesi amaçlanmıştır.  
Proje ödev kapsamında hazırlanmıştır.

## Özellikler
- Gerçek zamanlı konuşma tanıma  
- Başlat / Durdur kontrolleri  
- Tanınan metni uygulama içindeki bir **TextBox**’ta gösterme  
- **İngilizce ses komutlarını** tanıma (English speech recognition)

## Gereksinimler
- Windows 10 veya üzeri  
- Visual Studio 2019 veya 2022 (güncel sürüm önerilir)  
- .NET Framework 4.7.2 veya 4.8  
- Bilgisayar mikrofonu ve mikrofon erişim izinleri

> **Not:** `System.Speech` yalnızca .NET Framework sürümlerinde kullanılabilir.  
> Eğer proje .NET Core veya .NET 5+ tabanlıysa, alternatif kütüphaneler (Azure / Google / IBM Speech SDK vb.) kullanılmalıdır.

## Kurulum & Çalıştırma
1. Depoyu GitHub’a yükledikten sonra (veya zip olarak indirdikten sonra)  
2. Visual Studio’yu açın → **File → Open → Project/Solution** → `.sln` dosyasını seçin  
3. **Solution Configuration:** `Debug`  
4. **Platform:** `Any CPU`  
5. Menüden **Build → Rebuild Solution**  
6. Hata yoksa **Start (F5)** tuşuna basarak uygulamayı çalıştırın  
7. Uygulama açıldıktan sonra **Start** butonuna basın ve **İngilizce konuşun** — tanınan metin TextBox içinde görünecektir.
