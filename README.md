# HTML Crash Course for Beginner Web Developers

This crash course introduces the fundamentals of HTML (HyperText Markup Language) for beginners. Designed to be concise and practical, it covers the essentials of HTML in ~30–40 minutes, with no prior knowledge required. By the end, you'll understand how to structure web pages and be ready to explore CSS and JavaScript.

> **Note**: This guide assumes no coding experience. If you’re ready to build your first web page, follow along and try the examples in a code editor like [VS Code](https://code.visualstudio.com/).

## Table of Contents

- [What is HTML?](#what-is-html)
- [Setting Up Your Environment](#setting-up-your-environment)
- [Basic HTML Structure](#basic-html-structure)
- [Common HTML Elements](#common-html-elements)
- [Attributes in HTML](#attributes-in-html)
- [Semantic HTML](#semantic-html)
- [Forms and Input Elements](#forms-and-input-elements)
- [Best Practices](#best-practices)
- [What's Next?](#whats-next)
- [Example Project](#example-project)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## What is HTML?

HTML is the backbone of every web page, defining its structure and content. It uses **tags** to organize elements like headings, paragraphs, images, and links. Think of HTML as the skeleton of a website, with CSS (styling) and JavaScript (interactivity) adding the skin and muscles.

- **Key Facts**:
  - HTML stands for HyperText Markup Language.
  - It’s not a programming language but a markup language.
  - Current version: HTML5, widely supported by modern browsers.

## Setting Up Your Environment

To start coding HTML:

1. **Install a Code Editor**: Use [VS Code](https://code.visualstudio.com/) or alternatives like Sublime Text.
2. **Create a Project Folder**: Save your files with a `.html` extension (e.g., `index.html`).
3. **Open in a Browser**: Drag your `.html` file into a browser or use VS Code’s Live Server extension.

**Pro Tip**: Use `!` + Tab in VS Code to generate a basic HTML template.

## Basic HTML Structure

Every HTML document follows this structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

- `<!DOCTYPE html>`: Declares the document as HTML5.
- `<html lang="en">`: Root element, specifies language.
- `<head>`: Contains metadata (e.g., charset, title).
- `<body>`: Holds visible content.

## Common HTML Elements

HTML uses tags to define elements. Here are the most common:

#### Headings:`<h1>` to `<h6>` (largest to smallest). html

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

#### Paragraphs: `<p>` for text blocks.

```html
<p>This is a paragraph of text.</p>
```

#### Links: `<a>` with `href` attribute for navigation.

```html
<a href="https://example.com">Visit Example</a>
```

#### Images: `<img />` with `src` and `alt` attributes.

```html
<img src="image.jpg" alt="Description of image" />
```

#### Lists:

- Ordered (`<ol>`): Numbered list.
- Unordered (`<ul>`): Bulleted list.

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
<ul>
  <li>Item A</li>
  <li>Item B</li>
</ul>
```

### Attributes in HTML

Attributes provide additional information to tags, written as `name="value"`. Common attributes:

- `id`: Unique identifier for an element.
- `class`: Groups elements for styling or scripting.
- `src`: Specifies the source for images or scripts.
- `href`: Defines the URL for links.

#### Example:

```html
<img src="logo.png" alt="Company Logo" class="logo" />
```

### Semantic HTML

Semantic tags improve accessibility and SEO by clearly defining content roles. Use these instead of generic `<div>` tags:

- `<header>`: Page or section header.
- `<nav>`: Navigation menu.
- `<main>`: Primary content.
- `<article>`: Self-contained content.
- `<footer>`: Page or section footer.

Example:

```html
<header>
  <h1>My Blog</h1>
</header>
<main>
  <article>
    <h2>Post Title</h2>
    <p>Post content...</p>
  </article>
</main>
<footer>
  <p>© 2025 My Blog</p>
</footer>
```

### Forms and Input Elements

Forms collect user input using the `<form>` tag. Common input types include text, email, password, and buttons.

Example:

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required />
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required />
  <button type="submit">Submit</button>
</form>
```

- `action`: URL where form data is sent.
- `method`: GET or POST for data submission.
- `required`: Ensures the field isn’t empty.

## Best Practices

- **Use Semantic Tags**: Improve accessibility and SEO.
- **Validate Your HTML**: Use tools like [W3C Validator](https://validator.w3.org/).
- **Keep Code Clean**: Indent properly and comment complex sections.
- **Test Responsiveness**: Ensure your page works on mobile and desktop.
- **Optimize Images**: Use compressed images for faster loading.

## What's Next?

Now that you know HTML basics:

- **Learn CSS**: Style your pages with colors, layouts, and animations. Check out [Dev Path’s CSS Crash Course](https://devpath.pro/css-crash-course-for-web-developers/).
- **Explore JavaScript**: Add interactivity. See [Dev Path’s JavaScript Crash Course](https://devpath.pro/javascript-crash-course-for-beginner-web-developers/).
- **Build Projects**: Create a portfolio website or a simple blog to practice.

## Example Project

This repository contains a sample project to practice the concepts covered in this crash course. It includes:

- A simple HTML page with semantic structure.
- Examples of headings, paragraphs, links, images, lists, and a form.
- A basic layout using semantic tags like `<header>`, `<main>`, and `<footer>`.

### Getting Started

1. Clone this repository:

```bash
git clone https://github.com/TheDevPath/HTML-Crash-Course.git
```

- Open the project folder in your code editor.
- Open `index.html` in your browser to view the example page.

### Project Structure

```
your-repo/
├── index.html        # Main HTML file
├── images/           # Folder for images
└── README.md         # This file
```

Try It Out

- Add a new `<section>` with a heading and paragraph.
- Create a `<nav>` with links to other pages.
- Build a form to collect user feedback.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional examples. For issues or suggestions, open an issue on the GitHub repository.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

This crash course is based on the [Dev Path HTML Crash Course](https://devpath.pro/html-crash-course-for-beginner-web-developers/). Thanks to the Dev Path team for creating accessible learning resources for aspiring developers.

## Happy coding!
