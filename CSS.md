# Complete Guide to CSS for Beginners

## Introduction
CSS (Cascading Style Sheets) is used to style HTML elements and improve the visual presentation of web pages.

## CSS Syntax
```css
selector {
    property: value;
}
```

Example:
```css
p {
    color: blue;
    font-size: 16px;
}
```

## Ways to Apply CSS
### Inline CSS
```html
<p style="color: red;">This is an inline-styled paragraph.</p>
```
### Internal CSS
```html
<style>
p {
    color: blue;
}
</style>
```
### External CSS
```html
<link rel="stylesheet" href="styles.css">
```

## CSS Selectors
### Universal Selector
```css
* {
    margin: 0;
    padding: 0;
}
```
### Element Selector
```css
h1 {
    color: green;
}
```
### Class Selector
```css
.class-name {
    font-style: italic;
}
```
### ID Selector
```css
#unique-id {
    text-align: center;
}
```
### Grouping Selector
```css
h1, h2, p {
    font-family: Arial, sans-serif;
}
```

## Colors in CSS
### Named Colors
```css
p {
    color: red;
}
```
### RGB Colors
```css
p {
    color: rgb(255, 0, 0);
}
```
### Hex Colors
```css
p {
    color: #ff0000;
}
```

## CSS Box Model
```css
div {
    width: 200px;
    height: 100px;
    padding: 10px;
    border: 5px solid black;
    margin: 20px;
}
```

## CSS Display & Positioning
### Display
```css
div {
    display: block;
}
span {
    display: inline;
}
```
### Positioning
```css
div {
    position: absolute;
    top: 50px;
    left: 100px;
}
```

## Text Properties
```css
p {
    text-align: center;
    text-decoration: underline;
    font-weight: bold;
    font-family: Arial, sans-serif;
    text-transform: uppercase;
}
```

## CSS Flexbox
```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

## CSS Grid
```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 10px;
}
```

## CSS Units
### Absolute Units
- px, cm, mm, in
### Relative Units
- %, em, rem, vh, vw

## CSS Transitions & Animations
### Transitions
```css
div {
    transition: all 0.5s ease;
}
```
### Animations
```css
@keyframes slide {
    from { left: 0; }
    to { left: 100px; }
}
```

## Backgrounds and Borders
### Background Image
```css
body {
    background-image: url('image.jpg');
    background-size: cover;
}
```
### Border Radius
```css
div {
    border-radius: 10px;
}
```

## Responsive Design
```css
@media (max-width: 600px) {
    body {
        background-color: lightgray;
    }
}
```

## z-Index
```css
div {
    position: absolute;
    z-index: 10;
}
```

## Opacity and Visibility
```css
div {
    opacity: 0.5;
    visibility: hidden;
}
```

## Conclusion
This guide covered the basics of CSS, including styling techniques, layout design, and responsive web design. Keep practicing to master CSS!

