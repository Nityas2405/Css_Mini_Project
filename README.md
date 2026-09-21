# 🎞️ CSS Mini Project — Animated Sidebar Navigation

A mini frontend project built with **HTML and CSS only** (no JavaScript). Clicking the hamburger icon slides out a dark-themed sidebar with icon-based menu items, layered over a full-screen photography background.

---

## ✨ Features

- **Hamburger toggle** — click to slide the sidebar open, click the ✕ to close it
- **Pure CSS animation** — smooth slide-in transition with zero JavaScript
- **Icon-based menu** — Gallery, Shortcuts, Exhibits, Events, Store, Contact, Feedback
- **Hover highlights** — menu items respond visually on hover
- **Full-screen hero background** — dark, cinematic camera photograph
- **Social links footer** — Facebook, Twitter, Instagram, and YouTube icons
- **Minimal dark UI** — high-contrast, clean layout

## 🛠️ Built With

- **HTML5** — page structure
- **CSS3** — layout, transitions, and the slide-in animation
- **Font Awesome** — menu and social media icons

> The sidebar toggle is built using the CSS checkbox hack (a hidden `input[type="checkbox"]` with the `:checked` selector), which is how the whole interaction works without any JavaScript.

## 📁 Project Structure

```
Css_Mini_Project/
├── index (1).html      # Page markup
├── style.css           # All styling and animations
├── photo.jpg           # Hero background image
└── README.md
```

## 🚀 Getting Started

No build tools, dependencies, or installation needed.

### 1. Clone the repository

```bash
git clone https://github.com/Nityas2405/Css_Mini_Project.git
cd Css_Mini_Project
```

### 2. Open in a browser

Open the HTML file directly:

```bash
# macOS
open "index (1).html"

# Windows
start "index (1).html"
```

Or use VS Code's **Live Server** extension for auto-reload while editing.

## 🎨 Customization

- **Change the background** — replace `photo.jpg` with your own image (keep the same filename, or update the `background-image` URL in `style.css`)
- **Edit menu items** — add or remove list items in the sidebar `<ul>` in the HTML file
- **Swap icons** — browse [Font Awesome](https://fontawesome.com/icons) and change the icon class names
- **Adjust colors** — the dark theme colors are set in `style.css`
- **Change animation speed** — modify the `transition` duration on the sidebar container

## 📚 What I Learned

- Building interactive UI using **CSS-only techniques** (the checkbox hack) instead of JavaScript
- Using **CSS transitions and transforms** for smooth slide animations
- Working with **`position: fixed`** and z-index layering for overlay panels
- Integrating an **icon library** and aligning icons neatly with text labels
- Structuring a reusable navigation component

## 🔮 Future Improvements

- [ ] Make the sidebar fully responsive on mobile screens
- [ ] Rename `index (1).html` to `index.html` so it loads as the default page on GitHub Pages
- [ ] Add working links/pages for each menu item
- [ ] Improve keyboard accessibility (focus states, Esc to close)
- [ ] Deploy live via GitHub Pages

## 📬 Contact

**Nitya Sharma**
- GitHub: [@Nityas2405](https://github.com/Nityas2405)
