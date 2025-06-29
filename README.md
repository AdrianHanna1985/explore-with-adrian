# Explore with Adrian – The American Backpacker

Welcome to the source code for **The American Backpacker** website, a scenic and story-driven travel hub for outdoor adventurers.

---

## 🌄 Project Overview

This is a static HTML/CSS website designed to showcase destinations, custom itineraries, 360° experiences, and booking services. It is mobile-friendly, dark mode–enabled, and deployable to GitHub Pages or Netlify.

---

## 📁 Folder Structure

```
/
├── index.html
├── about.html
├── booking.html
├── contact.html
├── styles.css
├── nav.html            # Shared navigation (included via JS)
├── footer.html         # Shared footer (included via JS)
├── assets/
│   ├── images/         # Photo galleries per destination
│   ├── videos/         # Embedded or linked trip videos
│   └── js/             # Optional interactive maps, modals
```

---

## 🚀 How to Run Locally

You can open any `.html` file directly in your browser, but to see JavaScript-included headers/footers working:

### Option 1: VS Code Live Server
1. Install [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. Right-click `index.html` → “Open with Live Server”

### Option 2: Python HTTP Server
```bash
python -m http.server
```

---

## 🌐 Deploying to GitHub Pages

1. Push to a GitHub repo
2. Go to **Settings → Pages**
3. Set source to `/main` and root directory
4. Visit: `https://<your-username>.github.io/<repo-name>/`

---

## 🧹 Suggestions for Optimization

- Compress images using [TinyPNG](https://tinypng.com/) or [Squoosh](https://squoosh.app/)
- Offload large assets (e.g. `.mp4`) to YouTube, Cloudinary, or GitHub Releases
- Use modular includes for nav and footer to reduce HTML duplication

---

## 🧭 Author

**Adrian Hanna**  
Backpacker, photographer, and founder of *Explore with Adrian*

Instagram: [@explore.adrian](https://www.instagram.com/explore.adrian/)  
Facebook: [Adrian Hanna](https://www.facebook.com/profile.php?id=61577194507913)