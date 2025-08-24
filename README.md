# 🚀 Web Developer Portfolio - Bahattin Tok

Modern, responsive ve etkileşimli bir web developer portfolio'su. HTML5, CSS3, JavaScript ve Bootstrap kullanılarak geliştirilmiştir. **Animasyonlu orbit skills section** ve **proje video player** özellikleri ile öne çıkar.

## ✨ Öne Çıkan Özellikler

- **🎯 Orbit Skills Animation**: Teknoloji logolarının orbit üzerinde döndüğü etkileyici animasyon
- **🎬 Video Player Modals**: Proje demo videolarını modal içinde oynatma
- **📱 Responsive Design**: Tüm cihazlarda mükemmel görünüm
- **🎨 Modern UI/UX**: Gradient renkler, gölgeler ve modern tipografi
- **⚡ Smooth Animations**: AOS (Animate On Scroll) kütüphanesi ile akıcı animasyonlar
- **🔗 Project Modals**: Detaylı proje bilgileri için modal sistemi
- **📊 Interactive Elements**: Hover efektleri, smooth scroll ve dinamik içerik
- **🔍 SEO Optimized**: Semantic HTML yapısı
- **⚙️ Performance Optimized**: Optimize edilmiş kod ve lazy loading

## 🛠️ Kullanılan Teknolojiler

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern styling, CSS Grid, Flexbox, Keyframe Animations
- **JavaScript**: ES6+, DOM manipulation, custom animations
- **Bootstrap 5**: Responsive framework

### Libraries & Tools
- **Font Awesome**: İkonlar
- **Google Fonts**: Poppins, Inter, Lato, Rubik
- **AOS**: Scroll animasyonları
- **Typed.js**: Typing animasyonları

## 📁 Proje Yapısı

```
portfolio/
├── index.html              # Ana HTML dosyası
├── style.css               # CSS stilleri ve animasyonlar
├── script.js               # JavaScript fonksiyonları
├── img/                    # Proje görselleri
│   ├── main_photo.jpg
│   ├── e-commerce-home.png
│   ├── organic-foodd.png
│   └── weather-app.png
├── videos/                 # Proje demo videoları
│   ├── e-commerce-demo-video.mp4
│   ├── organic-food-demo-video.mp4
│   └── weather-app-demo-video.mp4
└── README.md               # Proje dokümantasyonu
```

## 🎨 Tasarım Özellikleri

### Renk Paleti
- **Primary**: #007bff (Mavi)
- **Secondary**: #6c757d (Gri)
- **Gradient Primary**: Linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- **Dark**: #343a40 (Koyu gri)
- **Success**: #28a745 (Yeşil)
- **Warning**: #ffc107 (Sarı)

### Fontlar
- **Primary**: Poppins (Başlıklar)
- **Secondary**: Inter (Metin)
- **Code**: Courier New (Kod blokları)

### Animasyonlar
- **Orbit Animation**: Teknoloji logolarının dairesel hareketi
- **Counter-rotation**: Logoların düz kalması için ters dönüş
- **Fade in/out**: Sayfa geçiş efektleri
- **Slide animations**: Yatay kaydırma animasyonları
- **Hover transformations**: Etkileşimli hover efektleri
- **Typing animation**: Yazı makinesi efekti
- **Progress bar animations**: İlerleme çubuğu animasyonları

## 🌟 Özel Özellikler

### 1. Orbit Skills Animation
```css
/* Frontend ve Backend için ayrı orbit animasyonları */
#frontend-orbit-container, #backend-orbit-container {
    animation: spin-right 30s linear infinite;
}

.inner-orbit-circles, .outer-orbit-circles {
    animation: counter-rotate 30s linear infinite;
}

.middle-orbit-circles {
    animation: counter-rotate-reverse 30s linear infinite;
}
```

### 2. Video Player Modals
- Bootstrap modal sistemi
- Otomatik video pause/play
- Responsive video container
- Multiple video support

### 3. Project Detail Modals
- Detaylı proje açıklamaları
- Teknoloji listeleri
- GitHub ve demo linkleri
- Video player entegrasyonu

## 📱 Responsive Breakpoints

- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: > 768px

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/BT-maker/portfolio.git
cd portfolio
```

2. Dosyaları web sunucunuzda çalıştırın veya doğrudan `index.html` dosyasını tarayıcıda açın.

3. Gerekli değişiklikleri yapın:
   - Kişisel bilgilerinizi güncelleyin
   - Projelerinizi ekleyin
   - Sosyal medya linklerinizi güncelleyin
   - Fotoğraflarınızı ekleyin

## 📝 Özelleştirme

### Kişisel Bilgileri Güncelleme

`index.html` dosyasında aşağıdaki alanları güncelleyin:

```html
<!-- Hero Section -->
<h1 class="hero-title">
    Merhaba, Ben <span class="highlight">Bahattin Tok</span>
