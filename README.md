# Tap30 — RTL Landing Page (Demo)

**Tap30** is a Persian (Farsi / RTL) landing page mockup for a ride-hailing and delivery service. This repository contains a static, responsive frontend built with plain HTML, CSS and a few small JavaScript bits for UI interactions (tabs, accordion, AOS animations).

> ⚠️ This is a static demo / UI mock. No backend or payment functionality is included.

---

## 🔗 Live demo

https://tap30-project-ali-khezri.netlify.app/
---

## 🧭 About this project

This project demonstrates a right-to-left (RTL) marketing site for a mobility product. It includes:

* Hero with responsive banner and phone mockup
* Services / tabs section (multiple ride & delivery types)
* Plans / pricing cards
* Travel suggestions carousel
* Contact form UI and company information
* Footer with links and trust badges

The markup intentionally uses RTL `dir="rtl"` on the `<html>` element and Persian copy for headings, descriptions and labels.

---

## 📁 Project structure

```
tap30/
├─ index.html
├─ css/
│  ├─ normalize.css
│  └─ style.css
├─ js/
│  └─ main.js
├─ assets/
│  ├─ images/
│  └─ fonts/
└─ README.md
```

---

## 🛠️ Built with

* HTML5 with `dir="rtl"` for Persian layout
* CSS3 (custom properties, responsive grid)
* Vanilla JavaScript for small UX behaviors (nav toggler, tabs, accordion)
* Google Fonts / local Persian font (`Vazir`) via `@font-face`
* AOS (Animate On Scroll) for entrance animations
* Font Awesome for icons (CDN)

---

## ✅ Features

* Fully RTL layout and Persian content
* Mobile-first responsive design
* Accessible-ish semantic structure (sections, headings, forms)
* Tabs and accordion interactions
* Pricing cards and CTA buttons
* Lightweight JS (no frameworks)

---

## 🚀 Run locally

Static project — open `index.html` directly, or run a simple server for correct font & asset behavior:

**Python (quick):**

```bash
python -m http.server 8000
# open http://localhost:8000
```

**Node (serve):**

```bash
npm install -g serve
serve .
# open printed URL
```
---

Ali Khezri — [GitHub](https://github.com/ali-khezri)
