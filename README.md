# SSPE-Wave-Propagation: Split-Step Parabolic Equation Method

Üsküdar Üniversitesi Elektrik-Elektronik Mühendisliği Yüksek Lisans / Lisansüstü **Computational Electromagnetics (EEE510)** dersi kapsamında, Prof. Dr. Gökhan Apaydın danışmanlığında geliştirilen elektromanyetik dalga yayılım simülasyonu projesi.

## 📌 Proje Özeti
Bu çalışma; karmaşık araziler, yerküre eğriliği ve atmosferik ducting (buharlaşma kanalları) gibi uzun menzilli elektromanyetik dalga yayılım problemlerini çözmek için **Split-Step Parabolic Equation (SSPE)** yönteminin matematiksel türetimini, sayısal sınır koşullarını ve MATLAB tabanlı uygulama aşamalarını inceler.

## 🛠 Temel Başlıklar ve İçerik
* **Matematiksel Temel:** 2D Helmholtz dalga denkleminden Standart Parabolic Equation (SPE) ve Wide-Angle Parabolic Equation (WAPE) türetimleri.
* **Algoritmik Yaklaşım:** Operatör Parçalama (Operator Splitting) ve Hızlı Fourier Dönüşümü (FFT) tabanlı adımlama motoru.
* **Sınır Koşulları:** Düşük yüzey sınırları (Method of Images) ve üst sınır yansımalarını önleyen **Tukey Snger Layer (Apodization)** pencereleme teknikleri.
* **Çevresel Modelleme:** Düz Dünya Dönüşümü (Flat-Earth), Modifiye Refraktivite ($M$-profile) ile buharlaşma kanalları ve merdiven yaklaşımıyla (staircase approximation) engebeli arazi maskelemesi.
* **MATLAB Benzetimleri:** Faz birikimi, Nyquist örnekleme sınırları ve donanım/bellek maliyet optimizasyonları.

## 📂 Depo İçeriği
* `split-step-parabolic-equation-method-sspe.pdf` / `.docx`: Projenin resmi teknik mühendislik raporu.
* `SSPE_Wave_Propagation.pptx`: Deri sunumu ve savunma slaytları.
