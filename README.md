# Premium Cars

A responsive landing/catalog site with article and vehicle cards, fully keyboard-accessible and supporting `prefers-reduced-motion`.

## Tech Stack

- HTML5
- CSS3 (Flexbox/Grid, media queries, CSS variables)
- Vanilla JavaScript (no frameworks)

## Features

- 📱 Responsive Layout — Adaptive design structured with modern CSS layout techniques (Flexbox & Grid), seamlessly adjusting to desktop, tablet, and mobile viewports.
- ♿ Text-based accessibility — the layout remains readable and does not break when the font size is changed in the browser.
- ⌨️ Keyboard accessibility — all interactive elements (navigation, cards, search) are reachable via Tab/Shift+Tab, with visible :focus styles and a logical focus order.
- **Semantic markup** — proper HTML tags and ARIA attributes are used where needed for correct screen reader support.
- 🎬 Loading animations - with respect for prefers-reduced-motion — animations are automatically disabled when the corresponding OS or browser setting is enabled.

## Project Structure

```
├── index.html          # Main page
├── Styles/             # Styles, including media queries and reduce-motion
├── js/
│   └── app.js          # UI logic (menu, cards, animations)
└── Img/                # Images and icons
```

## Accessibility

- Navigation is fully operable via keyboard.
- Visible `:focus-visible` styles are provided for interactive elements.
- Images include `alt` attributes.
- Proper heading hierarchy is maintained.
