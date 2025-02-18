# HTML-revison

# HTML Guide: Basic to Advanced

This guide covers HTML (HyperText Markup Language) from basic to advanced concepts, with examples and explanations. Use this as a reference to learn and practice HTML.

---

## Table of Contents
1. [Basic HTML Structure](#basic-html-structure)  
   Explains the fundamental layout of an HTML document, including essential elements like `<!DOCTYPE>`, `<html>`, `<head>`, and `<body>`.

2. [Basic HTML Tags](#basic-html-tags)  
   Covers fundamental HTML elements used for structuring content.  
   - **[Headings](#headings):** Defines different levels of headings (`<h1>` to `<h6>`).
   - **[Paragraphs](#paragraphs):** Represents blocks of text using the `<p>` tag.
   - **[Links](#links):** Creates hyperlinks using the `<a>` tag.
   - **[Images](#images):** Displays images using the `<img>` tag.
   - **[Lists](#lists):** Defines ordered (`<ol>`) and unordered (`<ul>`) lists.
   - **[Line Break](#line-break):** Inserts a line break using `<br>`.
   - **[Horizontal Rule](#horizontal-rule):** Adds a horizontal line using `<hr>`.

3. [Intermediate HTML Tags](#intermediate-html-tags)  
   Introduces more advanced HTML elements used for structuring and organizing content.  
   - **[Tables](#tables):** Creates tabular data structures using `<table>`, `<tr>`, `<td>`, etc.
   - **[Forms](#forms):** Enables user input through `<input>`, `<textarea>`, `<select>`, etc.
   - **[Divisions and Spans](#divisions-and-spans):** Helps group and style elements using `<div>` and `<span>`.
   - **[Semantic Elements](#semantic-elements):** Improves accessibility and SEO with elements like `<article>`, `<section>`, `<nav>`, etc.

4. [Advanced HTML Tags](#advanced-html-tags)  
   Explores specialized HTML elements for multimedia, embedding, and interactivity.  
   - **[Multimedia](#multimedia):** Integrates audio and video using `<audio>` and `<video>`.
   - **[Iframes](#iframes):** Embeds external content using `<iframe>`.
   - **[Semantic Elements for Accessibility](#semantic-elements-for-accessibility):** Enhances accessibility with tags like `<header>`, `<footer>`, `<main>`, etc.
   - **[Meta Tags for SEO](#meta-tags-for-seo):** Optimizes search engine visibility using `<meta>` tags.
   - **[Data Attributes](#data-attributes):** Stores custom data in elements using `data-*` attributes.
   - **[Progress and Meter](#progress-and-meter):** Displays progress and measurements with `<progress>` and `<meter>`.

5. [HTML5 Features](#html5-features)  
   Introduces modern HTML5 elements and APIs.  
   - **[Canvas](#canvas):** Enables dynamic graphics rendering with the `<canvas>` element.
   - **[Geolocation API](#geolocation-api):** Provides user location data using JavaScript.

---




---

## Basic HTML Structure
```html
<!DOCTYPE html> <!-- Declares the document type as HTML5 -->
<html lang="en"> <!-- Root element of the HTML document, specifies the language as English -->
<head>
    <meta charset="UTF-8"> <!-- Specifies the character encoding as UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Ensures proper rendering on mobile devices -->
    <title>Basic HTML Page</title> <!-- Title of the webpage (appears in the browser tab) -->
</head>
<body>
    <h1>Welcome to My Website</h1> <!-- Main heading -->
    <p>This is a paragraph of text.</p> <!-- Paragraph -->
</body>
</html>
```

---

## Basic HTML Tags

### Headings
```html
<h1>Main Heading</h1> <!-- Largest heading -->
<h2>Subheading</h2> <!-- Second-level heading -->
<h3>Sub-subheading</h3> <!-- Third-level heading -->
<h4>Lower-level heading</h4> <!-- Fourth-level heading -->
<h5>Small heading</h5> <!-- Fifth-level heading -->
<h6>Smallest heading</h6> <!-- Smallest heading -->
```

### Paragraphs
```html
<p>This is a paragraph of text.</p> <!-- Paragraph tag for text content -->
```

### Links
```html
<a href="https://example.com">Visit Example</a> <!-- Anchor tag for hyperlinks -->
```

### Images
```html
<img src="image.jpg" alt="Description of image"> <!-- Image tag with source and alternative text -->
```

### Lists
```html
<ul> <!-- Unordered list -->
    <li>Item 1</li> <!-- List item -->
    <li>Item 2</li>
</ul>
<ol> <!-- Ordered list -->
    <li>First item</li> <!-- List item -->
    <li>Second item</li>
</ol>
```

### Line Break and Horizontal Rule
```html
<p>First line.<br>Second line.</p> <!-- Line break tag -->
<hr> <!-- Horizontal rule tag -->
```

---

## Intermediate HTML Tags

### Tables
```html
<table> <!-- Table tag -->
    <tr> <!-- Table row -->
        <th>Header 1</th> <!-- Table header -->
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td> <!-- Table data -->
        <td>Data 2</td>
    </tr>
</table>
```

### Forms
```html
<form> <!-- Form tag for user input -->
    <label for="name">Name:</label> <!-- Label for input field -->
    <input type="text" id="name" name="name"> <!-- Text input field -->
    <label for="message">Message:</label> <!-- Label for textarea -->
    <textarea id="message" name="message"></textarea> <!-- Textarea for multi-line input -->
    <label for="options">Choose an option:</label> <!-- Label for dropdown -->
    <select id="options" name="options"> <!-- Dropdown menu -->
        <option value="option1">Option 1</option> <!-- Dropdown option -->
        <option value="option2">Option 2</option>
    </select>
    <button type="submit">Submit</button> <!-- Submit button -->
</form>
```

## Divisions and Spans
```html
<div style="background-color:lightblue; padding:10px;"> <!-- Block-level container -->
    <p>This is a block-level division.</p> <!-- Paragraph inside a div -->
    <span style="color:red;">This is an inline span inside a div.</span> <!-- Inline container -->
</div>
```

### Multimedia
```html
<audio controls> <!-- Audio player with controls -->
    <source src="audio.mp3" type="audio/mpeg"> <!-- Audio source file -->
</audio>
<video controls> <!-- Video player with controls -->
    <source src="video.mp4" type="video/mp4"> <!-- Video source file -->
</video>
```

### Iframes
```html
<iframe src="https://example.com" width="600" height="400"></iframe> <!-- Embeds another webpage -->
```


## Semantic Elements for Accessibility
```html
<header> <!-- Header section -->
    <h1>Website Title</h1> <!-- Main heading -->
</header>
<main> <!-- Main content section -->
    <article> <!-- Article section -->
        <h2>Article Heading</h2> <!-- Article heading -->
        <p>Article content goes here.</p> <!-- Article content -->
    </article>
</main>
<footer> <!-- Footer section -->
    <p>Footer Content</p> <!-- Footer content -->
</footer>
```

## Meta Tags for SEO
```html
<head>
    <meta name="description" content="This is an example of a meta description for SEO."> <!-- Meta description for search engines -->
    <meta name="keywords" content="HTML, SEO, Meta Tags"> <!-- Meta keywords for search engines -->
</head>
```

## Data Attributes
```html
<button data-user-id="123" onclick="alert(this.dataset.userId)">Click me</button> <!-- Button with custom data attribute -->
```

## Progress and Meter
```html
<progress value="70" max="100">70%</progress> <!-- Progress bar -->
<meter value="3" min="0" max="5">3 out of 5</meter> <!-- Meter for measurements -->
```

### Canvas
```html
<canvas id="myCanvas"></canvas> <!-- Canvas element for drawing graphics -->
<script>
    var canvas = document.getElementById("myCanvas"); // Get canvas element
    var ctx = canvas.getContext("2d"); // Get 2D rendering context
    ctx.fillStyle = "green"; // Set fill color
    ctx.fillRect(10, 10, 100, 50); // Draw a rectangle
</script>
```

### Geolocation API
```html
<script>
navigator.geolocation.getCurrentPosition(function(position) { // Get current location
    console.log(position.coords.latitude, position.coords.longitude); // Log latitude and longitude
});
</script>
```

