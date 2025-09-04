## What is HTML?
HTML (HyperText Markup Language) is the standard markup language used to create and structure content on the web. It defines the layout and elements of a webpage using tags.

##  Basic Structure of an HTML Document
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>Main Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>

- <!DOCTYPE html>: Declares HTML5 document type.
- <html>: Root element.
- <head>: Metadata, title, links.
- <body>: Visible content.

## What Are Tags, Elements, and Attributes?
- Tags: Keywords in angle brackets (e.g.,<p>) that define elements.
- Elements: Complete structure with opening tag, content, and closing tag.
- Attributes: Extra info added to tags (e.g., href, src) written as name="value".

## Block-Level vs Inline Elements
- Block-level: Start on a new line, take full width (e.g., <div>, <p>, <h1>).
- Inline: Flow within text, take up only necessary space (e.g., <span>, <a>, <strong>).

## Semantic vs Non-Semantic Tags
- Semantic: Clearly describe their meaning (e.g., <article>, <section>, <nav>, <footer>).
- Non-semantic: Generic containers (e.g., <div>, <span>).

## Common HTML Tags
<h1><h6> - Headings (largest to smallest)
<P> - Paragraph
<a> - Hyperlink
<img> - Image
<ul>, <ol>, <li> - Lists
<table> - Table structure
<form>- user input forms

## Void (Self-Closing) Elements
These don’t require closing tags:
<br>   <!-- Line break -->
<hr>   <!-- Horizontal rule -->
<img>  <!-- Image -->
<input> <!-- Form input -->

##  Creating Hyperlinks
<a href="https://example.com">Visit Example</a>
- href: Specifies the URL


## Adding Images
<img src="image.jpg" alt="Description">
- src: Image path
- alt: Text shown if image fails to load (important for accessibility)

##  Lists in HTML
- Unordered List:
  <ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
- Ordered List:
<ol>
  <li>First</li>
  <li>Second</li>
</ol>

## HTML Forms (Basic)
<form action="/submit" method="post">
  <input type="text" name="username">
  <input type="submit" value="Submit">
</form>

## HTML Comments
<!-- This is a comment -->

##  Accessibility Best Practices
- Use semantic tags.
- Add alt text to images.
- Use proper heading hierarchy (<h1> to <h6>).
- Avoid using only color to convey meaning.

##  HTML and CSS Integration
<link rel="stylesheet" href="style.css">
- Links external CSS to style HTML elements.









