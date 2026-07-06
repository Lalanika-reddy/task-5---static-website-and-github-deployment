https://lalanika-reddy.github.io/task-5---static-website-and-github-deployment/
# Antigravity Workspace - Responsive Landing Page

A premium, responsive, dark-themed landing page representing **Antigravity OS**, a futuristic spatial developer workspace.

This project is built from scratch using semantic **HTML5**, modern **CSS3**, and **Vanilla JavaScript** to showcase advanced responsive layout structures and micro-interactions.

## Features

- **Responsive Design**: Auto-reflowing grids and flex items across mobile, tablet, and desktop screen sizes.
- **Collapsible Mobile Menu**: Hamburger toggle animation that opens a slide-in navigation panel on mobile viewports, featuring vertical scrollability (`overflow-y: auto`) to accommodate short/landscape screens.
- **Background Scroll Locking**: Toggles a helper class on the `<body>` element when the mobile navigation menu is active to prevent background scroll leakage.
- **Glassmorphism Panels**: UI layout mockups styled using CSS backdrop filters, subtle gradients, and translucent borders.
- **Hover Spotlight Effect**: Interactivity on feature cards where the glow spotlight dynamically follows mouse movement.
- **Floating Visuals**: Custom keyframe CSS animations simulating floating IDE windows and diagnostic statistics.
- **SEO Best Practices**: Uses semantic markup structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`), descriptive metadata, unique IDs, and lightweight inline SVG elements.

## Tech Stack

- **Core**: HTML5
- **Styling**: CSS3 (Variables, Flexbox, Grid, Media Queries, Keyframe Animations)
- **Logic**: Vanilla JavaScript (Scroll listeners, click toggles, cursor tracking coordinate mapping)
- **Typography**: Google Fonts (Outfit & Inter)

## How to Run Locally

### Method 1: VS Code Live Server
1. Open this workspace in **VS Code**.
2. Install the **Live Server** extension (if not already installed).
3. Right-click on `index.html` and click **Open with Live Server**.
4. The page will serve on `http://127.0.0.1:5500`.

### Method 2: Python HTTP Server
If Python is installed on your machine, run the following command in your terminal:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.

### Method 3: Node JS (http-server / live-server)
Run either of these command lines:
```bash
npx live-server
# or
npx http-server
```
