# html-css-bootcamp

Fork this repository to your GitHub account

## Tasks
### Task 1
Fix all HTML and CSS errors in files *broken.html* and *broken-style.css* (at least 10), rename them to *fixed.html* and *fixed-style.css*.
Make the page structurally correct, replace generic divs with suitable semantic elements, add meaningful alt text, and correct the CSS so the page displays neatly with working margin and padding.

### Task 2
Cheat-sheet mini project

Create a simple page called cheatsheet.html with an external file cheatsheet.css.

#### Brief
Create a semantic page using header, main, section, and footer.
Add a heading: My HTML & CSS Cheat Sheet.
Add one section with at least 10 useful HTML tags.
Add another section with at least 10 useful CSS properties.
Link an external stylesheet.
Use margin and padding so the page looks neat.
Style the header and footer with a different background colour.

#### Starter HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My HTML & CSS Cheat Sheet</title>
  <link rel="stylesheet" href="cheatsheet.css" />
</head>
<body>
  <header>
    <h1>My HTML & CSS Cheat Sheet</h1>
    <p>A quick revision page for Unit 2.</p>
  </header>

  <main>
    <section>
      <h2>HTML tags to remember</h2>
      <ul>
        <li>&lt;header&gt;</li>
        <li>&lt;nav&gt;</li>
        <li>&lt;main&gt;</li>
        <li>&lt;section&gt;</li>
        <li>&lt;article&gt;</li>
        <li>&lt;footer&gt;</li>
        <li>&lt;a&gt;</li>
        <li>&lt;img&gt;</li>
        <li>&lt;table&gt;</li>
        <li>&lt;form&gt;</li>
      </ul>
    </section>

    <section>
      <h2>CSS properties to remember</h2>
      <ul>
        <li>color</li>
        <li>background-color</li>
        <li>font-size</li>
        <li>font-family</li>
        <li>margin</li>
        <li>padding</li>
        <li>border</li>
        <li>width</li>
        <li>height</li>
        <li>text-align</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>Created for revision practice.</p>
  </footer>
</body>
</html>
```

#### Starter CSS
```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f4f4;
  color: #222;
}

header,
footer {
  background: #0f6a6e;
  color: white;
  padding: 20px;
}

main {
  padding: 20px;
}

section {
  background: white;
  border: 1px solid #ddd;
  margin-bottom: 16px;
  padding: 16px;
}

h1, h2 {
  margin-top: 0;
}
```

#### Submission checklist
I corrected the HTML structure.
I used semantic elements where suitable.
I added meaningful alt text to the image.
I corrected CSS syntax errors.
I used margin and padding clearly.
I submitted a working editor link or zip file.
I created a separate cheat-sheet page with at least 10 HTML tags and 10 CSS properties.
