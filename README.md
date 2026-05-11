# Chorale Saint Padre Pio – Website

Website for the **Chorale Saint Padre Pio de la Paroisse de Kansanga**, built with the [Agency Jekyll Theme](https://github.com/raviriley/agency-jekyll-theme) and customized for our choir.

## 🚀 Getting Started on GitHub Pages

### 1. Create a GitHub Repository
- Go to [github.com](https://github.com) and create a new repository
- Name it `chorale-saint-padre-pio` (or your preferred name)
- Upload all these files to the repository

### 2. Enable GitHub Pages
- Go to **Settings → Pages**
- Set source to **main branch / root**
- Your site will be live at `https://yourusername.github.io/chorale-saint-padre-pio`

### 3. Update `_config.yml`
```yaml
url: "https://yourusername.github.io"
baseurl: "/chorale-saint-padre-pio"
email: your-real-email@example.com
```

---

## 📁 Site Structure

```
chorale-site/
├── _config.yml          # Main site settings
├── index.md             # Home page
├── blog.md              # Blog listing page
├── scores.md            # Music scores page
├── join.md              # Member registration page
├── _data/
│   ├── sitetext.yml     # All text content (edit this!)
│   ├── navigation.yml   # Menu links
│   └── style.yml        # Colors and fonts
├── _posts/              # Blog posts (add new .md files here)
├── _includes/           # Reusable page sections
├── _layouts/            # Page templates
├── _sass/               # Styles (edit _choir-custom.scss for colors)
└── assets/
    └── img/             # Images – replace with real choir photos!
```

---

## ✏️ How to Edit Content

### Change text, titles, descriptions
Edit **`_data/sitetext.yml`** – all section text is here.

### Add a blog post
Create a new file in `_posts/` named `YYYY-MM-DD-title.md`:
```yaml
---
layout: post
title: "Your Post Title"
date: 2025-06-01
author: Your Name
category: Announcements
image: assets/img/blog/your-image.jpg  # optional
---

Your post content here in **Markdown**.
```

### Add a music score
Edit `scores.md` and add a new card block. Upload your PDF to `assets/scores/`.

### Replace images
- **Hero header**: Replace `assets/img/header.jpg` with a choir photo
- **Contact background**: Replace `assets/img/contact.jpg`
- **Team photos**: Add to `assets/img/team/`
- **Timeline photos**: Replace files in `assets/img/timeline/`

### Change colors
Edit `_data/style.yml`:
```yaml
highlight: "#1a4a8a"   # Primary blue
white: "#f5f0e8"       # Warm beige
black: "#0d2b5e"       # Dark navy
```

---

## 📬 Setting Up Contact & Registration Forms

Both forms use **[Formspree](https://formspree.io)** (free):
1. Create a free account at formspree.io
2. Create a form and copy the form ID
3. In `_config.yml` set: `formspree_form_path: "f/YOUR_FORM_ID"`
4. In `join.md` update the form action URL with your Formspree ID

---

## 🖼️ Recommended Images to Add

| File path | Description |
|-----------|-------------|
| `assets/img/header.jpg` | Choir singing at Mass (hero banner) |
| `assets/img/contact.jpg` | Church or choir image for contact section |
| `assets/img/team/director.jpg` | Choir director photo |
| `assets/img/team/assistant.jpg` | Assistant director photo |
| `assets/img/team/coordinator.jpg` | Coordinator photo |
| `assets/img/timeline/1.jpg` – `4.jpg` | Historical photos |
