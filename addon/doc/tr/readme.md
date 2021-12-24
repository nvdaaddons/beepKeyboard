# Sesli klavye #

* Yazar: David CM
* [Kararlı sürümü][1] indir
* [Geliştirici sürümünü][2] indir
* NVDA uyumluluğu: 2018.2-2019.2

Bu eklentiyle NVDA'yı bazı klavye tuşlarına basıldığında bip sesi çıkartmak
üzere ayarlayabilirsiniz.

## Özellikler

Eklenti sayesinde NVDA'nın klavye davranışlarını değiştirmek için aşağıdaki
özellikleri kullanabilirsiniz:

* Capslock açıkken büyük harf yazıldığında bip sesi çıkar: Bu özellik
  etkinken capslock açıkken büyük harf yazarsanız NVDA bip sesi
  çıkarır. Büyük harf hatası yapmamış olursunuz!
* Shift tuşu basılıyken karakter yazıldığında bip sesi çıkar: Shift tuşunu
  basılı tutarken karakter yazdığınızda NVDA bip sesi çıkarır.
* Açılıp kapanan tuşların durumu değiştiğinde bip sesi çıkar: Açılıp kapanan
  tuşlardan biri açılırsa NVDA daha ince bir bip sesi çıkarır, kapanırsa
  kalın bir bip sesi çıkarır.
  Windows'un erişim kolaylığı merkezinde bu tuşlar açılıp kapandığında ses
  çalmasına yarayan geçiş tuşları özelliği olduğunu unutmayın. Dizüstü
  klavye dizinini kullanmıyorsanız Windows'un özelliği iyi çalışır.
* Açılıp kapanan tuş değişikliklerini söyle: Açılıp kapanan tuşların durumu
  değiştiğinde bip sesi çıkar özelliği açıkken NVDA'nın açılıp kapanan
  tuşların durumunu söylemesini açıp kapatabilirsiniz.
* Belirli karakterler yazıldığında bip sesi çıkar: Gelişmiş ayarlarda
  ayarladığınız tüm karakterler yazıldığında NVDA bip sesi çıkarır.
* Şifre alanlarında bip sesi çıkarma: Güvenlik risklerini önlemek için bu
  özellik varsayılan olarak açıktır. NVDA'nın şifre alanlarında bip sesi
  çıkarmasını istiyorsanız özelliği kapatabilirsiniz.

## Gereksinimler

NVDA 2018.2 veya daha üstü sürümü

## Kurulum

Özelliği NVDA eklentisi olarak yükleyebilirsiniz.

## Kullanım

Özellikleri açıp kapatmak için NVDA ayarlarının sesli klavye kategorisini kullanın. Bu kategoride eklentinin desteklediği tüm özellikleri ayarlayabilirsiniz.

* "Capslock açıkken büyük harf yazıldığında bip sesi çıkar" özelliği
  varsayılan olarak açıktır.

Daha fazla ayarlama yapmak istiyorsanız aşağıdaki seçenekleri içeren
gelişmiş ayarlar iletişim kutusunu kullanın:

* Shift tuşu basılıyken yoksayılacak karakterler: Shift tuşu basılıyken bu
  karakterler yazılırsa NVDA bip sesi çıkarmayacaktır. Tab için "\t", satır
  başı için "\r" gibi kaçış dizileri de yazılabilir.
* Şu karakterler yazıldığında her zaman bip sesi çıkar: NVDA'nın her zaman
  bip sesi çıkarmasını istediğiniz karakterleri yazın. Tab için "\t", satır
  başı için "\r" gibi kaçış dizileri de yazılabilir.
* Ayarlamak için ses seçin: Tüm seslerin parametrelerini
  ayarlayabilirsiniz. Buradan sesi seçtikten sonra metin kutularından sesi
  ayarlayabilirsiniz. Seçiminizi değiştirdiğinizde yaptığınız ayarlarla
  seçtiğiniz sesi duyacaksınız.
* Ses kalınlığı: Seçtiğiniz sesin kalınlığını ayarlamanıza yarar.
* Ses uzunluğu: Seçtiğiniz sesin uzunluğunu ayarlamanıza yarar.
* Ses yüksekliği: Seçtiğiniz sesin yüksekliğini ayarlamanıza yarar.
* Sesi test et: Yaptığınız ayarlarla seçtiğiniz sesi dinlemenize yarar.
* Ayarları kaydetmek için tamam düğmesine basın veya iptal etmek için iptal
  düğmesini kullanın.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
