# 🌱 Köroğlu Agriculture - Sustainable Farming Website

A modern, responsive website built for my friend's agricultural company. This project represents the digital presence of Köroğlu Agriculture, a family-owned farming business in Çukurova, Turkey, with over 50 years of experience in sustainable agriculture.

> **Note**: I'm proud to have built this website to help my friend establish their agricultural company's online presence. It was truly a pleasure to contribute to their business journey.

## 🎯 Project Purpose

This website serves as the official digital platform for Köroğlu Agriculture, showcasing their:
- Premium citrus and fruit products
- Sustainable farming practices since 1970
- R&D initiatives and innovation
- Company history and values
- Contact information for business inquiries

## ✨ Features

- **🎥 Video Hero Section**: Dynamic landing page with background video
- **🎨 Animated Logo**: Custom-designed brand identity with animations
- **🧭 Dual Language Support**: Full English and Turkish versions (index.html & index_tr.html)
- **📱 Fully Responsive**: Perfect display on all devices (mobile, tablet, desktop)
- **🎬 Promotional Video**: Showcase section with company introduction video
- **📊 Timeline Section**: Animated company history from 1970 to present
- **🍊 Product Showcase**: Grid layout featuring 8 premium products
- **🔬 R&D Section**: Innovation and technology-focused content
- **💬 WhatsApp Integration**: Floating button + dedicated contact card
- **📞 Contact Cards**: Beautiful contact section with phone, email, address, and WhatsApp
- **🎯 SEO Optimized**: Complete meta tags, sitemap, robots.txt, and structured data
- **⚡ Fast Loading**: Optimized images and code
- **♿ Accessible**: WCAG compliant design
- **🚀 GitHub Pages Ready**: Deploy directly from repository

## 📁 File Structure

```
koroglu-tarim-simple/
├── index.html                      # Main page (English)
├── index_tr.html                   # Turkish version
├── style.css                       # All CSS styles
├── script.js                       # JavaScript functionality
├── sitemap.xml                     # SEO sitemap
├── robots.txt                      # Search engine instructions
├── images/                         # Image assets
│   ├── logo.png                    # Company logo
│   ├── logo.svg                    # Logo (vector)
│   ├── 1970 ilk adımlar kısmı.jpeg # Timeline: 1970
│   ├── 2003 ilk bahçemiz kısmı.jpeg # Timeline: 2003
│   ├── 2022 şirketleşme kısmı.jpeg # Timeline: 2022
│   ├── bugün kısmı.jpeg            # Timeline: Today
│   ├── biz kimiz misyon kısmı.jpeg # About section background
│   ├── arge yaklaşım kısmı.jpeg    # R&D section image
│   ├── portakal.jpeg               # Product: Orange
│   ├── mandalina.jpeg              # Product: Mandarin
│   ├── limon.jpeg                  # Product: Lemon
│   ├── nar.jpeg                    # Product: Pomegranate
│   ├── şeftali.jpeg                # Product: Peach
│   ├── kayısı.jpeg                 # Product: Apricot
│   ├── nektarin.jpeg               # Product: Nectarine
│   └── mısır.jpeg                  # Product: Corn
├── videos/                         # Video files
│   ├── hero-video.mp4              # Hero background video
│   └── WhatsApp Video 2025-11-01.mp4 # Promotional video
├── favicon.ico                     # Site icon
└── README.md                       # This file
```

## 🆕 Yeni Özellikler

### Video Hero Section
- Arka plan videosu ile dinamik giriş sayfası
- Otomatik oynatma, sessiz ve döngü
- Fallback görsel desteği
- Mobil uyumlu video oynatma

### Animasyonlu Logo
- Özel tasarım logo elementi
- Güneş, tarla çizgileri ve yaprak animasyonları
- Meyve ikonları ile canlı görünüm
- Responsive logo tasarımı

### 4 Ana Navigasyon
- **Hakkımızda**: Şirket bilgileri ve değerler
- **Ürünlerimiz**: Ürün kataloğu
- **Ar-Ge**: İnovasyon ve teknoloji
- **İletişim**: İletişim bilgileri ve form

### Ar-Ge Bölümü
- Koyu yeşil arka plan ile profesyonel görünüm
- Turuncu vurgu renkleri
- İnovasyon odaklı içerik
- Görsel destekli sunum

### Tanıtım Videosu
- Drone çekimleri ile hazırlanan video
- Play butonu ile interaktif oynatma
- Poster görsel desteği
- Responsive video player

## 🎨 Tasarım Sistemi

### Renkler
- **Leaf**: #49663D (Ana yeşil)
- **Sage**: #AFC39A (Açık yeşil)
- **Sand**: #E8D3BD (Kum rengi)
- **Clay**: #E5863A (Turuncu)
- **Ink**: #2A2A2A (Koyu gri)
- **Milk**: #FAF9F7 (Açık krem)
- **Dark Green**: #2D4A2A (Koyu yeşil)
- **Light Green**: #8FBC8F (Açık yeşil)
- **Orange**: #FF8C00 (Turuncu)
- **Cream**: #F5F5DC (Krem)

