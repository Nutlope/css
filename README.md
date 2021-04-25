# CSS Knowledge

> A repo to document my knowledge on CSS.

```css
/* Box Model: Magin is outside the border, padding is inside */

box-sizing: border-box; /* makes it so that padding doesn't add to the width */
padding: 20px 10px; /* top, right, bottom, left OR top/bottom, left/right */
text-decoration: none; /* to get rid of link underline */
```

CSS Fonts

- Use google fonts for custom fonts, add link in head and use in CSS
- We use families of fonts in case one isn't available in a browser
- Common properties are font-family, font-size, and line-height (spacing)

```css
/* Background */
.blog-post p {
  color: white;
  background-image: url(./author.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  background-attachement: fixed;
}
```

```css
/* Displays */
* {
	display: none /* Hides element completely */
	display: block /* Makes it into a block so new line (1 default) */
	display: inline /* Makes it into an inline document (another default) */
	display: inline-block /* Not sure when to use this */
}
```

Centering a div

- margin: auto on left and right (margin 0 auto) will center a block element
- A div is a block element by default but need to give it a height and width

Responsive Design

- Use media queries to show different things on the screen depending on size
