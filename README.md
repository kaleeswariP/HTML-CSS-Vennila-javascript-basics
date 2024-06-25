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

**6. Hyperlinks and Images:**
HTML allows embedding hyperlinks `(<a> tags)` to navigate between pages or sections within a page, and embedding images `(<img> tags)` to display graphics.

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
* new semantic tags, Some of these elements include `<header>, <footer>, <nav>, <section>, <article>, <aside>, <main>, <figure>, and <figcaption>`.
* Multimedia Support:`<audio> and <video>` elements for embedding audio and video content with native controls.
* Graphics and Animation: HTML5 introduced the `<canvas>` element, which provides a 2D drawing API that allows dynamic rendering of graphics, animations, charts, and more using JavaScript.
* Form Enhancements: New input types such as email, URL, tel, number, date, time, color, etc., which provide improved user experience and validation support. New attributes like placeholder, required, autocomplete, autofocus, and pattern for enhanced form control and usability.
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

## 5. Explain the difference between `<div>` and `<span>` tags.
The `<div>` is a block-level element used for grouping and structuring content.
`<span></span>` is an inline element used for applying styles to a specific part of text.

## 6. What is the significance of the alt attribute in the `<img>` tag?
The alt attributes provide alternative text for an image, which is displayed if the image cannot be loaded. It is also used for accessibility aiding screen readers.

## 7. How does the `<iframe>` tag work in the HTML?
The `<iframe>` tag is used to embed an external document within an HTML document. It's commonly used to embed videos, maps, or other external content.

## 8. How to open a link in a new tab using HTML?
set the target attribute of the <a> tag to "_blank".
```HTML
<a href="https://example.com" target="_blank">Visit Example</a>.
```

## What is the difference between `<strong>` and `<b>` tags?
The `<strong>` is a semantic tag indicating strong importance, while `<b>` is a presentational tag for bold text. `<strong>` is preferred for meaningful text.

## How do you create a numbered list in HTML?
Create a numbered list in HTML, you use the `<ol> (ordered list)` tag in combination with the `<li> (list item)` tag.

```html
<!DOCTYPE html>
<html>
<head>
    <title>Numbered List Example</title>
</head>
<body>
    <h1>My Numbered List</h1>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
    </ol>
</body>
</html>
```

## Common tags

**Headings and Paragraphs:**
* `<h1> to <h6>`
* `<p>`
  
**Lists:**
* Ordered lists: `<ol>, <li>`
* Unordered lists: `<ul>, <li>`
* Description lists: `<dl>, <dt>, <dd>`

**Links and Navigation:**
* Hyperlinks: `<a>`
* Navigation menus
  
**Images and Media:**
* Embedding images: `<img>`
* Embedding videos: `<video>, <source>`
* Embedding audio: `<audio>, <source>`
  
**Tables:**
* Basic table structure: `<table>, <tr>, <td>, <th>`
* Table attributes: colspan, rowspan, border
  
**Forms:**
* Form element: `<form>`
* Input elements: `<input>, <textarea>, <button>, <select>, <option>, <label>`
* Form attributes: action, method, name, id
  
**Semantic HTML:**
* Header: `<header>`
* Navigation: `<nav>`
* Main content: `<main>`
* Section: `<section>`
* Article: `<article>`
* Aside: `<aside>`
* Footer: `<footer>`
  
**Metadata:**
* Meta tags: `<meta>`
* Title: `<title>`
* Linking stylesheets: `<link>`
  
**HTML5 Features:**
* New semantic elements: `<section>, <article>, <nav>, <footer>, <header>`
* Multimedia elements: `<audio>, <video>`
* Canvas for drawing: `<canvas>`
* Geolocation API
* Local storage: localStorage, sessionStorage
  
**Accessibility:**
* ARIA roles and attributes
* Alt text for images
* Tabindex and keyboard navigation
  
**Responsive Web Design:**
* Viewport meta tag: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
* Media queries in CSS
  
**Best Practices:**
* Using semantic HTML
* Ensuring accessibility
* Properly structuring HTML documents
* Minimizing inline styles and scripts

## Input tag
The `<input>` tag in HTML is used to create interactive controls within a web form that allow users to input data. The `<input>` element is versatile and supports a wide variety of input types. 

## Common Attributes
* **type:** Specifies the type of input control. This is a required attribute for the `<input>` tag.
* **name** Defines the name of the input element. The name attribute is used to reference form data after a form is submitted.
* **id:** Provides a unique identifier for the input element. Useful for targeting with CSS or JavaScript.
* **Value:** Specifies the initial value of the input element.
* **Placeholder:** Provides a hint to the user of what can be entered in the input field.
* **Required:** Specifies that the input field must be filled out before submitting the form.
* **read-only:** Makes the input field non-editable.
* **disabled:** Disables the input field, preventing user interaction.
* **maxlength:** Defines the maximum number of characters allowed in the input field.
* **pattern:** Specifies a regular expression that the input's value must match for validation.

## Types of `<input>`

