# Premium Car

A responsive landing/catalog site with article and vehicle cards, fully keyboard-accessible and supporting `prefers-reduced-motion`.

## Tech Stack

- HTML5
- CSS3 (Flexbox/Grid, media queries, CSS variables)
- Vanilla JavaScript (no frameworks)

## Features

- **Responsive layout** — displays correctly on desktop, tablet, and mobile devices.
- **Keyboard accessibility** — all interactive elements (navigation, cards, search) are reachable via `Tab`/`Shift+Tab`, with visible `:focus` styles and a logical focus order.
- **Semantic markup** — proper HTML tags and ARIA attributes are used where needed for correct screen reader support.
- **Animations** — smooth transitions and effects (card appearance, hover states, etc.).
- **`prefers-reduced-motion` support** — when the system's reduced-motion setting is enabled, animations are disabled/simplified so users sensitive to on-screen motion aren't affected.

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
