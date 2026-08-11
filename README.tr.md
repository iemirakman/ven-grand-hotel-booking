# 🏨 Ven Grand Hotel - Web Platform

[![Canlı Demo](https://img.shields.io/badge/Canl%C4%B1_Demo-Ven_Grand_Hotel-blue?style=for-the-badge)](https://ven-grand-hotel.page.gd/?i=1)

---

<div align="center">

[![Türkçe](https://img.shields.io/badge/Dil-T%C3%BCrk%C3%A7e-red.svg?style=for-the-badge)](README.tr.md)
[![English](https://img.shields.io/badge/Language-English-blue.svg?style=for-the-badge)](README.md)

</div>

---

Ven Grand Hotel, WordPress kullanılarak inşa edilmiş kapsamlı, uçtan uca bir konaklama hizmeti platformudur. Bu proje, lüks bir otelin çevrimiçi varlığını dijitalleştirmek, tamamen işlevsel bir rezervasyon motorunu entegre etmek ve müşteri etkileşimlerini yönetmek amacıyla Burdur Mehmet Akif Ersoy Üniversitesi'ndeki İçerik Tasarımı dersi için final projesi olarak geliştirilmiştir.

## 🚀 Özellikler

* **Gerçek Zamanlı Rezervasyon Motoru:** Oda tahsisi, dönemsel fiyatlandırma ve gerçek zamanlı müsaitlik kontrolleri için VikBooking ile entegre edildi.
* **Yapay Zeka Destekli Müşteri Desteği:** 7/24 anlık ziyaretçi iletişimi için Tidio AI chatbot entegrasyonu.
* **Duyarlı ve Premium Arayüz:** Tüm cihazlarda kesintisiz ve mobil optimize bir deneyim için Astra Tema ve Elementor ile oluşturuldu.
* **Performans Optimizasyonu:** Bulut barındırma üzerinde hızlı sayfa yükleme süreleri sağlamak için LiteSpeed Cache ve WebP görsel optimizasyonu ile yapılandırıldı.
* **Özel Yerelleştirme:** Yerel pazar için Loco Translate kullanılarak karmaşık rezervasyon arka uç sistemleri tamamen Türkçe'ye çevrildi.
* **Dinamik Formlar:** SureForms aracılığıyla yönetilen güvenli ve modern müşteri talep formları.

## 🛠️ Teknoloji Yığını ve Altyapı

* **CMS (İçerik Yönetim Sistemi):** WordPress (v6.9.4)
* **Tema/Tasarım:** Astra Theme, Elementor, Ultimate Addons
* **Temel Eklentiler:** VikBooking (Rezervasyon Sistemi), Tidio (Yapay Zeka Sohbeti), Loco Translate (Yerelleştirme), LiteSpeed Cache (Performans)
* **Veritabanı Yönetimi:** Gelişmiş MySQL ilişkileri (örneğin, `wp_vikbooking_rooms`, `wp_vikbooking_reservations`)
* **Barındırma (Hosting):** InfinityFree (PHP/MySQL tabanlı bulut kurulumu)

## 📸 Arayüz Ekran Görüntüleri

*(Not: Tam çözünürlükte görüntülemek için görsellerin üzerine tıklayın.)*

### Ana Sayfa
Yüksek çözünürlüklü görseller ve hızlı arama rezervasyon aracı içeren dinamik bir açılış sayfası.
![Ana Sayfa](screenshots/anasayfa.png)

### Odalarımız
Oda tiplerinin (Standart, Deluxe, Süit) kapasite ve fiyatlandırmalarıyla birlikte detaylı listelemesi.
![Odalarımız](screenshots/odalarimiz.png)

### Rezervasyon Sistemi
VikBooking motoru üzerinde çalışan etkileşimli rezervasyon modülü.
![Rezervasyon](screenshots/rezervasyon-sayfasi.png)

### Hakkımızda ve İletişim
Kurumsal kimlik sayfaları ve harita entegrasyonlu dinamik iletişim formları.
![Hakkımızda](screenshots/hakkimizda.png)

![İletişim](screenshots/iletisim.png)

## 💡 Problem Çözümü ve Mimari

Geliştirme aşamasında çeşitli mimari zorluklar başarıyla çözülmüştür:
1.  **Yerelleştirme Engeli:** Temel rezervasyon motorunda yerleşik Türkçe desteğinin olmaması, Loco Translate kullanılarak PO/MO dosyalarının manuel olarak çevrilmesiyle aşıldı.
2.  **Kaynak Kısıtlamaları:** Paylaşımlı barındırmada yaşanan sunucu taraflı veritabanı bağlantı sorunları, agresif HTML/CSS küçültme (minification) ve WebP görsel sıkıştırma işlemleri uygulanarak çözüldü.
3.  **Canlıya Alma (Deployment):** Karmaşık yerel geliştirme ortamı (MAMP), All-in-One WP Migration kullanılarak canlı bulut sunucusuna sorunsuz bir şekilde taşındı; tüm kalıcı bağlantıların (permalinks) ve veritabanı ilişkilerinin eksiksiz aktarılması sağlandı.

## 👥 Geliştiriciler

* **İbrahim Emir Akman**

---
*Bu depo bir portföy vitrini niteliğindedir. UX tasarım sürecinin detaylı dökümü, veritabanı mantığı ve gelecekteki ticari ölçeklendirme planları (VPS geçişi, Stripe/İyzico entegrasyonu vb.) için lütfen ekteki [Proje Sunumu PDF dosyasını](./vengrandhotel_sunum.pdf) inceleyin.*
