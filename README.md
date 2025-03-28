# Sınav Not Hesaplama Sistemi (2022)

 ## Proje Hakkında
Bu proje, 2022 yılında C programlama dili kullanılarak geliştirilmiş kapsamlı bir sınav notlandırma ve analiz sistemidir. Sistem, eğitim kurumlarında sınav değerlendirme süreçlerini otomatikleştirmek ve nesnel analizler yapabilmek amacıyla tasarlanmıştır.
 ## Proje Açıklaması
 Bu proje, C programlama dili kullanılarak geliştirilmiş kapsamlı bir sınav notlandırma ve analiz sistemidir. Sistem, eğitimcilerin sınav sonuçlarını hızlı ve etkili bir şekilde değerlendirmesine olanak tanıyan çok yönlü bir çözüm sunmaktadır. Program, rastgele oluşturulan cevap anahtarlarına göre öğrenci performanslarını simüle edebilmekte ve detaylı istatistiksel analizler yapabilmektedir.

Temel olarak, sistem şu işlevleri yerine getirmektedir: Öncelikle belirtilen sayıda soru için rastgele bir cevap anahtarı oluşturulmakta, ardından öğrenci sayısı ve belirlenen olasılıklar doğrultusunda (boş bırakma, doğru ve yanlış cevap olasılıkları) öğrenci cevapları simüle edilmektedir. Daha sonra her öğrenci için ham başarı notu (HBN) hesaplanmakta, bu notlar üzerinden sınıf ortalaması ve standart sapma gibi istatistikler elde edilmektedir.

Sistemin en önemli özelliklerinden biri, hesaplanan bu istatistiklere dayanarak her öğrenci için T-skoru ve harf notu belirleyebilmesidir. Ayrıca, sınıfın genel performans düzeyini "Üstün Başarı"dan "Zayıf"a kadar çeşitli kategorilerde değerlendirebilmektedir. Bu özellikler, eğitimcilerin sınav sonuçlarını bütünsel olarak analiz edebilmeleri ve öğrenci performanslarını objektif kriterlere göre değerlendirebilmeleri için tasarlanmıştır.

Programın kullanıcı dostu arayüzü sayesinde, kullanıcılar yalnızca temel parametreleri (öğrenci sayısı, soru sayısı, olasılık değerleri) girerek kapsamlı bir sınav analiz raporu alabilmektedir. Bu rapor, hem bireysel öğrenci performanslarını hem de sınıfın genel başarı düzeyini anlamaya yönelik detaylı bilgiler içermektedir.
## Özellikler
- Rastgele cevap anahtarı oluşturma
- Öğrenci cevaplarını simüle etme
- Ham başarı notu (HBN) hesaplama
- Sınıf istatistikleri (ortalama, standart sapma)
- Otomatik harf notu atama
## Girdiler
Program çalıştığında sizden şu bilgileri isteyecektir:
- Öğrenci sayısı (en fazla 100)
- Soru sayısı
- Boş bırakma olasılığı (0-1 arası)
- Doğru cevap verme olasılığı (0-1 arası)
## Örnek Çıktı
```
CEVAP ANAHTARI:
001: A | 002: B | 003: C | ...

1. öğrencinin HBN: 75.00, T-skoru: 68.50, harf notu: BA
Sınıf Ortalaması: 62.50
Standart Sapma: 12.30
Sınıf Düzeyi: Çok iyi
```
