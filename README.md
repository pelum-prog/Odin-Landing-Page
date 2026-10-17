Odin Landing Page

 Introduction
This is the landing page project from The Odin Project's Flexbox section. It is a single-page website built with HTML and CSS, recreating a given design: a header with navigation, a hero section, an information section, a quote, a call-to-action and a footer.


Skills Demonstrated

1. Building page layouts with Flexbox
2. Using `display: flex`, `justify-content`, `align-items`, `flex-direction` and `gap`
3. Writing semantic HTML (`nav`, `header`, `main`, `section`, `footer`)
4. Applying the box model (margin, padding, border, width and height)
5. Styling text, buttons and colors with CSS
6. Using CSS nesting and positioning
7. Linking an external stylesheet to an HTML file

How I Built It

1. Reset default `margin` and `padding` with `*`.
2. Wrapped the nav and header in a `.Topmost` div with a dark background.
3. Used `display: flex` with `justify-content: space-between` to put the logo and links on opposite sides of the `nav`.
4. Removed link underlines and list bullets, then spaced the nav links with `gap`.
5. Made the `header` a flex row: text and sign-up button on the left, image placeholder on the right.
6. Centered the placeholder text by making `.content` a flex column with `justify-content: center`.
7. Styled the buttons with a blue background, rounded corners and no border.
8. Built the four info boxes in a `.BOX` flex container, using `gap` to space them evenly.
9. Placed each box caption below its box with `position: relative` and `top`.
10. Styled the quote `section` with a light gray background and left-aligned italic text.
11. Made the `.down` call-to-action a flex row, with `space-between` separating the text and button.
12. Centered the footer text with `display: flex` and `justify-content: center`.
13. Linked `Odin.css` to the HTML file with `<link rel="stylesheet">`.
