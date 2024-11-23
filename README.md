# Havayolu Veri Seti Üzerine Analiz
![havayolu-take-off](https://github.com/user-attachments/assets/7445ee62-ef76-4241-a23e-768a85f0b787) 

Airline Dataset : https://www.kaggle.com/datasets/iamsouravbanerjee/airline-dataset?select=Airline+Dataset+Updated+-+v2.csv

Bu veri seti, küresel havayolu operasyonlarına dair yolcu demografisi, seyahat ayrıntıları, uçuş rotaları, mürettebat bilgileri ve uçuş durumları hakkında kapsamlı veriler sunar. İçeriğinde yer alan Yolcu Kimliği, Adı, Soyadı, Cinsiyet, Yaş, Milliyet, Havaalanı Adı, Havaalanı Ülke Kodu, Ülke Adı, Havaalanı Kıtası, Kıtalar, Kalkış Tarihi, Varış Havaalanı, Pilot Adı ve Uçuş Durumu gibi parametrelerle yolcu davranışları, seyahat trendleri, uçuş performansı ve bölgesel uçuş ağları analiz edilebilir. Bu veriler, havayolu şirketlerinin operasyonel verimliliği artırmak, yolcu deneyimlerini iyileştirmek ve stratejik kararlar almak için faydalıdır.

### Değişkenler
* Yolcu Kimliği - Her yolcu için benzersiz tanımlayıcı
* Adı - Yolcunun adı
* Soyadı - Yolcunun soyadı
* Cinsiyet - Yolcunun cinsiyeti
* Yaş - Yolcunun yaşı
* Milliyet - Yolcunun milliyeti
* Havaalanı Adı - Yolcunun uçağa bindiği havaalanının adı
* Havaalanı Ülke Kodu - Havaalanının bulunduğu yerin ülke kodu
* Ülke Adı - Havaalanının bulunduğu ülkenin adı
* Havaalanı Kıtası - Havaalanının bulunduğu kıta
* Kıtalar - Uçuş rotasında yer alan kıtalar
* Kalkış Tarihi - Uçuşun kalkış tarihi
* Varış Havaalanı - Uçuşun varış havaalanı
* Pilot Adı - Uçuşu gerçekleştiren pilotun adı
* Uçuş Durumu - Uçuşun güncel durumu (zamanında, gecikmeli, iptal edilmiş)


Veri setinde temel olarak 8 adet işlem yapılmıştır.
* _Veri Setinin Hazırlanması_
* _Veriye İlk Bakış_
* _Eksik Veri Analizi_
* _Kategorik Değişken Analizi_
* _Sürekli Değişken Analizi_
* _Aykırı Değer Analizi_
* _Feature Engineering_
* _Sonuç ve Öneriler_

### Bulgular ve İşlemler

* Veri seti toplamda 98619 satır ve 15 sütun içermektedir.
* Yaş(Age) sütunu nümerik veriler içerirken diğer sütunlar metin ve sayı-metin karışık olmak üzere object veriler içermektedir.
* Veride yaş ortalaması 45.484538 bulunmuştur.
* Veride milliyet değişkeninde en çok yolcu Çin'den elde edilmiştir.
* En çok 43 kayıt ile San Pedro Havaalanı gözlemlenirken, en az Falcon State Havaalanı ve Hiroshima Havaalanı'na ait 1'er kayıt gözlenmiştir.
* Veride en çok avaalanının bulunduğu ülke United States olmuştur.
* Veride aykırı değer gözlenmemiştir.

### Kaggle Çalışmam
https://www.kaggle.com/code/bsakoz/havayolu-veri-seti-zerine-analiz
