# 🌸 Priya & Arjun — Premium Wedding Invitation

A stunning, high-performance wedding invitation website built with a focus on **South Indian tradition** and **modern luxury aesthetics**. This project features rich animations, 3D parallax effects, and procedural audio.

![Wedding Theme](https://img.shields.io/badge/Theme-South_Indian_Luxury-800000?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Tech-HTML5_CSS3_VanillaJS-gold?style=for-the-badge)

---

## ✨ Key Features

### 🏺 1. 3D Parallax Hero Section
Experience a deep, immersive entrance. The hero section uses a 4-layer parallax engine:
- **Layer 0-1**: Deep glows and subtle temple patterns.
- **Layer 2**: Midground hanging marigolds and ornamental SVGs.
- **Layer 3**: Elegant typography with gold gradients.
- **Layer 4**: Foreground interactive elements.
*Includes mouse-interactive depth on desktop.*

### ⏳ 2. Celestial Countdown
A mystical countdown timer set against a **Canvas-rendered starry night sky**.
- Real-time ticking with "pulse" animations.
- Procedural stars that twinkle and drift.
- Automatically transitions to a "Wedding Begun" state.

### 🎵 3. Procedural "Nada" Music
Rather than heavy MP3 files, this site uses the **Web Audio API** to generate a calming, meditative melody in real-time.
- Low performance overhead.
- Instant toggle with pulse animation.

### 📋 4. Smart RSVP System
- Minimalist glassmorphic form.
- Instant validation and success animations.
- **One-click WhatsApp integration** for guests to RSVP directly to the couple.

### 🎭 5. Premium Motion Design
- **Reveal-on-Scroll**: Smooth transitions using `IntersectionObserver`.
- **Gold-Leaf Accents**: Custom SVG ornaments and temple silhouettes.
- **Typography**: A curated blend of *Cinzel Decorative*, *Lora*, and *Noto Serif Tamil*.

---

## 🎨 Color Palette

| Color | Hex | Role |
| :--- | :--- | :--- |
| **Deep Ruby** | `#2C0000` | Backgrounds & Luxury depth |
| **Royal Red** | `#5A0001` | Section Headings |
| **Gold Leaf** | `#D4AF37` | Ornaments & Accents |
| **Ivory Warm** | `#FFF9E3` | Main background & Contrast |
| **Vermilion** | `#C0392B` | Highlights & Sacred text |

---

## 🛠️ Customization Guide

### 1. Update Names & Date
Find the `index.html` file and search for:
- `Priya & Arjun` -> Replace with your names.
- `August 24, 2026` -> Update the hero display date.
- `const weddingDate = new Date('2026-08-24T10:30:00+05:30');` -> Update the JS timer logic.

### 2. Configure RSVP
Update the WhatsApp link in the RSVP section:
```html
<a href="https://wa.me/YOUR_PHONE_NUMBER?text=Hello!..."
```

### 3. Change Assets
- **Photos**: Replace the `photo-placeholder-icon` in the `#couple` section with `<img>` tags for your own portraits.
- **Fonts**: The project pulls from Google Fonts. You can swap them in the `<link>` section in `<head>`.

---

## 🚀 Deployment

Since this is a vanilla HTML/CSS project, it can be deployed anywhere:
- **GitHub Pages**: Perfect for easy hosting.
- **Netlify/Vercel**: Drag and drop the folder.
- **Shared Hosting**: Upload via FTP.

---

## 📜 License
*Custom crafted for Priya & Arjun's special day. All rights reserved.*
