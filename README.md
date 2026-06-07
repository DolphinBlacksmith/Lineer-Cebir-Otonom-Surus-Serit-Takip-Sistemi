# Otonom Araç Sürüş Güvenliği İçin Bilgisayarlı Görü Tabanlı KDS Pipeline

Bu proje; otonom araç yazılımlarında yüksek hesaplama maliyeti getiren derin öğrenme modellerine alternatif olarak, endüstriyel gömülü sistemlerde gerçek zamanlı (real-time) çalışabilecek, hafif ve deterministik bir şerit takip ve akıllı **Karar Destek Sistemi (KDS)** mimarisi sunmaktadır. 

Udacity Otonom Sürüş Veri Seti'nden alınan zamansal olarak ardışık **5000 adet sürüş karesi** üzerinde test edilen sistem; şerit segmentasyonu verilerini işleyerek otonom direksiyon müdahale kararları ve rota planlaması üretmektedir.

---

## 🚀 Proje Özellikleri & Senaryo Yönetimi

Geliştirilen kural tabanlı KDS motoru, şerit merkezinden piksel sapma indeksini milisaniyeler düzeyinde analiz ederek şu dinamik otonom sürüş senaryolarını yönetmektedir:
* **Sol Şerit Daralması / Yol Sonu:** Sağ şeride güvenli geçiş manevrası planlar (%15 Sağ direksiyon).
* **Sağda Engel / Şerit Sonu:** Sol şeride güvenli geçiş manevrası planlar (%15 Sol direksiyon).
* **Şerit İhlali / Kayma Riski:** Aracı şerit içinde tutmak için hafif merkezleme müdahalesi yapar (%5 Sağ/Sol).
* **İdeal Sürüş Modu:** Şerit kararlılığı sağlandığında otopilot modunu aktif tutar (%0 Düz).

---

## 📊 Önemli Bağlantılar (Veri Seti & Çıktılar)

* **Google Colab Çalışma Ortamı:** https://drive.google.com/file/d/1NdEFtuK_MY1hE5Bj7GWv8fM_DHWAPO_r/view?usp=sharing
* **Proje Büyük Veri Seti (5000 Kare):** https://drive.google.com/drive/folders/1auMESfo_SWo_GhC-mDez87J2ksOzT8Js?usp=sharing
* **Otonom HUD Örnek Segmentasyon Videosu (Google Drive):** https://drive.google.com/drive/folders/1auMESfo_SWo_GhC-mDez87J2ksOzT8Js?usp=sharing
* **Nihai Proje Makalesi (PDF / HTML Gösterimi):**

---
👤 Geliştirici Bilgileri
Adı Soyadı: YunusEmre Demirci

Öğrenci Numarası: 2404040249

Bölüm: Yazılım Mühendisliği Bölümü

İletişim / GitHub: @DolphinBlacksmith
