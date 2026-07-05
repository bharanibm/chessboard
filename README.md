# Chessboard Styling in CSS

A clean, responsive, and pixel-perfect 8x8 chessboard layout created using pure HTML5 semantic tags and modern CSS Flexbox layout techniques.

## 🚀 Live Demo
*(Optional: Add your GitHub Pages link here if you host it later!)*

## 🛠️ Tech Stack Used
* **HTML5:** Structured semantic markup using `<main>` and container elements.
* **CSS3:** Flexbox modules (`display: flex`), background gradients, and explicit dimension handling.

## 📁 File Structure
```text
├── chess.html   # Main HTML structural file
├── chess.css    # Layout and design rules
└── README.md    # Documentation file
```

## 💡 Key Learnings & Features Implemented
* **Flexbox Direction Manipulation:** Structured rows inside a parent container using `flex-direction: column` while handling individual squares horizontally using default flex rows.
* **Exact Sizing & Calculations:** Configured individual grid squares to an exact `50px` size, fitted securely into a bounded wrapper.
* **Absolute Center Alignment:** Utilized a centralized alignment technique to perfectly position the final chessboard into the absolute middle of any viewport height (`100vh`).
* **Box Model Management:** Enforced universal `box-sizing: border-box` to avoid internal borders from breaking row alignment and wrap limits.

---
*Part of my Web Technology Learning Repository.*
