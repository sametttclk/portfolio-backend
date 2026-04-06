# 🚀 Portfolio Backend | Java & Spring Boot

Bu proje, kişisel portfolyo sitemin veri yönetimini ve blog içeriklerini sağlayan ana API servisidir. Modern backend pratikleri ve bulut mimarisi hedeflenerek geliştirilmektedir.

## 🛠️ Teknolojiler
- **Java 21 (LTS)** & **Spring Boot 3.5.13**
- **Spring Data JPA** (Veri erişim katmanı)
- **H2 Database** (Yerel geliştirme ve test için)
- **PostgreSQL** (Üretim ortamı için)
- **Lombok** (Boilerplate kod azaltımı)
- **Spring Security** (Güvenlik ve Yetkilendirme)

## 🏗️ Mimari Yapı
Proje, **Layered Architecture** (Katmanlı Mimari) prensiplerine göre yapılandırılmıştır:
- `Controller`: API uç noktaları.
- `Service`: İş mantığı (Business Logic).
- `Repository`: Veritabanı etkileşimi.
- `Entity`: Veri modelleri.

## ☁️ Deployment
API servisi **Oracle Cloud (OCI)** üzerinde, Ubuntu Instance içerisinde Dockerize edilerek barındırılmaktadır.

## ⚙️ Yerel Kurulum
1. Repoyu clone'layın: `git clone https://github.com/sametttclk/portfolio-backend.git`
2. `src/main/resources/` altına bir `application.properties` dosyası oluşturun.
3. Projeyi çalıştırın: `./mvnw spring-boot:run`