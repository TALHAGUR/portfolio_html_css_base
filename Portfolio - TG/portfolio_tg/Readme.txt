# Portfolio - TG (Pure HTML/CSS/JS Version)

Bu proje, **React + Next.js + TailwindCSS** ile geliştirilmiş olan  
[mostafizurhimself/getprofile](https://github.com/mostafizurhimself/getprofile) reposundaki **Pofology** templat’inin  
**sadece HTML, CSS ve JavaScript** kullanılarak yeniden yazılmış halidir.

Amaç: Orijinal modern Next.js portfolyo şablonunu, hiçbir build adımı olmadan,  
sadece statik dosyalarla (HTML/CSS/JS) çalışan, her yerde kolayca host edilebilir bir versiyona dönüştürmek.

> Bu repo, Talha Gür’ün kişisel portfolyo sitesi için uyarlanmış halidir.

---

## 🚀 Özellikler

- ✅ **Tamamen statik**: Sadece `index.html`, `css/style.css` ve görsellerden oluşur.
- 🎨 **Dark / Light tema desteği**  
  - Tema değişimi JavaScript ile yönetilir, tercih `localStorage` üzerinde saklanır.
- 📱 **Tam responsive tasarım**  
  - Masaüstü, tablet ve mobil ekranlarda uyumlu görünüm.
- 🧭 **Sticky header & smooth scroll**  
  - Scroll sonrası yapışan header  
  - Menüden ilgili bölüme yumuşak kaydırma (smooth scrolling)
- 📂 **Portfolyo, blog, deneyim ve eğitim bölümleri**  
  - **About Me** (Hakkımda)  
  - **Recent Works** (Projeler)  
  - **Latest Posts** (Blog yazıları)  
  - **Skills**, **Experience**, **Education** alanları
- 🍔 **Mobil hamburger menü**  
  - Açılır/kapanır mobil menü, body scroll kilitleme desteği
- ⌨️ **Typed.js ile yazı efekti**  
  - Hero bölümündeki dinamik yazı, [typed.js](https://github.com/mattboldt/typed.js/) CDN’i ile sağlanır.
- 🔤 **Google Fonts & Font Awesome ikonlar**  
  - `Rubik` fontu ve sosyal ikonlar CDN üzerinden yüklenir.

---

## 🧱 Teknoloji Stack’i

Bu repo bilerek minimum bağımlılıkla hazırlanmıştır:

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **CDN üzerinden**:
  - [Typed.js](https://cdn.jsdelivr.net)
  - [Google Fonts](https://fonts.googleapis.com)
  - [Font Awesome 6](https://cdnjs.com)

Herhangi bir Node.js, paket yöneticisi veya build süreci **gerektirmez**.

---

## 📂 Klasör Yapısı

Projenin esas yapısı:

```bash
portfolio_tg/
├── index.html
├── css/
│   └── style.css
└── images/
    ├── avatar/
    ├── books/
    ├── posts/
    ├── skills/
    ├── tools/
    └── works/
