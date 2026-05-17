<h1 align="center">Liquid Glass CSS</h1>

<p align="center">
  <a href="./README.md">English</a> | <a href="./README.ru.md">Русский</a>
</p>

<p align="center">
  <strong>Minimal, dark-first liquid glass CSS kit built for production UI surfaces.</strong>
</p>

<p align="center">
  <a href="https://test-motion-design.vercel.app/"><img src="https://img.shields.io/badge/Demo-test--motion--design-06B6D4?style=flat-square&logo=vercel" alt="Live Demo" /></a>
  <a href="#"><img src="https://img.shields.io/badge/CSS-Pure-3178C6?style=flat-square&logo=css3" alt="Pure CSS" /></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-88CE02?style=flat-square" alt="MIT License" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.0.1-61DAFB?style=flat-square" alt="v1.0.1" /></a>
</p>

---

## ✦ Primary Demo

This repository is intentionally base-focused.  
The main visual concept and showcase is available on the author's mock site:

- [test-motion-design.vercel.app](https://test-motion-design.vercel.app/)

## ✦ What You Get

- Pure CSS liquid glass styles (no JavaScript)
- Clean base preset for reusable UI blocks
- Strong preset for navigation and active elements
- Form-ready helpers for fast prototyping

## ✦ Installation

```bash
git clone https://github.com/GANSGX/liquid-glass-css.git
cd liquid-glass-css
```

Include stylesheet:

```html
<link rel="stylesheet" href="./src/liquid-glass.css">
```

## ✦ Quick Start

```html
<section class="glass-form liquid-glass">
  <h1 class="glass-title">Welcome Back</h1>
  <input class="glass-input" placeholder="Email" />
  <button class="glass-button">Sign In</button>
</section>
```

## ✦ Core Classes

- `.liquid-glass` - base glass surface
- `.nav-blob` - stronger glass surface for nav/active controls
- `.glass-form` - compact panel wrapper
- `.glass-input` / `.glass-textarea` - form fields
- `.glass-button` / `.glass-button.secondary` - action buttons

<br/>

## ✦ Local Examples

- [examples/form-login.html](./examples/form-login.html)
- [examples/form-contact.html](./examples/form-contact.html)
- [examples/variants.html](./examples/variants.html)

<br/>

## ✦ Mock Reference Screenshots

Hero section:

![Mock Hero](./assets/mock-hero.jpg)

Protocol section:

![Mock Protocol](./assets/mock-protocol.jpg)

Feature cards:

![Mock Cards](./assets/mock-cards.jpg)

<br/>

## ✦ Local Preview

```bash
open ./examples/variants.html
```

or

```bash
npx serve .
```

## ✦ License

MIT
