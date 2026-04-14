# NotFound_404 — Team Website (Static)

NotFound_404-ийн багийн **one-page, cyber-style** танилцуулга веб. Цэвэр **HTML/CSS/JS** (frameworkгүй) тул хурдан, хялбар deploy хийгддэг.

## Features

- **Responsive layout** (desktop/tablet/mobile)
- **Sticky navbar** + mobile **hamburger menu**
- **SEO + Social preview meta** (Open Graph / Twitter Card)
- **Accessibility basics**: skip link, `:focus-visible`, reduced motion support
- **External link hardening**: `rel="noopener noreferrer"`

## Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**

## Project Structure

```text
.
├─ index.html
├─ logo5.png
├─ logo4.png
├─ bebe.jpeg
├─ byamba.webp
├─ bagsh.jpg
└─ images/
   ├─ bayar.jpeg
   └─ bayar.jpg
```

> Note: `index.html` нь бүх CSS/JS-ээ inline байдлаар агуулсан.

## Run locally

### Option A: VS Code Live Server (recommended)

1. VS Code → **Live Server** extension суулгана.
2. `index.html` дээр right click → **Open with Live Server**

### Option B: Python HTTP server

```bash
python -m http.server 5173
```

Дараа нь browser дээр `http://localhost:5173` нээнэ.

### Option C: Node (http-server)

```bash
npx http-server -p 5173
```

## Deploy

### GitHub Pages

1. Repo → **Settings** → **Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / Folder: `/ (root)`
4. Save → URL үүснэ

### Netlify / Vercel

- Build command: **none**
- Output/Publish directory: **root** ( `index.html` байрлаж байгаа хавтас )

## Customize content

- **Team members**: `#team` section доторх card-ууд
- **Projects**: `#projects` section доторх card-ууд
- **Links**: `#contact` хэсэг

## Assets

Зургийн файлууд (`logo5.png`, `images/*` гэх мэт) зөв замаар (relative path) байрласан эсэхийг шалгаарай.

## License

License-аа тодорхойлох бол `LICENSE` файл нэмнэ үү. (Ж: MIT)
