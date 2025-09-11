# 🚀 GitHub Pages Deployment Guide

Bu rehber, Köroğlu Tarım web sitesini GitHub Pages'de yayınlamak için adım adım talimatlar içerir.

## 📋 Ön Gereksinimler

- GitHub hesabı
- Git yüklü (opsiyonel, GitHub web arayüzü de kullanılabilir)

## 🔧 Yöntem 1: GitHub Web Arayüzü (Kolay)

### 1. Repository Oluştur
1. GitHub'a giriş yap: https://github.com
2. "New repository" butonuna tıkla
3. Repository adı: `koroglu-tarim` (veya istediğin isim)
4. "Public" seç (GitHub Pages ücretsiz sadece public repo'larda)
5. "Create repository" tıkla

### 2. Dosyaları Yükle
1. "uploading an existing file" linkine tıkla
2. Tüm dosyaları sürükle-bırak ile yükle:
   - `index.html`
   - `style.css`
   - `script.js`
   - `images/` klasörü (tüm görsellerle birlikte)
   - `README.md`
   - `.gitignore`
   - `CNAME` (opsiyonel, custom domain için)

3. Commit message: "Initial commit: Köroğlu Tarım website"
4. "Commit changes" tıkla

### 3. GitHub Pages Aktif Et
1. Repository'de "Settings" sekmesine git
2. Sol menüden "Pages" seç
3. Source: "Deploy from a branch" seç
4. Branch: "main" seç
5. Folder: "/ (root)" seç
6. "Save" tıkla

### 4. Site URL
- GitHub Pages URL: `https://kullanici-adi.github.io/koroglu-tarim`
- Custom domain (CNAME dosyası varsa): `https://koroglu-tarim.com`

## 🔧 Yöntem 2: Git Komut Satırı (Gelişmiş)

### 1. Repository Oluştur
```bash
# GitHub'da repository oluştur (web arayüzü ile)
# Sonra local'de:
git init
git add .
git commit -m "Initial commit: Köroğlu Tarım website"
git branch -M main
git remote add origin https://github.com/KULLANICI-ADI/koroglu-tarim.git
git push -u origin main
```

### 2. GitHub Pages Aktif Et
- Repository Settings > Pages
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

## 🌐 Custom Domain (Opsiyonel)

### 1. Domain Satın Al
- Domain sağlayıcısından domain satın al
- Örnek: `koroglu-tarim.com`

### 2. DNS Ayarları
Domain sağlayıcısında DNS kayıtları:
```
Type: CNAME
Name: www
Value: kullanici-adi.github.io

Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

### 3. CNAME Dosyası
Repository'de `CNAME` dosyası oluştur:
```
koroglu-tarim.com
```

## 📱 Test Etme

### 1. GitHub Pages URL
- `https://kullanici-adi.github.io/koroglu-tarim`

### 2. Mobile Test
- Google Mobile-Friendly Test: https://search.google.com/test/mobile-friendly
- URL'yi test et

### 3. Performance Test
- Google PageSpeed Insights: https://pagespeed.web.dev/
- URL'yi test et

## 🔄 Güncelleme

### Web Arayüzü ile:
1. Repository'de dosyayı düzenle
2. "Commit changes" tıkla
3. Otomatik olarak yeniden deploy olur

### Git ile:
```bash
git add .
git commit -m "Update: yeni özellik"
git push origin main
```

## 🛠️ Sorun Giderme

### Site Açılmıyor
1. Repository Settings > Pages kontrol et
2. Branch ve folder ayarları doğru mu?
3. Dosya yolları doğru mu? (`index.html` root'ta olmalı)

### Görseller Yüklenmiyor
1. `images/` klasörü yüklendi mi?
2. Dosya yolları doğru mu? (`./images/portakal.jpg`)
3. Dosya isimleri büyük/küçük harf duyarlı

### CSS/JS Çalışmıyor
1. Dosya yolları doğru mu?
2. HTML'de linkler doğru mu?
3. Browser console'da hata var mı?

### Custom Domain Çalışmıyor
1. DNS ayarları doğru mu?
2. CNAME dosyası var mı?
3. 24-48 saat bekle (DNS propagation)

## 📊 Analytics (Opsiyonel)

### Google Analytics
1. Google Analytics hesabı oluştur
2. Tracking code'u `index.html`'e ekle:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### GitHub Insights
- Repository'de "Insights" sekmesi
- Traffic ve visitor bilgileri

## 🎯 SEO Optimizasyonu

### 1. Meta Tags
`index.html`'de mevcut meta taglar optimize edilmiş

### 2. Sitemap
GitHub Pages otomatik sitemap oluşturur:
- `https://kullanici-adi.github.io/koroglu-tarim/sitemap.xml`

### 3. Robots.txt
Repository root'unda `robots.txt` oluştur:
```
User-agent: *
Allow: /

Sitemap: https://kullanici-adi.github.io/koroglu-tarim/sitemap.xml
```

## 🚀 Sonuç

Site başarıyla yayınlandıktan sonra:
- ✅ Responsive tasarım
- ✅ Modern UI/UX
- ✅ SEO optimized
- ✅ Fast loading
- ✅ Mobile-friendly
- ✅ GitHub Pages hosting

**Site URL**: `https://kullanici-adi.github.io/koroglu-tarim`

---

**Not**: Bu rehber GitHub Pages'in ücretsiz planı için hazırlanmıştır. Pro plan için ek özellikler mevcuttur.
