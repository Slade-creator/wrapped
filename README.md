# Wrapped 

A "Wrapped-style" birthday experience built in plain HTML, CSS, and JavaScript. No frameworks. Synchronized animations, a crossfading audio engine, and a mobile-first layout.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

---

## Features

**Intro Sequence:** Procedural CSS starfield, a glowing backdrop orb, multilingual typography that shifts as the page loads, and an inline SVG flower that grows via custom cubic-bezier keyframes.

**Edge-to-Edge Canvas:** Fluid sizing across modern mobile devices using `viewport-fit=cover` to account for hardware notches and safe areas.

**Slideshow Engine:** Timeline built from scratch with hardware-accelerated `scaleX` transforms. Supports automatic progression, tap-to-skip, and keyboard navigation.

**Audio Crossfading:** Multi-channel HTML5 `Audio()` playlist that tracks which slide you're on and crossfades between tracks without clipping.

**Accessibility:** `aria-live="polite"` announcements for screen readers, touch targets above 48px, and `prefers-reduced-motion` support.

---

## Repository Structure

```text
├── audio/
│   ├── track2.mp3       # Slides 1-2 (Daniel Caesar)
│   ├── track3.mp3       # Slides 3-4 (Nascent)
│   └── track4.mp3       # Slides 5+ (Sampha)
├── index.html           # Structure, styles, and engine code
└── README.md
```
