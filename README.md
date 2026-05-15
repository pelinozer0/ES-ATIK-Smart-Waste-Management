# ES-ATIK: Akıllı Atık Yönetimi ve Rota Optimizasyon Sistemi 🚛♻️

IoT tabanlı sensör simülasyonlarıyla çöp doluluk oranlarını takip eden ve Flutter ile geliştirilmiş mobil uygulama üzerinden en verimli toplama rotasını çıkaran, test süreçleri tamamlanmış bir akıllı şehir sistemi simülasyonudur.

## 🚀 Proje Hakkında (Project Overview)
Bu proje, Eskişehir Osmangazi Üniversitesi Bilgisayar Mühendisliği "Tasarım Süreçleri" dersi kapsamında geliştirilmiştir. Geleneksel atık toplama yöntemlerindeki verimsizliği (boş konteyner ziyareti, yakıt israfı vb.) veri odaklı bir yaklaşımla çözmeyi hedefler.

## ✨ Temel Özellikler (Key Features)
- **Dinamik Rota Optimizasyonu:** %60 doluluk eşiğini aşan konteynerler için otomatik ve en kısa rotayı oluşturma.
- **Vatandaş Paneli:** En yakın 5 konteyneri haritada görme ve taşma bildirimi gönderme.
- **Personel Paneli:** Canlı rota takibi ve toplanan konteynerlerin sistem üzerinden güncellenmesi.
- **Eko-Puan Sistemi:** Bildirim yapan vatandaşları teşvik eden oyunlaştırma altyapısı.

## 🛠️ Teknoloji Yığını (Tech Stack)
- **Frontend:** Flutter & Dart
- **Backend/Database:** MariaDB
- **IoT Simulation:** ESP32 & Ultrasonic Sensors (Conceptual Design)
- **API/Design Patterns:** Observer Pattern, Google Maps API

## 📋 Yazılım Test Süreçleri (Testing)
Proje, V-Model yazılım geliştirme döngüsüne uygun olarak test edilmiştir:
- **Birim (Unit) Testleri:** Doluluk hesaplama ve puanlama algoritmalarının doğrulanması.
- **Entegrasyon Testleri:** UI ve veritabanı arasındaki veri akışının senkronizasyonu.
- **Sistem Testleri:** Rol bazlı erişim kontrolü ve rota oluşturma performansı.

## 💡 Kişisel Katkım (Personal Contribution)
Bu proje 4 kişilik bir ekip çalışması olarak yürütülmüştür. Benim bu süreçteki temel sorumluluklarım:
- **Sistem Mimarisi ve Tasarımı:** Projenin kavramsal sistem tasarımının kurgulanması.
- **Yazılım Test Senaryoları:** Black-box ve White-box test senaryolarının kurgulanması ve dökümante edilmesi.
- **Raporlama:** Analiz, tasarım ve test süreçlerinin profesyonel mühendislik standartlarında raporlanması.

## 📄 Proje Dokümanları (Project Documentation)
Projenin tüm akademik detaylarına aşağıdaki PDF belgelerinden ulaşabilirsiniz:

* [Final Raporu (Final Report)](./docs/ES_ATIK_Final_Report.pdf)
* [Ara Rapor (Midterm Report)](./docs/ES_ATIK_Midterm_Report.pdf)
* [Final Sunumu (Final Presentation)](./docs/ES_ATIK_Final_Presentation.pdf)

---
*Bu proje akademik bir simülasyon çalışmasıdır.*
