# html-css-basics

## Definition
HTML, which stands for HyperText Markup Language, is the standard markup language used to create and structure content on web pages. It provides a way to describe the structure of web documents using a system of tags and attributes.

# Key concepts
**1. Markup Language:** 
HTML uses tags to define the structure and content of web pages. Tags are surrounded by angle brackets (< >) and typically come in pairs: an opening tag and a closing tag (</ >). 
For example:
```html
<p>This is a paragraph.</p>
```
**2. Elements:** 
Elements are components defined by tags that encapsulate content. They can be nested within each other to create hierarchical structures. Examples include headings `(<h1> to <h6>)`, paragraphs `(<p>)`, lists `(<ul>, <ol>, <li>)`, links `(<a>)`, images `(<img>)`, etc.

**3. Attributes:**
Attributes provide additional information about an element and are specified within the opening tag. They are usually in name-value pairs and modify the behavior or appearance of an element.
For example:
```html
<a href="https://www.example.com">Visit Example</a>
```
**4. Document Structure:** 
An HTML document typically consists of a hierarchy of elements enclosed within an opening <html> tag and a closing </html> tag. It often includes <head> and <body> sections.
```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```
**5. Semantics:**
HTML5 introduced semantic elements `(<header>, <footer>, <nav>, <section>, <article>, <aside>, <main>, <figure>, <figcaption>, etc.)` that provide meaning to the content, improving accessibility, SEO, and structuring flexibility.
**6. Hyperlinks and Images::**
HTML allows embedding hyperlinks (<a> tags) to navigate between pages or sections within a page, and embedding images (<img> tags) to display graphics.

**Basic example**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
        }
        h1 {
            color: #333;
        }
        p {
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Us</h2>
        <p>This is a sample website demonstrating HTML and CSS.</p>
        <img src="sample.jpg" alt="Sample Image">
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Web Design</li>
            <li>Graphic Design</li>
            <li>Digital Marketing</li>
        </ul>
    </section>
    
    <footer>
        <p>&copy; 2024 Sample Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

**CheatSheet**
![Html tags](https://github.com/kaleeswariP/html-css-basics/assets/22699303/1fa38d69-39d8-49ad-b4fb-3ca4b817c94b)

# Questions & Answers:

## 1. What is the purpose of DOCTYPE in HTML?
DOCTYPE declaration specifies the version being used and helps the browser to render the page correctly.

## 2. Explain the difference between HTML and XHTML?
XHTML is stricter and more XML-compliant version of HTML. It requires well-formed documents, adheres to XML syntax, and has stricter rules for element and attribute usage.

## 3. What are the new features in HTML5?
* new semantic tags, Some of these elements include <header>, <footer>, <nav>, <section>, <article>, <aside>, <main>, <figure>, and <figcaption>.
* Multimedia Support:`<audio> and <video> elements for embedding audio and video content with native controls.
* Graphics and Animation: HTML5 introduced the <canvas> element, which provides a 2D drawing API that allows dynamic rendering of graphics, animations, charts, and more using JavaScript.
* Form Enhancements: New input types such as email, url, tel, number, date, time, color, etc., which provide improved user experience and validation support. New attributes like placeholder, required, autocomplete, autofocus, and pattern for enhanced form control and usability.
* Web Storage: HTML5 introduced the localStorage and sessionStorage APIs, 

## 4. What is the purpose of the <meta> tag in HTML?
Metadata is data about data, which provides additional information about the document itself rather than its content. The <meta> tag does not have a closing tag and is typically placed within the <head> section of an HTML document.
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="This is a description of the web page">
<meta name="keywords" content="HTML, CSS, JavaScript, web development">
<meta name="author" content="John Doe">
<meta name="robots" content="index, follow">
<meta http-equiv="refresh" content="5;url=https://example.com">
```
**Purpose of the <meta> Tag:** SEO (Search Engine Optimization), Viewport Control, Social Media Sharing.

## 5. Explain the difference between <div> and <span> tags?
<div> is a block-level element used for grouping and structuring content.
<span></span> is an inline element used for applying styles to a specific part of text.

## 6. What is the significance of the alt attribute in the <img> tag?
The alt attributes provides alternative text for an image, which is displayed if the image acnnot be loaded. It is also used for accessibility aiding screen readers.

## 7. How does the <iframe> tag work in the HTML?
The <iframe> tag is used to embed an external document within an HTML document. It's commonly used to embed videos, maps, or other ecternal content.





