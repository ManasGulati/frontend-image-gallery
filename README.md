# 🖼️ Image Gallery

> A responsive, interactive image gallery built with pure HTML & CSS - no JavaScript, no frameworks.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Tools and Technologies](#tools-and-technologies)
- [Project Structure](#project-structure)
- [Methods](#methods)
- [Key Highlights](#key-highlights)
- [Output](#output)
- [How to Run](#how-to-run)
- [Results and Conclusion](#results-and-conclusion)
- [Future Work](#future-work)
- [Author and Contact](#author-and-contact)

---

## Overview

This project is a front-end web page that displays a collection of images in a structured, visually appealing grid layout. The gallery leverages CSS Grid for responsive layout and CSS transitions for hover-based interactivity, demonstrating that rich user experiences can be achieved without any JavaScript or third-party libraries.

Each image renders in grayscale by default and transitions to full color on hover, accompanied by a scale-up effect, drop shadow, and an animated caption, creating an engaging browsing experience.

---

## Tools and Technologies

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic page structure using `<figure>`, `<figcaption>`, `<section>`, `<article>` |
| **CSS3** | Styling, layout, transitions, animations, hover effects |
| **CSS Grid** | Responsive 3 column image grid layout |
| **CSS Transitions & Filters** | Grayscale-to-color effect, scale, drop-shadow on hover |
| **Google Fonts** | Clean, modern typography |

> No JavaScript. No frameworks. No dependencies.

---

## Project Structure

```
Image_Gallery/
│
├── Assets/                  # All image assets and favicon
│   ├── image1.jpg
│   ├── image2.jpeg
│   ├── ... (15 images total)
│   └── favicon.ico
│
├── index.html               # Main gallery page
├── styles.css               # All styling and animations
├── README.md                # Project documentation
└── dependencies.txt         # Tech stack reference
```

---

## Methods

- **Semantic HTML** — Used appropriate HTML5 elements (`<figure>`, `<figcaption>`, `<main>`, `<article>`, `<section>`) for accessible, well-structured markup.
- **CSS Grid Layout** — Implemented a `repeat(3, 1fr)` grid with `gap` spacing for a clean, uniform card arrangement.
- **CSS Filters** — Applied `grayscale(100%)` as the default image state; removed on `:hover` to reveal full color using a smooth transition.
- **Hover Animations** — Combined `transform: scale()`, `filter: drop-shadow()`, and `opacity` transitions to create layered, polished hover effects.
- **Caption Animation** — Captions slide in with a `translateY` and `skew` transform on hover, adding personality to the UI.

---

## Key Highlights

-  Zero JavaScript: all interactivity achieved purely with CSS
-  Fully responsive grid layout using CSS Grid
-  Smooth grayscale to color reveal on hover
-  Animated captions with skew & slide effect
-  Clean semantic HTML structure
-  Lightweight, no external libraries or frameworks

---

## Output

The output is a fully functional, browser-ready HTML page. Upon opening `index.html`:

- A 3-column image grid is displayed against a light background
- Images appear in grayscale until hovered
- On hover: image reveals full color, scales up slightly, gains a drop shadow, and the caption animates into view

> See the live demo or open `index.html` directly in any modern browser.

---

## How to Run

No installation or setup required.

1. Clone or download this repository
   ```bash
   git clone https://github.com/your-username/Image_Gallery.git
   ```
2. Navigate to the project folder
   ```bash
   cd Image_Gallery
   ```
3. Open `index.html` in any modern browser
   ```bash
   # On macOS
   open index.html

   # On Windows
   start index.html

   # On Linux
   xdg-open index.html
   ```

> Works in all modern browsers: Chrome, Firefox, Edge, Safari.

---

## Results and Conclusion

This project successfully demonstrates core front-end development skills — semantic markup, responsive design, and CSS-driven interactivity, without relying on any JavaScript or external frameworks. The result is a clean, performant, and visually engaging gallery page that loads instantly and works across all modern browsers.

It reinforces a key principle in front-end development: **CSS alone is powerful enough to create rich, interactive user experiences** when used thoughtfully.

---

## Future Work

- [ ] Add a **lightbox/modal view** to open images in full screen on click (JS)
- [ ] Implement **category filtering** to sort images by tags or type
- [ ] Make the layout fully **mobile responsive** with media queries
- [ ] Add **lazy loading** for images to improve performance at scale
- [ ] Integrate a **dark mode** toggle
- [ ] Replace static images with a **dynamic image feed** from an API

---

## Author and Contact

**Manas Gulati**
- GitHub: [@ManasGulati](https://github.com/ManasGulati)
- LinkedIn: [linkedin.com/in/manasgulatiryu](https://www.linkedin.com/in/manasgulatiryu/)
- Email: manasgulati222@gmail.com

---

> ⭐ If you found this project useful or interesting, feel free to star the repository!
