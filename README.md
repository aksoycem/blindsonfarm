# Köroğlu Tarım - Sürdürülebilir Tarım Web Sitesi

Modern, responsive ve GitHub Pages'de çalışan basit HTML/CSS/JavaScript web sitesi.

## 🚀 Özellikler

- **Video Hero Section**: Arka plan videosu ile dinamik giriş sayfası
- **Animasyonlu Logo**: Özel tasarım logo ile marka kimliği
- **4 Ana Navigasyon**: Hakkımızda, Ürünlerimiz, Ar-Ge, İletişim
- **Ar-Ge Bölümü**: İnovasyon ve teknoloji odaklı içerik
- **Tanıtım Videosu**: Drone çekimleri ile hazırlanan video bölümü
- **Responsive Tasarım**: Tüm cihazlarda mükemmel görünüm
- **Modern UI/UX**: Profesyonel tarım sitesi tasarımı
- **Smooth Animasyonlar**: CSS ve JavaScript ile
- **SEO Optimized**: Arama motorları için optimize edilmiş
- **Accessibility**: WCAG uyumlu
- **Fast Loading**: Optimize edilmiş görseller ve kod
- **GitHub Pages Ready**: Direkt GitHub'da yayınlanabilir

## 📁 Dosya Yapısı

```
koroglu-tarim-simple/
├── index.html          # Ana sayfa
├── style.css           # CSS stilleri
├── script.js           # JavaScript fonksiyonları
├── images/             # Görseller
│   ├── hero-bg.jpg     # Hero arka plan (fallback)
│   ├── sustainability.jpg
│   ├── r-d.jpg         # Ar-Ge görseli
│   ├── video-poster.jpg # Video poster
│   ├── portakal.jpg
│   ├── mandalina.jpg
│   ├── limon.jpg
│   ├── greyfurt.jpg
│   ├── nar.jpg
│   ├── incir.jpg
│   ├── zeytin.jpg
│   ├── pamuk.jpg
│   └── og.jpg          # Open Graph görseli
├── videos/             # Video dosyaları
│   ├── hero-video.mp4  # Hero arka plan videosu
│   ├── hero-video.webm # Hero video (WebM format)
│   ├── promotional-video.mp4 # Tanıtım videosu
│   └── promotional-video.webm # Tanıtım video (WebM)
├── favicon.ico         # Site ikonu
└── README.md           # Bu dosya
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

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

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

**Köroğlu Tarım** - Çukurova'nın bereketli topraklarında sürdürülebilir tarım 🌱
