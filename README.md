# Genetic Algorithms
Genetik algoritmalar Sezgisel Optimizasyon Algoritmasıdır. En iyi noktayı arayan algoritmalardır. Permütasyon tabanlı bir optimizasyon yapar ve olasılıklar üzerinden yakınsama kriterleri altında arama yapan bir fonksiyondur. Doğada gözlemlenen evrimsel sürece benzer bir şekilde çalışan, arama ve eniyileme yöntemidir.

GA ’da olası çözüm bilgilerini ifade eden bireylerin topluluğuna **Popülasyon** denir. Popülasyonda ki her bireyimizin ismi **Kromozomdur.** Kromozomlarımız da **gen**lerden oluşmaktadır.

![image](https://user-images.githubusercontent.com/72580629/233979135-636a4640-64f2-4792-ab85-60f25a13a2c5.png)

- **İşleyiş şöyledir;**
    Başlangıçta kromozomlarımızın ideal kromozom olup olmadıkları için belirli testlere (**fitness function**) sokuyor ve puanlıyoruz, belirlenen yeni popülasyonumuzu bir kurallar yapısına sokuyor ve bu kromozonlardan tekrardan yeni kromozomlar oluşturuyoruz. Bu yeni kuşakta yine başarılı olanları türetiyor ve başarısız olanları popülasyonumuzdan uzaklaşmasını bekliyoruz. Bu işlem sürekli belirli bir noktaya kadar devam ediyor. Bittiğinde elimizde en başarılı kromozom kalıyor. Bu en başarılı kromozomda bizim en ideal çözümümüze yakın olan çözüm oluyor (Sezgisel algoritmalarda en ideal değil ideal ’e en yakın aranır.) ve çözümü bulmuş varsayıyoruz.
    Yeni nesilleri türetme evresinde kullanabileceğimiz iki yöntemimiz bulunmaktadır. Bunlardan birincisi **çaprazlama** ve ikincisi **mutasyon** dur.
Çaprazlama seçilmiş iki kromozomun belirlenmiş bir kural ile yeni gen oluşturmasıdır. Mutasyon ise belirlenmiş bir genin üzerine zorlama ile farklılaştırmaktır.

![image](https://user-images.githubusercontent.com/72580629/233979638-18c345dc-694c-46eb-8dab-9ac0d78b7594.png)

![image](https://user-images.githubusercontent.com/72580629/233979929-273cfb86-f19f-4780-9c77-37dfb1652cbf.png)

