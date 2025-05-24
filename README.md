
# Uçak Bilet Rezervasyon Sistemi – Java OOP Console Application

## Proje Hakkında

Bu proje, Java Nesne Yönelimli Programlama (OOP) prensipleriyle geliştirilmiş bir uçak bileti rezervasyon sistemidir. Konsol üzerinden çalışan bu uygulama ile uçuşlar listelenebilir, yolcu bilgileri girilerek rezervasyon yapılabilir ve tüm veriler yerel olarak  CSV dosyasına  kaydedilebilir.


## Kullanılan Yapılar

- Class, Abstract Class, Interface kavramları
- Java Collections (ArrayList)
- Tarih/saat işlemleri (LocalDate, LocalDateTime, Period)
- Kullanıcı etkileşimi (Scanner)
- Veri formatlama (DateTimeFormatter)
- Dosya işlemleri (CSV formatında veri kaydetme)

 ## Temel Classlar

- Ucak.java
  Uçak bilgilerini içerir. (Model, Marka, Seri No, Kapasite, Durum)

- Lokasyon.java
  Lokasyon bilgilerini tutar. (Ülke, Şehir, Havalimanı, Aktiflik)

- Ucus.java  
  Uçuşa ait kalkış/varış lokasyonu, saat, uçak ve temel fiyat gibi bilgiler içerir.

- Rezervasyon.java  
  Uçuşa bağlı olarak, yolcu bilgileri ve ödenen tutarı içerir.

## Kullanım

1. Uygulama başlatıldığında menü üzerinden:
   - Mevcut uçuşlar listelenebilir
   - Rezervasyon yapılabilir
   - Yapılmış rezervasyonlar görüntülenebilir

2. Yolcu bilgileri alındıktan sonra yaşa göre ücret hesaplanır:
   - 2–12 yaş arası %50 indirim uygulanır.

3. Rezervasyonlar uygulama içinde saklandığı gibi, dışa aktarılabilir (CSV olarak).

 
## Nasıl Çalıştırılır?

1. Java 11 veya üzeri bir sürüm yüklü olmalıdır.
2. IntelliJ IDEA gibi bir IDE ile proje açılabilir.
3. UcakRezervasyonSistemi.java sınıfı çalıştırılarak konsol uygulaması başlatılır.
