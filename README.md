# Frontend Mentor - 3-column preview card component solution

This is a clean, responsive, and modern solution to the 3-column preview card component challenge on Frontend Mentor.

## The challenge

The challenge was to build a 3-column preview card component and get it looking as close to the design as possible using HTML and CSS. The component needed to be fully responsive, handling both mobile and desktop layouts seamlessly, while managing custom button states and distinct background colors for each car category.

## Links

- Solution URL: [https://github.com/veon321/3-column-preview-card-component](https://github.com/veon321/3-column-preview-card-component)
- Live Site URL: [https://veon321.github.io/3-column-preview-card-component/](https://veon321.github.io/3-column-preview-card-component/)

## Built with

- Semantic HTML5 markup (including `<section>` blocks for each column and proper accessibility header hierarchy)
- CSS Custom Properties (Variables) for a clean, theme-ready color palette
- Flexbox layout for structural alignment and layout axis swapping
- Modern CSS Math Functions (`clamp()`) for fluid typography and responsive scaling without rigid text jumps
- Google Fonts (Lexend Deca & Big Shoulders Display)

## Features

- **Perfect Multi-Column Symmetry:** By using `flex: 1` on each car category container (`.sedans`, `.suv`, `.luxury`), the layout forces all three columns to share the exact same width dynamically, maintaining perfect visual balance across all desktop monitor sizes.
- **Fluid Typography & Adaptive Padding:** The headers (`h2`), text descriptions, and internal paddings scale fluidly using `clamp()`. This ensures the content shrinks gracefully on smaller tablets and laptops before hitting the main mobile breakpoint.
- **Smart Button Layout via Auto-Margins:** The "Learn More" buttons always stay perfectly anchored to the bottom of each card, regardless of text length, thanks to a clever Flexbox trick (`margin-top: auto`).
- **Interactive Button States:** Buttons feature an elegant inverted hover effect. On hover, the solid background becomes transparent, revealing a clean white border, while the text color switches to match the exact background color of its respective card column.
- **Robust Screen Centering:** The component stays perfectly centered both vertically and horizontally via modern `height: 100vh` on the body for a clean presentation, automatically adapting to a flexible scrolling height on mobile platforms (`height: auto`).
