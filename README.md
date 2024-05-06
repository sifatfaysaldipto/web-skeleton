# Semantic HTML Layout Structure

This is a basic example of a semantic HTML layout structure. Semantic HTML provides meaning to the content of a web page by using elements that describe the structure of the content rather than just its appearance.

## HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <article>
                <h2>Heading</h2>
                <p>Content goes here...</p>
            </article>
            <article>
                <h2>Heading</h2>
                <p>Content goes here...</p>
            </article>
        </section>
        <aside>
            <h3>Related Links</h3>
            <ul>
                <li><a href="#">Link 1</a></li>
                <li><a href="#">Link 2</a></li>
                <li><a href="#">Link 3</a></li>
            </ul>
        </aside>
    </main>
    <footer>
        <p>&copy; 2024 Semantic HTML. All rights reserved.</p>
    </footer>
</body>
</html>
```

## This structure includes:

- **Header:** Contains navigation links.
- **Main:** Divided into sections and articles.
- **Aside:** Contains related links.
- **Footer:** Contains copyright information.

This layout structure helps improve accessibility, SEO, and maintainability of the web page.
