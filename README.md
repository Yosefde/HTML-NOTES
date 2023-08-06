# HTML-NOTES
**Introduction to HTML**

HTML, short for HyperText Markup Language, is the fundamental building block of the World Wide Web. It is a markup language used to create the structure and layout of web pages. HTML allows web developers to define the content and structure of a webpage by using various elements and tags.

**HTML Document Structure**

An HTML document consists of several parts, including the document type declaration, the `<html>` element, the `<head>` section, and the `<body>` section.

1. **Document Type Declaration (DTD):** The DTD is the first line of an HTML document and specifies the version of HTML being used. It informs the browser about the type of markup language the document adheres to.

Example:
```html
<!DOCTYPE html>
```

2. **The `<html>` Element:** The `<html>` element encloses the entire HTML document and serves as the root element. It contains the `<head>` and `<body>` elements.

```html
<html>
  <head>
    <!-- Metadata and other information -->
  </head>
  <body>
    <!-- Visible content of the webpage -->
  </body>
</html>
```

3. **The `<head>` Section:** The `<head>` element is not visible on the webpage itself. Instead, it contains meta-information about the document, such as the page title, character encoding, links to external resources (CSS, JavaScript), and more.

```html
<head>
  <title>Page Title</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles.css">
</head>
```

4. **The `<body>` Section:** The `<body>` element contains the visible content of the webpage, including text, images, videos, links, and other multimedia elements.

```html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a sample paragraph.</p>
  <img src="image.jpg" alt="Sample Image">
  <a href="https://www.example.com">Visit Example Website</a>
</body>
```

**HTML Elements and Tags**

HTML elements are the building blocks used to define the structure and content of a webpage. Each element is enclosed by an opening tag `<tag>` and a closing tag `</tag>`. The content goes between the opening and closing tags.

Here are some common HTML elements:

1. **Headings:** Headings represent various levels of titles and subtitles. They range from `<h1>` (most important) to `<h6>` (least important).

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

2. **Paragraphs:** The `<p>` element is used for paragraphs of text.

```html
<p>This is a paragraph.</p>
```

3. **Links:** The `<a>` element creates hyperlinks to other web pages or resources.

```html
<a href="https://www.example.com">Click here to visit Example Website</a>
```

4. **Images:** The `<img>` element is used to display images on a webpage.

```html
<img src="image.jpg" alt="Image description">
```

5. **Lists:** HTML supports ordered `<ol>` and unordered `<ul>` lists, along with list items `<li>`.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```

**HTML Attributes**

HTML attributes provide additional information about elements and modify their behavior. They are specified within the opening tag of an element.

```html
<element attribute="value">Content</element>
```

For example, the `<img>` element can have attributes such as `src` (source) and `alt` (alternate text).

```html
<img src="image.jpg" alt="Description of the image">
```

**HTML Forms**

HTML forms allow users to input data and submit it to the server for processing. Forms use various input elements like text fields, checkboxes, radio buttons, and buttons.

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="4" required></textarea>

  <input type="submit" value="Submit">
</form>
```



HTML is the backbone of the web, allowing developers to create structured and interactive web pages. Understanding HTML is essential for anyone looking to build websites, and this introductory note serves as a foundation for further exploration and learning in web development. As you delve deeper into the world of web development, you'll encounter CSS (Cascading Style Sheets) and JavaScript, which together with HTML, form the core technologies of modern web development. Happy coding!
