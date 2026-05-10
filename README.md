# Liquid Glass CSS

This repository has two documentation versions:
- English: `README.md`
- Russian: `README.ru.md`

Minimal, dark-first, open-source liquid glass styles built with pure CSS.
This repo focuses on base styles, while the author's mock concept lives here:
[test-motion-design.vercel.app](https://test-motion-design.vercel.app/).

## Why This

- Clean glassmorphism without UI noise
- Tuned for dark backgrounds where the effect looks best
- Reusable classes for forms, cards, nav blobs, and controls

## Features

- Pure CSS (no JavaScript required)
- Soft blur + edge highlight + depth shadows
- Minimal dark visual language
- Base-first API (`.liquid-glass` and `.nav-blob`)
- Ready-to-use examples

## Install

### Clone repository

```bash
git clone https://github.com/<your-username>/liquid-glass-css.git
cd liquid-glass-css
```

### Include stylesheet

```html
<link rel="stylesheet" href="./css/liquid-glass.css">
```

## Quick Start

```html
<section class="glass-form liquid-glass">
  <h1 class="glass-title">Welcome Back</h1>
  <input class="glass-input" placeholder="Email" />
  <button class="glass-button">Sign In</button>
</section>
```

## Utility Classes

- `.liquid-glass` - base glass panel
- `.nav-blob` - strong glass chip for nav/active controls
- `.glass-form` - layout wrapper for forms/cards
- `.glass-input` - text-like input field
- `.glass-textarea` - textarea style
- `.glass-button` - primary button
- `.glass-button.secondary` - muted secondary button

## Examples

- [examples/form-login.html](./examples/form-login.html)
- [examples/form-contact.html](./examples/form-contact.html)
- [examples/variants.html](./examples/variants.html)
- Reference mock site: [test-motion-design.vercel.app](https://test-motion-design.vercel.app/)

## Screenshots

Mock hero (glass nav + CTA):

![Mock Hero](./assets/mock-hero.png)

Mock protocol section:

![Mock Protocol](./assets/mock-protocol.png)

Mock feature cards:

![Mock Cards](./assets/mock-cards.png)

## Local Preview

Open any example file directly:

```bash
open ./examples/form-login.html
```

Or run a static server:

```bash
npx serve .
```

## License

MIT
