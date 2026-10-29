# MT5 Panel

[English](README.md) | **Türkçe**

MetaTrader 5 için taşınabilir (portable) bir işlem paneli: tek tıkla alış/satış, grafik analiz araçları, SL yöneticisi, hedge modülü ve yapay zeka asistanı. Kurulum gerektirmeden kendi klasöründe çalışır.

*A portable MetaTrader 5 trading panel for Windows: one-click trading, charting tools, SL manager, hedge module and an AI assistant. (Turkish and English UI.)*

> ⚠️ **Risk uyarısı:** Forex ve CFD işlemleri yüksek risk taşır, sermayenin tamamı kaybedilebilir. Bu yazılım yatırım tavsiyesi vermez ve kâr garantisi sunmaz. **Önce demo hesapta deneyin.** Yazılım "olduğu gibi" sunulur; kullanımdan doğan zararlardan geliştirici sorumlu değildir.

## İndirme

**[➡ Son sürümü indir (Releases)](https://github.com/KULLANICI_ADI/MT5Panel/releases/latest)**

| Dosya | Ne için |
|---|---|
| `MT5Panel-Setup-x.y.z.exe` | Kurulum programı (kullanıcı klasörüne kurar, yönetici izni gerekmez) |
| `MT5Panel-portable-x.y.z.zip` | Taşınabilir sürüm: zip'i bir klasöre açıp `MT5Panel.exe` çalıştırın |

**İndirdiğiniz dosyayı doğrulayın:** Release sayfasında her dosyanın SHA256 değeri yazar. Windows'ta:

```
certutil -hashfile MT5Panel-Setup-x.y.z.exe SHA256
```

Çıkan değer sayfadakiyle birebir aynı olmalı.

> Windows "SmartScreen: bilgisayarınızı korudu" uyarısı gösterebilir (program henüz imzalı değil). **Daha fazla bilgi → Yine de çalıştır** ile devam edebilirsiniz. Dosyanın SHA256 değerini yukarıdaki gibi doğrulamanız önerilir.

## Gereksinimler

- Windows 10 / 11 (64 bit)
- Bir MT5 işlem hesabı (hesap no, sunucu, şifre) — **önce demo hesap önerilir**
- İnternet bağlantısı

## İlk çalıştırma

1. Programı açın; **Hesap no**, **Sunucu** ve **Şifre** alanlarını doldurup **Giriş**'e basın.
2. Şifre yalnızca sizin bilgisayarınızda, Windows'un kullanıcıya özel şifrelemesiyle saklanır ("Şifreyi kaydet" işaretliyse).
3. Dil, arayüzün üst kısmındaki listeden değiştirilir (yeniden başlatma gerekir).

## Özellikler

**Temel (ücretsiz):** MT5 hesabıyla giriş, tek tıkla alış/satış (lot +/−, SL/TP), pozisyon listesi ve toplu kapatma, Market Watch (spread ve günlük değişim), mum grafiği, MA20/50/200 ve Bollinger, çizim araçları (trend çizgisi, yatay/dikey çizgi, dikdörtgen, ölçüm), ekran görüntüsü, tam ekran, haber takvimi (3 yıldızlı olaylar).

**Lisanslı özellikler** (lisans dosyası gerekir):

| Özellik | Açıklama |
|---|---|
| SupDem | Supply / Demand bölgeleri |
| Grid Level | H1 açılışı çevresinde USD veya pip aralıklı seviye çizgileri |
| Swing çizgileri | Test edilmemiş swing high / low çizgileri, yaklaşınca sesli alarm |
| Seans kutuları | Asya, Londra, New York aralıkları |
| Hedge | Kademeli kapatmalı hedge, saat başı otomatik hedge |
| SL Yöneticisi | Riske göre ortak stop-loss |
| Yapay zeka | Claude / ChatGPT / Gemini ile grafik yorumu (kendi API anahtarınız veya kredi) |
| Çoklu grafik | 8 grafiğe kadar sekme |
| Fibo | Fibonacci çizim aracı |

## Lisans nasıl alınır?

1. Programda **Lisans** düğmesine basın ve **bilgisayar kimliğinizi** (ID) kopyalayın.
2. Bana iletin: `İLETİŞİM_BİLGİSİ`
3. Size bir `license.lic` dosyası göndereceğim. Dosyayı program klasörüne koyun ya da **Lisans → Lisans dosyası yükle** ile seçin.

Lisans dosyasını başkalarıyla paylaşmayın; bilgisayarınıza ve/veya hesabınıza bağlı olabilir. Lisans olmadan program temel özelliklerle çalışmaya devam eder.

## Sorun bildirme

[Issues](https://github.com/KULLANICI_ADI/MT5Panel/issues) bölümünden açın. **Paylaşmadan önce** ekran görüntülerinde ve günlüklerde hesap numaranızı, bakiyenizi ve şifrenizi silin/karartın.

## Gizlilik

- İşlem, MT5 hesabınız ile broker sunucusu arasında yapılır; hesap bilgileriniz benim sunucuma gönderilmez.
- Yapay zeka özelliği kullanıldığında grafik verisi seçtiğiniz sağlayıcıya (Claude/OpenAI/Gemini) gönderilir.

## Kullanım koşulları

[EULA.tr.txt](EULA.tr.txt) dosyasına bakın (çeviri; ihtilaf halinde İngilizce [EULA.txt](EULA.txt) geçerlidir).
