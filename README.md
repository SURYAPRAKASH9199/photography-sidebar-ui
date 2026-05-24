# 📷 Photography Sidebar UI

A sleek, **pure CSS photography portfolio landing page** featuring a glassmorphism sidebar — built with **zero JavaScript**. The sidebar toggle is powered entirely by the CSS checkbox hack, making it a great demonstration of what CSS alone can achieve.

![Project Preview](camera.png)

---

## ✨ Features

- **Pure CSS Sidebar Toggle** — No JavaScript used; sidebar opens/closes via the CSS checkbox trick
- **Glassmorphism Design** — Frosted glass sidebar with `backdrop-filter: blur()` and subtle white shadows
- **Smooth Animations** — All transitions are CSS-based (`transition: all 0.4s linear`)
- **Font Awesome Icons** — Clean iconography for menu items and social links
- **Google Fonts (Poppins)** — Modern, elegant typography
- **Social Media Links** — Facebook, Instagram, Twitter, LinkedIn with hover scale effect
- **Fully Responsive Layout** — Background image covers the full viewport (`100vh`)

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure & semantic markup |
| CSS3 | Styling, animations, glassmorphism |
| Font Awesome 6 | Icons for nav and social links |
| Google Fonts | Poppins font family |

> ⚡ **No JavaScript. No frameworks. No libraries.** Just HTML & CSS.

---

## 📁 Project Structure

```
photography-sidebar-ui/
│
├── photography_page_css_project.html   # Main HTML file
├── photography_page_css_project.css    # All styles
├── camera.png                          # Background image
└── README.md                           # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/SURYAPRAKASH9199/photography-sidebar-ui.git
```

### 2. Navigate to the Folder

```bash
cd photography-sidebar-ui
```

### 3. Open in Browser

Simply open the HTML file in any modern browser:

```bash
# On Windows
start photography_page_css_project.html

# On Mac
open photography_page_css_project.html

# Or just double-click the file in your file explorer
```

> No build tools, no npm install, no setup required. ✅

---

## 🎨 How the CSS Checkbox Hack Works

This project uses a **hidden checkbox** to control the sidebar — a clever pure CSS technique:

```html
<!-- Hidden checkbox acts as the state controller -->
<input type="checkbox" id="check">

<!-- Label triggers the checkbox on click -->
<label for="check"><i class="fa-solid fa-bars"></i></label>
```

```css
/* When checkbox is checked, slide the sidebar in */
#check:checked ~ .sidebar_menu {
    left: 0;
}

/* Hide the open button when sidebar is open */
#check:checked ~ .btn-one {
    opacity: 0;
}
```

No JavaScript needed — just CSS sibling selectors (`~`) and `:checked` pseudo-class! 🎉

---

## 📸 Preview

| Closed State | Open State |
|---|---|
| Hamburger menu icon visible | Glassmorphism sidebar slides in |
| Full camera background shown | Sidebar with nav links & social icons |

---

## 🙋‍♂️ Author

**Surya Prakash**

[![GitHub](https://img.shields.io/badge/GitHub-SURYAPRAKASH9199-black?style=flat&logo=github)](https://github.com/SURYAPRAKASH9199)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E1306C?style=flat&logo=instagram)](https://www.instagram.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> 💡 *Built as a mini CSS project to practice glassmorphism, pure CSS interactions, and modern layout techniques.*
