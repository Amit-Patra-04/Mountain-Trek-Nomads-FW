# 🏔️ Peak Quest — Premium Mountain Trekking Portal

A modern, responsive, and high-performance landing page designed for mountain trekking enthusiasts. Developed with clean semantic HTML, modular vanilla CSS, and custom interactive JavaScript features, this portal integrates swiper carousels, smooth scroll-reveal effects, and an elegant dark/light theme toggle.

---

## 📷 Website Preview

![Peak Quest Preview] <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/2e9e9b10-7649-4c54-8949-ed8aff2c4892" />

---

## 🔗 Live View
*Experience the website live: [ [Peak Quest Link](https://peak-quest-trek.netlify.app/)]*

---

## ✨ Features

- **🌓 Dynamic Dark/Light Theme**: Toggles background color, text color, scrollbars, and icons dynamically. Features persistent theme caching using `localStorage`.
- **📱 Fluid Responsive Layout**: Tailored using mobile-first design principles, styling breakpoints, and a modern CSS grid structure that scales seamlessly from small smartphones to large ultrawide monitors.
- **✨ ScrollReveal Animations**: Utilizes ScrollReveal.js to trigger polished, multi-directional fade-ins and slide-ups as the user scrolls.
- **🎡 Coverflow Discover Carousel**: Built with Swiper.js, rendering a swipe-friendly, looping 3D coverflow carousel of featured mountain peaks.
- **🎥 Integrated Custom Video Player**: A customized HTML5 video container with play/pause triggers and auto-resetting icons.
- **🗺️ Interactive Place Cards**: Grid of top destinations detailing ratings, estimated budgets, and external quick-links to encyclopedic records.
- **⚡ Performance Optimized**: Utilizes system fonts, lightweight vector icons from Remix Icons, minified JS/CSS libraries, and optimized responsive layouts.
- **🧭 Scroll-Active Navigation**: Automatically highlights the active section link in the navbar during vertical scrolls and provides a sticky header transition above 100px.
- **🔝 Quick Scroll-to-Top**: Features an interactive arrow trigger that smoothly animates the browser viewport back to the top once the scroll height exceeds 200px.

---

## 🎨 Design System

The visual identity is modeled around a professional, clean alpine palette using flexible HSL variables.

| Token | Light Mode Value | Dark Mode Value | Usage |
| :--- | :--- | :--- | :--- |
| `--hue-color` | `190` (Teal/Cyan) | `190` (Teal/Cyan) | Primary tint base |
| `--first-color` | `hsl(190, 64%, 22%)` | `hsl(190, 64%, 22%)` | Accent/Primary buttons, labels |
| `--body-color` | `hsl(190, 100%, 99%)` | `hsl(190, 29%, 12%)` | Page background canvas |
| `--title-color` | `hsl(190, 64%, 18%)` | `hsl(190, 24%, 95%)` | Headers, logo, key text |
| `--text-color` | `hsl(190, 24%, 35%)` | `hsl(190, 8%, 75%)` | Body copy, descriptions |
| `--input-color` | `hsl(190, 24%, 97%)` | `hsl(190, 29%, 16%)` | Form background |

### Typography
- **Primary Body Font**: `'Open Sans', sans-serif` (highly readable on screens)
- **Title & Heading Font**: `'Raleway', sans-serif` (geometric, modern display)

---

## 📁 Repository Structure

```markdown
Mountain-Trek-Nomads-FW/
│
├── Materials/                      # Media assets folder
│   ├── Fav.png                     # Browser favicon
│   ├── Home.jpeg                   # Primary hero header background image
│   ├── Home2.jpeg                  # Sub-hero overlay detail image
│   ├── About1.jpeg & About2.jpeg   # About section composition images
│   ├── Discover11.jpeg - 14.jpeg   # Carousel slideshow card images
│   ├── Discover21.jpeg - 22.jpeg   # Experience section statistics images
│   ├── Place1.jpeg - 9.jpeg        # Choose Your Place grid card backdrops
│   ├── sponsors1.png - 4.png       # Partner logo icons
│   └── Site treak.mp4              # Embedded MP4 video tour showcase
│
├── index.html                      # Core HTML5 layout & semantic structure
├── styles.css                      # Modern CSS layout, animations & theme definitions
├── main.js                         # Custom JavaScript logic, carousel configs & theme state
├── scrollreveal.min.js             # Local copy of the ScrollReveal.js animation library
├── swiper-bundle.min.js            # Local copy of the Swiper.js slider library
├── swiper-bundle.min.css           # Local copy of the Swiper.js layout styles
└── README.md                       # Comprehensive project documentation
```

---

## 🛠️ Technology Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) for semantic layouts.
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) using Custom Properties (Variables), Flexbox, CSS Grid, Media Queries, and Transitions.
- **Logic**: Vanilla ES6 [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) for scroll triggers, menu controls, active navigation tracking, custom video controls, and local storage queries.
- **Libraries**:
  - [Swiper.js](https://swiperjs.com/) for the responsive 3D coverflow carousel.
  - [ScrollReveal.js](https://scrollrevealjs.org/) for scroll-triggered page load animations.
  - [Remix Icon Library v2.5.0](https://remixicon.com/) for SVG icon symbols.

---

## 🚀 Running Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Amit-Patra-04/Mountain-Trek-Nomads-FW.git
   cd Mountain-Trek-Nomads-FW
   ```

2. **Launch a Local Server**:
   Because the video player and theme toggling leverage standard DOM events, it's recommended to launch this page inside a local development server:
   - **VS Code Live Server**: Open the workspace in VS Code, right-click `index.html`, and select **Open with Live Server**.
   - **Python Simple HTTP Server**:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`.
   - **Node.js (http-server)**:
     ```bash
     npx http-server
     ```

---

## 🔒 License & Credits

- **Trek Nomads Reference**: Links sourced from [Trek Nomads](https://www.treknomads.com/).
  
