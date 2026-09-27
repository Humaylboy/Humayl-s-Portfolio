# Humayl Siddiqui — Photography Portfolio

Professional single-page portfolio website built with HTML, CSS & JavaScript.

## Folder Structure

```
photography-portfolio/
├── index.html          ← Main page
├── css/
│   └── style.css       ← All styles & animations
├── js/
│   └── script.js       ← Interactions & animations
├── images/             ← Put your photos here
└── README.md
```

## How to Add Your Images

### 1. Hero background (optional)
In `css/style.css`, find the `.hero` rule and uncomment / set:

```css
background-image: url('../images/hero-bg.jpg');
```

Recommended size: **1920×1080px** or larger.

### 2. About / Portrait photo
In `index.html`, find the About section placeholder and replace the whole `<div class="image-placeholder portrait">...</div>` with:

```html
<img src="images/portrait.jpg" alt="Humayl Siddiqui">
```

Recommended size: **600×800px**.

### 3. Portfolio images
There are 8 portfolio slots. For each one, replace the placeholder div with an `<img>`:

```html
<img src="images/event-1.jpg" alt="Campus Festival">
```

Suggested filenames already written in the placeholders:
- `images/event-1.jpg`, `images/event-2.jpg`
- `images/portrait-1.jpg`, `images/portrait-2.jpg`
- `images/campus-1.jpg`, `images/campus-2.jpg`
- `images/creative-1.jpg`, `images/creative-2.jpg`

Recommended size: **1200×800px** (landscape) or **800×1000px** (portraits).

### 4. Contact email
Search for `humayl.siddiqui@email.com` in `index.html` and replace with your real email.

## How to Open

Simply open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).

No build step required.

## Features

- Responsive design (mobile + desktop)
- Smooth scroll navigation
- Portfolio category filters
- Scroll-triggered animations
- Animated skill bars & counters
- Contact form (demo – shows “Message Sent!”)
- Dark professional theme with gold accent
