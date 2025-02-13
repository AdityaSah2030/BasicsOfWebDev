# Complete Guide to HTML for Beginners

## Introduction
HTML (HyperText Markup Language) is the standard language used to create web pages. It consists of elements that structure the content on the web.

## Basic Structure of an HTML Document
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Page</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

## HTML Elements

### Headings
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Section Title</h3>
```

### Paragraphs and Line Breaks
```html
<p>This is a paragraph.</p>
<br> <!-- Line Break -->
<hr> <!-- Horizontal Line -->
```

### Text Formatting
```html
<b>Bold</b>
<i>Italic</i>
<u>Underline</u>
<small>Small text</small>
<big>Big text</big>
<mark>Highlighted text</mark>
<del>Strikethrough text</del>
<ins>Inserted text</ins>
```

### Subscript & Superscript
```html
H<sub>2</sub>O <!-- Subscript -->
E=mc<sup>2</sup> <!-- Superscript -->
```

## Lists

### Unordered List
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

### Ordered List
```html
<ol>
    <li>First Item</li>
    <li>Second Item</li>
</ol>
```

## Links and Images

### Anchor Tag (Links)
```html
<a href="https://example.com">Visit Example</a>
<a href="https://example.com" target="_blank">Open in New Tab</a>
```

### Image Tag
```html
<img src="image.jpg" alt="Description of Image" width="200" height="150">
```

## Page Layout Elements
```html
<header>Website Header</header>
<nav>Navigation Bar</nav>
<main>
    <section>Section Content</section>
    <article>Article Content</article>
    <aside>Sidebar Content</aside>
</main>
<footer>Footer Information</footer>
```

## Forms and Inputs

### Basic Form
```html
<form action="submit.php" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name">
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    <br>
    <input type="submit" value="Submit">
</form>
```

### Radio Buttons & Checkboxes
```html
<label>
    <input type="radio" name="gender" value="male"> Male
</label>
<label>
    <input type="radio" name="gender" value="female"> Female
</label>

<label>
    <input type="checkbox" name="subscribe" value="yes"> Subscribe to Newsletter
</label>
```

### Dropdown Menu
```html
<select name="city">
    <option value="newyork">New York</option>
    <option value="london">London</option>
</select>
```

### Text Area
```html
<textarea name="message" rows="4" cols="50" placeholder="Enter your message"></textarea>
```

## Tables
```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John</td>
        <td>25</td>
    </tr>
    <tr>
        <td>Jane</td>
        <td>28</td>
    </tr>
</table>
```

## Multimedia Elements

### Video
```html
<video width="320" height="240" controls>
    <source src="video.mp4" type="video/mp4">
</video>
```

### Audio
```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
```

### Embedding External Content (iframe)
```html
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```

## Forms of Input Elements
```html
<input type="text" placeholder="Enter text">
<input type="password" placeholder="Enter password">
<input type="email" placeholder="Enter email">
<input type="number" placeholder="Enter number">
<input type="date">
<input type="color">
<input type="file">
<input type="submit" value="Submit">
```

## Special HTML Elements

### Details & Summary
```html
<details>
    <summary>Click to Expand</summary>
    <p>More information here.</p>
</details>
```

### Progress & Meter
```html
<progress value="50" max="100"></progress>
<meter value="8" min="0" max="10"></meter>
```

## Comments in HTML
```html
<!-- This is a comment -->
```

## Conclusion
This guide covered the basics of HTML for beginners. Keep practicing by building simple web pages and experimenting with different elements.