### Tipografi
- **Başlıklar**: Cormorant Garamond (Serif)
- **Metin**: Inter (Sans-serif)

## 🛠️ Kurulum

### GitHub Pages'de Yayınlama

1. **Repository Oluştur**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/aksoycem/blindsonfarm.git
   git push -u origin main
   ```

2. **GitHub Pages Aktif Et**:
   - Repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)

3. **Site URL**: `https://aksoycem.github.io/blindsonfarm`

### Yerel Geliştirme

1. **Dosyaları İndir**:
   ```bash
   git clone https://github.com/aksoycem/blindsonfarm.git
   cd blindsonfarm
   ```

2. **Basit HTTP Server**:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   
   # PHP
   php -S localhost:8000
   ```

3. **Tarayıcıda Aç**: `http://localhost:8000`

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Bölümler

1. **Hero**: Ana başlık ve CTA
2. **Hakkımızda**: Misyon, vizyon, değerler
3. **Sürdürülebilirlik**: Çevre dostu uygulamalar
4. **Tarihçe**: Şirket geçmişi timeline
5. **Ürünler**: Ürün kartları grid
6. **İletişim**: Form ve iletişim bilgileri

## ⚡ Performans

- **Lazy Loading**: Görseller için
- **CSS Minification**: Production için
- **Image Optimization**: WebP format
- **Critical CSS**: Above-the-fold
- **Font Preloading**: Hızlı yükleme

## 🔧 Özelleştirme

### Renkleri Değiştirme
`style.css` dosyasında `:root` bölümündeki CSS değişkenlerini düzenleyin:

```css
:root {
    --color-leaf: #49663D;
    --color-clay: #E5863A;
    /* Diğer renkler... */
}
```

### İçerik Güncelleme
`index.html` dosyasında ilgili bölümleri düzenleyin.

### Görsel Ekleme
`images/` klasörüne yeni görseller ekleyin ve HTML'de referans verin.

## 📞 İletişim Bilgileri

- **Ad Soyad**: Haşim Alphan Köroğlu
- **Telefon**: +90 536 054 45 45
- **E-posta**: alphankoroglu03@gmail.com
- **Adres**: Yunusoğlu Mah. Yunusoğlu Sok. No:117, Tarsus/Mersin Türkiye

## 🔒 Privacy & Security Notice

This repository contains publicly accessible information about Köroğlu Agriculture. All contact information, business details, and media content shared here are:

- **Publicly Available**: Contact details (phone, email, address) are intentionally public for business purposes
- **Business Information**: All company information is meant for public viewing and customer outreach
- **No Sensitive Data**: No private customer data, financial information, or confidential business secrets are stored in this repository
- **Media Rights**: All images and videos are owned by Köroğlu Agriculture and used with permission
- **Open Source**: The code is open source, but the brand assets and content remain property of Köroğlu Agriculture

### ⚠️ Important Notes

- **Contact Information**: The phone number, email, and address displayed are official business contact points
- **WhatsApp Integration**: The WhatsApp link is intentionally public for customer communication
- **No Personal Data Collection**: This static website does not collect, store, or process any user data
- **Third-Party Services**: Links to external services (Google Maps, WhatsApp) are governed by their respective privacy policies

## 📄 License

**Code**: MIT License - Feel free to use the code structure and design patterns  
**Content & Brand Assets**: © 2024 Köroğlu Agriculture - All rights reserved

The website code (HTML, CSS, JavaScript) is open source under MIT License. However, all brand-specific content including:
- Company name and logo
- Product images and videos
- Business information and text content
- Promotional materials

...remain the intellectual property of Köroğlu Agriculture and may not be used without permission.

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Commit yapın (`git commit -m 'Add amazing feature'`)
4. Push yapın (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📈 Gelecek Özellikler

- [ ] Çoklu dil desteği
- [ ] Blog bölümü
- [ ] Ürün detay sayfaları
- [ ] Online sipariş sistemi
- [ ] Müşteri yorumları
- [ ] Newsletter kayıt
- [ ] Sosyal medya entegrasyonu

---

## 💚 Acknowledgments

This website was built with care and dedication to support my friend's agricultural business. I'm honored to contribute to Köroğlu Agriculture's digital journey and help showcase their commitment to sustainable farming.

**Special Thanks**:
- To Haşim Alphan Köroğlu for trusting me with this project
- To the Köroğlu family for their 50+ years of dedication to sustainable agriculture
- To everyone who supports local, sustainable farming practices

---

**Köroğlu Agriculture** - Sustainable farming in the fertile lands of Çukurova since 1970 🌱

**Live Website**: [https://aksoycem.github.io/blindsonfarm/](https://aksoycem.github.io/blindsonfarm/)
