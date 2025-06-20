A responsive landing page showcasing a premium headphone product, 
closely following the Figma design. Built with HTML5 and CSS3, 
with mobile-friendly breakpoints, interactive states, and pixel-perfect fidelity.# 🎧 Headphones Landing Page

Welcome to the **Headphones** responsive landing page project, crafted from a Figma design. This project demonstrates clean HTML and CSS practices, responsive behavior, and subtle interactive effects.

---

## 📁 Project Structure

headphones/
├── index.html # Main HTML file
├── styles.css # CSS styles
├── assets/ # Images, fonts, icons
└── README.md # Project documentation (this file)

yaml
Copier
Modifier

---

## 🎨 Design Guidelines

This project strictly follows the Figma design specs.

- **Figma Access**: Duplicate the project into your own Drafts from the provided link.
- **Fonts Required**:
  - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
  - Spin Cycle OT (external link or provided file)

> ⚠️ If a float value appears in the design (e.g., 13.678px), feel free to round for cleaner code.

---

## 💡 Features

- ✅ Fully responsive layout
- 📱 Mobile version loads automatically at `480px` or less
- 🔗 Link hover & active color: `#FF6565`
- 🧼 Button hover/active state: `opacity: 0.9`
- 📏 Maximum content width: `1000px` and centered

---

## 📐 Responsive Behavior

Media query triggers layout change:
```css
@media (max-width: 480px) {
  /* Mobile styles here */
}