**text:** A single-line text input field.
```HTML
<input type="text" name="username" placeholder="Enter your username">
```
**password:** A single-line text input field that obscures the entered text.
```html
<input type="password" name="password" placeholder="Enter your password">
```
**email:** A single-line text input field for email addresses, with built-in validation.
```html
<input type="email" name="email" placeholder="Enter your email">
```
**number:** An input field for entering numbers, with optional attributes min, max, and step.
```html
<input type="number" name="quantity" min="1" max="10" step="1">
```
**tel:** An input field for entering telephone numbers.
```html
<input type="tel" name="phone" placeholder="Enter your phone number">
```
**url:** An input field for entering URLs, with built-in validation.
```html
<input type="url" name="website" placeholder="Enter your website">
```
**search:** A single-line text input field for search queries.
```html
<input type="search" name="search" placeholder="Search...">
```
**date:** An input field for selecting a date.
```html
<input type="date" name="birthday">
```
**time:** An input field for selecting a time.
```html
<input type="time" name="meeting-time">
```
**color:** An input field for selecting a color.
```html
<input type="color" name="favcolor">
```
**checkbox:** A check box that allows the user to select one or more options.
```html
<input type="checkbox" name="subscribe" value="newsletter"> Subscribe to newsletter
```
**radio:** A radio button that allows the user to select one option from a group.
```html
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```
**file:** An input field for uploading files.
```html
<input type="file" name="profile-picture">
```
**submit:** A button that submits the form.
```html
<input type="submit" value="Submit">
```
**reset:** A button that resets the form to its initial state.
```html
<input type="reset" value="Reset
```
**button:** A generic button that can be programmed with JavaScript.
```html
<input type="button" value="Click Me" onclick="alert('Button clicked!')">
```

## Example Form
```html
<!DOCTYPE html>
<html>
<head>
    <title>Sample Form with Various Input Types</title>
    <style>
        label {
            display: inline-block;
            width: 140px;
        }
        .error {
            color: red;
        }
    </style>
    <script>
        function validateForm() {
            var username = document.getElementById("username").value;
            var password = document.getElementById("password").value;
            var email = document.getElementById("email").value;
            var dob = document.getElementById("dob").value;
            var gender = document.querySelector('input[name="gender"]:checked');
            var phone = document.getElementById("phone").value;
            var url = document.getElementById("website").value;
            var color = document.getElementById("color").value;
            var errors = [];

            if (username === "") {
                errors.push("Username is required");
            }
            if (password === "") {
                errors.push("Password is required");
            }
            if (email === "") {
                errors.push("Email is required");
            }
            if (dob === "") {
                errors.push("Date of Birth is required");
            }
            if (!gender) {
                errors.push("Gender is required");
            }
            if (phone === "") {
                errors.push("Phone number is required");
            }
            if (url === "") {
                errors.push("Website URL is required");
            }
            if (color === "") {
                errors.push("Favorite color is required");
            }

            if (errors.length > 0) {
                document.getElementById("errorMessages").innerHTML = errors.join("<br>");
                return false;
            } else {
                alert("Form submitted successfully!");
                return true;
            }
        }
    </script>
</head>
<body>
    <h1>Sample Registration Form</h1>
    <div id="errorMessages" class="error"></div>
    <form onsubmit="return validateForm()">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" placeholder="Enter your username" required><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required><br><br>

        <label for="website">Website:</label>
        <input type="url" id="website" name="website" placeholder="Enter your website" required><br><br>

        <label for="color">Favorite Color:</label>
        <input type="color" id="color" name="favcolor" required><br><br>

        <label for="quantity">Quantity:</label>
        <input type="number" id="quantity" name="quantity" min="1" max="10" step="1" value="1"><br><br>

        <label for="range">Satisfaction:</label>
        <input type="range" id="range" name="satisfaction" min="0" max="10"><br><br>

        <label for="profile-picture">Profile Picture:</label>
        <input type="file" id="profile-picture" name="profile-picture"><br><br>

        <label for="bio">Biography:</label>
        <textarea id="bio" name="bio" placeholder="Tell us about yourself..."></textarea><br><br>

        <label for="newsletter">Subscribe:</label>
        <input type="checkbox" id="newsletter" name="subscribe" value="newsletter"> Subscribe to newsletter<br><br>

        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
    </form>
</body>
</html>
```

### How to set the default value to HTML form inputs

* We can set the initial value using the `value` attribute to the input tag.
* You can set default values to HTML form fields using JavaScript by accessing the DOM elements and assigning values to their value attributes in the middle of the program.
```html
<script>
 function setDefaultValues() {
            document.getElementById('username').value = 'JohnDoe';
            document.getElementById('password').value = 'password123';
            document.getElementById('email').value = 'john.doe@example.com';
            document.getElementById('dob').value = '1990-01-01';
            document.getElementById('male').checked = true;
            document.getElementById('phone').value = '123-456-7890';
            document.getElementById('website').value = 'https://www.example.com';
            document.getElementById('color').value = '#ff0000';
            document.getElementById('quantity').value = 5;
            document.getElementById('range').value = 7;
            document.getElementById('bio').value = 'This is a sample biography.';
            document.getElementById('newsletter').checked = true;
        }

        // Set default values when the page loads
        window.onload = setDefaultValues;
</script>
```



