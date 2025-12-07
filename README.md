# ⚖️ Oktay Hukuk Bürosu Web Sitesi

> **Kocaeli Üniversitesi - Bilişim Sistemleri Mühendisliği**
> **2025-2026 Güz Dönemi | Web Tasarımı Dersi Projesi**

Bu proje, modern web tasarım standartlarına uygun, responsive (mobil uyumlu) ve kullanıcı deneyimi odaklı geliştirilmiş kurumsal bir hukuk bürosu web sitesidir. Proje kapsamında hem ön yüz (Front-End) hem de yönetim paneli (Admin Dashboard) simülasyonu tasarlanmıştır.

## 🔗 Canlı Önizleme (Live Demo)
Projeyi canlı sunucuda incelemek için:
👉 **[CANLI SİTEYE GİT](https://emirhanok1.github.io/hukuk-burosu-web-sitesi/)**

---

## 💻 Proje Hakkında
* **Geliştirici:** Emirhan Oktay
* **Öğrenci No:** 231307074
* **Ders:** TBL303 - Web Tasarımı

## 🚀 Temel Özellikler

Proje, "Kanun" HTML şablonu altyapısı üzerine inşa edilmiş, ancak proje isterleri doğrultusunda **%80 oranında** özelleştirilerek yeniden kodlanmıştır.

### 🎨 Ön Yüz (Front-End)
* **Responsive Yapı:** Bootstrap 4 grid sistemi ile tüm cihazlarda (Mobil, Tablet, PC) kusursuz görünüm.
* **Dinamik Slider:** 3.5 saniye geçiş süreli, animasyonlu ve "Call-to-Action" butonlu manşet alanı.
* **Modal (Popup) Entegrasyonu:** Hizmetler ve duyurulara tıklandığında sayfa yenilenmez; detaylar **Bootstrap Modal** içinde açılır.
* **İstatistik Grafiği:** `Chart.js` kütüphanesi ile "Kazanılan Davalar" ve "Tecrübe" verilerini sunan dinamik grafik.
* **Kurumsal Kimlik:** Renkler, hukuk sektörüne uygun **Koyu Lacivert (#0e1c36)** ve **Altın Sarısı (#aa9166)** olarak revize edildi.
* **Tipografi:** Google Fonts (*Cinzel* ve *Montserrat*) kullanılarak modern bir logo ve metin hiyerarşisi oluşturuldu.

### 🛠️ Arka Yüz Simülasyonu (Admin Paneli)
Sunucu taraflı kodlama (Backend) yapılmadan, **Client-Side (Tarayıcı Tabanlı)** çözümlerle yönetim paneli mantığı kuruldu.
* **Panel Tasarımı:** `SB Admin 2` teması projeye entegre edildi.
* **Veri Giriş Ekranı:** "Duyuru Ekle" sayfası tasarlandı (Başlık, Kategori, Resim ve **Dosya Yükleme** alanları).
* **Dummy Data (DOM Manipülasyonu):** Admin panelinden girilen veriler, JavaScript ile yakalanarak sayfa yenilenmeden tabloya eklenir (Simülasyon).
* **Login Sistemi:** Basit bir JavaScript algoritması ile şifreli giriş ekranı simüle edildi.

## 📂 Kullanılan Teknolojiler
* **Core:** HTML5, CSS3, JavaScript (ES6)
* **Framework:** Bootstrap 4
* **Libraries:** jQuery, Chart.js, OwlCarousel, FontAwesome 5
* **Tools:** VS Code, GitHub Desktop

## ⚙️ Kurulum (Local)
Bu projeyi bilgisayarınızda çalıştırmak için:

1.  Repoyu klonlayın:
    ```bash
    git clone [https://github.com/emirhanok1/hukuk-burosu-web-sitesi.git](https://github.com/emirhanok1/hukuk-burosu-web-sitesi.git)
    ```
2.  Klasör içindeki `index.html` dosyasını tarayıcınızda açın.

---
*Bu proje eğitim amaçlı geliştirilmiştir.*
