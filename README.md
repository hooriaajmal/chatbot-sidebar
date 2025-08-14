## Professional AI Sidebar

A clean, responsive, single‑file HTML template featuring a collapsible sidebar UI for AI/chat applications or dashboards. It includes smooth animations, keyboard shortcuts, accessibility enhancements, and mobile‑first behavior. Everything is self‑contained in one file: `chatbot-sidebar.html`.

---

### Features
- **Collapsible sidebar**: Toggle open/close with a button or keyboard shortcut.
- **Keyboard shortcut**: Press `Ctrl + B` to toggle the sidebar.
- **Mobile overlay & responsive layout**: Auto-collapses on small screens and shows an overlay.
- **Smooth interactions**: Ripple, hover, and load-in animations.
- **Accessible focus states**: Visual focus outlines for keyboard users.
- **No build/dependencies**: Pure HTML/CSS/JS in a single file; works offline.
- **Progressive enhancement**: Uses `IntersectionObserver` when available, gracefully degrades when not.

---

### Video Demo
[Video Demo](https://github.com/hooriaajmal/chatbot-sidebar/blob/main/Recording%202025-08-14%20194423.mp4)

### Project Structure
```
─ chatbot-sidebar.html   # Main HTML (includes inline styles + scripts)
─ README.md              # This documentation
```

---

### Repository Setup (Git)

- Clone an repository instead:
  ```bash
  git clone https://github.com/hooriaajmal/chatbot-sidebar
  cd chatbot-sidebar
  ```

---

### Quick Start (Local Viewing)

- **Open directly**
  - Double‑click `chatbot-sidebar.html` to open it in your browser.
  - Works because all CSS/JS is inline and no network calls are required.

---

### How to Use / Customize

- **Change the title/branding**
  - Edit the `<title>` tag and the logo/heading text in `chatbot-sidebar.html`.

- **Update navigation items**
  - Look for elements with the class `nav-item` inside the sidebar; update icons/text and link targets.

- **Adjust layout dimensions/colors**
  - Sidebar width, backgrounds, and gradients are defined in the inline `<style>` section. Examples:
    - `.sidebar { width: 280px; }` → change width
    - Background gradients: `background: linear-gradient(...)` on `body` and `.main-content`

- **Keyboard interactions**
  - `Ctrl + B` toggles the sidebar.
  - `Escape` collapses the sidebar on small screens.

- **Animations**
  - Ripple, hover, and load-in animations are implemented via inline CSS/JS at the bottom of the file.

---

### Browser Support
- Designed for modern evergreen browsers (Chrome, Edge, Firefox, Safari).
- Graceful degradation for older browsers; if `IntersectionObserver` is unavailable, core functionality still works.

---

### Deployment

- **GitHub Pages**
  1. Commit and push the repository to GitHub.
  2. In the repo settings, enable GitHub Pages for the `main` branch and the `/root` directory.
  3. Access the page at:
     - `https://<your-username>.github.io/<your-repo>/chatbot-sidebar.html`
     - Or rename to `index.html` to serve at the repo root URL.

- **Any static host (Netlify, Vercel, S3, Azure Static Web Apps, etc.)**
  - Deploy the folder as a static site; no build steps required.

---

### Contributing

1. Fork the repo and create a feature branch:
   ```bash
   git checkout -b feat/your-change
   ```
2. Make your edits in `chatbot-sidebar.html`.
3. Commit with a clear message and open a Pull Request.

> Code style: keep variable and class names descriptive; prefer readability over cleverness. Avoid unrelated reformatting.

---

### Frequently Asked Questions

- **Do I need Node.js or a bundler?**
  - No. Everything is inline and self‑contained.

- **Why do animations or fonts look different locally?**
  - The template uses system fonts and CSS animations. Behavior can vary slightly by browser/OS.

- **Can I integrate this into my app?**
  - Yes. Copy the relevant parts of the sidebar markup, styles, and the closing `<script>` into your layout.

---

### License

Specify a license for your repository (e.g., MIT, Apache‑2.0, GPL‑3.0). If unsure, MIT is a common permissive choice. 