</h1>

<!-- About Section -->
<h3 class="about-title">Tutkulu Web Developer</h3>

<!-- Contact Section -->
<p>your-email@example.com</p>
<p>+90 555 123 4567</p>
```

### Orbit Animasyonuna Yeni Teknolojiler Ekleme

`index.html` dosyasında orbit bölümüne yeni teknolojiler ekleyebilirsiniz:

```html
<div class="inner-orbit-circles">
    <i class="fab fa-new-technology"></i>
</div>
```

### Projeleri Ekleme

Projeler bölümünde yeni proje kartları ekleyebilirsiniz:

```html
<div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="400">
    <div class="project-card">
        <div class="project-image">
            <img src="proje-resmi.jpg" alt="Proje Adı">
            <div class="project-overlay">
                <div class="project-links">
                    <a href="#" class="project-link" data-bs-toggle="modal" data-bs-target="#projectModal">
                        <i class="fas fa-external-link-alt"></i>
                    </a>
                    <a href="#" class="project-link">
                        <i class="fab fa-github"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="project-content">
            <h4 class="project-title">Proje Adı</h4>
            <p class="project-description">Proje açıklaması</p>
            <div class="project-tech">
                <span class="tech-tag">HTML</span>
                <span class="tech-tag">CSS</span>
                <span class="tech-tag">JavaScript</span>
            </div>
        </div>
    </div>
</div>
```

### Renkleri Değiştirme

`style.css` dosyasında CSS değişkenlerini güncelleyin:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --gradient-primary: linear-gradient(135deg, #color1 0%, #color2 100%);
}
```

## 🎯 Özellikler Detayı

### 1. Navigation
- Sticky navbar with blur effect
- Smooth scroll navigation
- Active link highlighting
- Mobile responsive hamburger menu

### 2. Hero Section
- Gradient background with grid pattern
- Typing animation for titles
- Code animation block
- Social media links with hover effects
- Call-to-action buttons

### 3. About Section
- Personal information with statistics
- Counter animation for stats
- Downloadable CV button
- Professional photo with frame effect

### 4. Skills Section
- **Static Skills List**: Categorized technology lists
- **Orbit Animation**: Animated technology logos
- **Frontend/Backend Separation**: Two distinct orbit sections
- **Responsive Design**: Mobile-optimized animations

### 5. Projects Section
- Project cards with hover effects
- Image overlays with action buttons
- Technology tags with brand colors
- External links and modal triggers
- **Video Player Integration**: Demo video playback

### 6. Contact Section
- Horizontal contact information layout
- Icon wrappers with gradient backgrounds
- Social media links
- Responsive design

### 7. Additional Features
- Back to top button with smooth scroll
- Scroll progress indicator
- Preloader animation
- Notification system
- Lazy loading for images
- **Central Divider**: Visual separation in skills section

## 🔧 JavaScript Özellikleri

- **AOS Animations**: Scroll-based animations
- **Orbit Animation Control**: Custom orbit and counter-rotation
- **Video Player Management**: Modal video control
- **Form Validation**: Email ve form validasyonu
- **Smooth Scrolling**: Yumuşak sayfa geçişleri
- **Counter Animation**: İstatistik sayaçları
- **Notification System**: Kullanıcı bildirimleri
- **Parallax Effect**: Hero section parallax
- **Lazy Loading**: Görsel lazy loading

## 📊 Performans Optimizasyonları

- CSS ve JavaScript optimizasyonu
- Image optimization ve lazy loading
- Debounced scroll events
- Efficient DOM queries
- Animation performance tuning
- **3D Transform Optimization**: Hardware acceleration

## 🌐 Browser Desteği

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+


## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit yapın (`git commit -m 'Add some AmazingFeature'`)
4. Push yapın (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📞 İletişim

- **GitHub**: [@BT-maker](https://github.com/BT-maker)

## 🙏 Teşekkürler

- [Bootstrap](https://getbootstrap.com/) - CSS Framework
- [Font Awesome](https://fontawesome.com/) - İkonlar
- [Google Fonts](https://fonts.google.com/) - Tipografi
- [AOS](https://michalsnik.github.io/aos/) - Scroll Animasyonları

## 🎉 Öne Çıkan Başarılar

- **Orbit Animation**: Teknoloji logolarının mükemmel senkronizasyonu
- **Video Integration**: Seamless video player experience
- **Responsive Design**: Tüm cihazlarda mükemmel performans
- **Performance**: Optimized animations ve smooth interactions

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!

