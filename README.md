# 📷 Plaka Tanımlı Otomatik Garaj Kapısı Sistemi

## 🚗 Proje Hakkında

Bu proje, araç plakalarının görüntü işleme yoluyla tanınarak garaj kapısının otomatik olarak açılmasını sağlayan bir sistemdir. Sistem, plakanın daha önce tanımlı olup olmadığına göre hareket eder ve duruma göre sesli ve görsel uyarılar verir.

## 🧠 Kullanılan Teknolojiler

- 🧠 **YOLOv3 (You Only Look Once)** – Plaka tanıma modeli olarak kullanıldı.
- 💻 **Python (OpenCV, NumPy, Serial)** – Görüntü işleme ve Arduino ile haberleşme için.
- 🔌 **Arduino (C++)** – Servo motor kontrolü, sensör okuma ve OLED ekran yönetimi için.
- 🧪 **Google Colab** – YOLOv3 eğitimi için kullanıldı (800 plaka fotoğrafı ile).
- 🖥️ **Spyder IDE** – Python tarafındaki yazılım geliştirme için.
- 📟 **OLED Ekran & Servo Motor** – Kapı açma ve bilgilendirme işlemleri için.

## 🔧 Sistem Özellikleri

- Plaka tanıma algoritması ile istenilen araç tespiti
- %95 doğruluk oranı ile çalışan YOLOv3 modeli
- Arduino üzerinden servo motor ile garaj kapısının açılması
- OLED ekran ve sesli uyarılarla sistem durumu bildirimi
- Tanımlı ve yabancı araçlar için farklı senaryolar
- Ultrasonik sensör ile güvenli kapama işlemi
