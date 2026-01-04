# 🚀 sukangoding.id - Portfolio

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)
![Technology](https://img.shields.io/badge/Built%20with-Astro-purple?style=for-the-badge)
![TailwindCSS](https://img.shields.io/badge/Styled%20with-TailwindCSS-blue?style=for-the-badge)

Halaman portofolio profesional untuk **sukangoding.id** — Fullstack Developer yang berfokus pada pengembangan aplikasi web dan mobile dengan teknologi modern.

## ✨ Fitur

- 🌙 **Dark Mode Design** — Desain futuristik dengan tema gelap
- 📱 **Responsive** — Tampilan optimal di semua ukuran layar
- ⚡ **Super Cepat** — Built dengan Astro (Zero JS by default)
- 🎨 **Glassmorphism UI** — Efek kaca modern yang menarik
- 💬 **WhatsApp Integration** — Form kontak langsung ke WhatsApp
- 🚀 **Auto Deploy** — GitHub Actions untuk deployment otomatis

## 🛠️ Tech Stack

| Teknologi | Kegunaan |
|-----------|----------|
| Astro | Static Site Generator |
| TailwindCSS v4 | Styling |
| GitHub Actions | CI/CD |

## 📂 Struktur Project

```
portofolio_project/
├── src/
│   ├── components/      # Komponen Astro
│   ├── layouts/         # Layout template
│   ├── pages/           # Halaman
│   └── styles/          # CSS global
├── public/              # Asset statis
├── .github/workflows/   # GitHub Actions
└── astro.config.mjs     # Konfigurasi Astro
```

## 🚀 Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📦 Deployment ke GitHub Pages

1. **Update `astro.config.mjs`:**
   ```javascript
   export default defineConfig({
     site: 'https://<username>.github.io',
     base: '/<repository-name>', // jika bukan username.github.io
   });
   ```

2. **Push ke GitHub:**
   ```bash
   git add .
   git commit -m "Deploy Astro portfolio"
   git push origin main
   ```

3. **Aktifkan GitHub Pages:**
   - Buka **Settings** → **Pages**
   - Pilih **Source**: `GitHub Actions`

Website akan otomatis di-deploy setiap push ke branch main.

## 📧 Kontak

- **WhatsApp:** [+62 822 8710 6193](https://wa.me/6282287106193)
- **Website:** sukangoding.id

## 📜 Lisensi

© 2024 sukangoding.id. All rights reserved.

---

<p align="center">
  Dibuat dengan ❤️ dan ☕ oleh <strong>sukangoding.id</strong>
</p>
