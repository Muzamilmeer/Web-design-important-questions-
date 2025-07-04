# Web-design-important-questions-
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Dev Unit 1: Q&A</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<style>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  background: #f5f7fa;
  color: #333;
  line-height: 1.6;
  padding-bottom: 60px;
}

/* Header */
header {
  background: linear-gradient(90deg, #0077ff, #00c2ff);
  color: white;
  text-align: center;
  padding: 30px 20px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

header h1 {
  font-size: 28px;
  letter-spacing: 1px;
}

/* Main content */
main {
  max-width: 900px;
  margin: 30px auto;
  padding: 0 20px;
}

/* Section styling */
section {
  background: white;
  border-radius: 12px;
  padding: 25px;
  margin-bottom: 30px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
  transition: transform 0.3s ease;
}

section:hover {
  transform: translateY(-4px);
}

h2 {
  margin-bottom: 15px;
  font-size: 22px;
  color: #0077ff;
  border-left: 5px solid #00c2ff;
  padding-left: 10px;
}

/* Q&A */
.qa p,
.qa li {
  margin-bottom: 12px;
}

.qa li {
  list-style-type: decimal;
  padding-left: 10px;
}

ol {
  padding-left: 20px;
}

/* Pre/code blocks */
pre,
code {
  background-color: #f0f0f0;
  font-family: monospace;
  padding: 8px 10px;
  border-radius: 6px;
  display: inline-block;
  overflow-x: auto;
  color: #000;
}

/* Footer */
footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  background: #222;
  color: #ccc;
  text-align: center;
  padding: 10px;
  font-size: 14px;
}
</style>
  <header>
    <h1>Unit 1: HTML, CSS & JavaScript - Questions & Answers</h1>
  </header>
  <main>
    <section>
      <h2>🔵 HTML Questions & Answers</h2>
      <ol>
        <li><strong>What is HTML, and what is its purpose?</strong><br>HTML (HyperText Markup Language) is the standard language for creating webpages. It structures content on the web.</li>
        <li><strong>What are the basic structure and elements of an HTML document?</strong><br>It includes: <code>&lt;!DOCTYPE html&gt;</code>, <code>&lt;html&gt;</code>, <code>&lt;head&gt;</code>, <code>&lt;title&gt;</code>, <code>&lt;body&gt;</code></li>
        <li><strong>How do you create a hyperlink in HTML?</strong><br><code>&lt;a href="https://example.com"&gt;Link&lt;/a&gt;</code></li>
        <li><strong>What is the difference between &lt;p&gt; and &lt;span&gt; tags?</strong><br><code>&lt;p&gt;</code> is block-level, <code>&lt;span&gt;</code> is inline.</li>
        <li><strong>How do you add an image to an HTML page?</strong><br><code>&lt;img src="image.jpg" alt="Description"&gt;</code></li>
        <li><strong>What is the purpose of the &lt;head&gt; tag?</strong><br>It contains metadata, links, scripts, and title.</li>
        <li><strong>How do you use the &lt;title&gt; tag?</strong><br>Inside &lt;head&gt;, sets the page title.</li>
        <li><strong>What is the difference between &lt;ol&gt; and &lt;ul&gt; tags?</strong><br><code>&lt;ol&gt;</code> creates numbered lists; <code>&lt;ul&gt;</code> creates bullet lists.</li>
        <li><strong>How do you create a table in HTML?</strong><br><code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;Data&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;</code></li>
        <li><strong>What are the different types of input fields in HTML forms?</strong><br>Text, password, email, checkbox, radio, file, submit, etc.</li>
        <li><strong>What are the new features introduced in HTML5?</strong><br>New semantic tags, audio/video, canvas, localStorage, form validation.</li>
        <li><strong>How do you use semantic HTML elements like &lt;header&gt;, &lt;nav&gt;, and &lt;footer&gt;?</strong><br>They define meaningful parts of a page.</li>
        <li><strong>What is the purpose of the &lt;article&gt; and &lt;section&gt; tags?</strong><br><code>&lt;article&gt;</code> is for independent content; <code>&lt;section&gt;</code> is for page grouping.</li>
        <li><strong>How do you use the &lt;canvas&gt; element in HTML5?</strong><br>Used with JS to draw graphics.</li>
        <li><strong>What are the benefits of using semantic HTML?</strong><br>Improves SEO, accessibility, and code readability.</li>
        <li><strong>How do you create a form in HTML?</strong><br><code>&lt;form action="/submit"&gt;&lt;input type="text"&gt;&lt;/form&gt;</code></li>
        <li><strong>What are the different types of form input fields?</strong><br>Text, number, email, password, date, checkbox, radio, file, etc.</li>
        <li><strong>How do you validate form input using HTML5 attributes?</strong><br>Use <code>required</code>, <code>minlength</code>, <code>pattern</code>, etc.</li>
        <li><strong>What is the purpose of the &lt;label&gt; tag?</strong><br>It labels input fields for accessibility.</li>
        <li><strong>How do you handle form submission and data processing?</strong><br>Via HTML <code>action</code>, or JavaScript fetch/submit handlers.</li>
      </ol>
    </section><section>
  <h2>🟢 CSS Questions & Answers</h2>
  <ol start="21">
    <li><strong>What is CSS, and what is its purpose?</strong><br>CSS styles HTML content — color, layout, spacing, etc.</li>
    <li><strong>How do you link a CSS file to an HTML document?</strong><br><code>&lt;link rel="stylesheet" href="style.css"&gt;</code></li>
    <li><strong>What are the different types of CSS selectors?</strong><br>Element, class, ID, attribute selectors.</li>
    <li><strong>How do you use CSS properties and values?</strong><br><code>p { color: red; font-size: 16px; }</code></li>
    <li><strong>What is the box model in CSS?</strong><br>It includes content, padding, border, margin.</li>
    <li><strong>How do you use CSS to style text?</strong><br>Using <code>font-family</code>, <code>color</code>, <code>text-align</code>, etc.</li>
    <li><strong>What are the different types of CSS positioning?</strong><br>Static, relative, absolute, fixed.</li>
    <li><strong>What is the difference between display: none and visibility: hidden?</strong><br><code>display: none</code> removes element; <code>visibility: hidden</code> hides but keeps space.</li>
    <li><strong>How do you use CSS to add borders, margins, and padding?</strong><br><code>border: 1px solid; margin: 10px; padding: 10px;</code></li>
    <li><strong>What are the types of CSS selectors?</strong><br>Element, class, ID, attribute.</li>
    <li><strong>How do you use CSS combinators?</strong><br>Descendant: <code>div p</code>, Child: <code>div > p</code>, Adjacent: <code>h1 + p</code></li>
    <li><strong>How do you use CSS pseudo-classes and pseudo-elements?</strong><br>Examples: <code>:hover</code>, <code>:focus</code>, <code>::before</code>, <code>::after</code></li>
    <li><strong>What is the difference between :hover and :focus?</strong><br><code>:hover</code> is mouse over; <code>:focus</code> is when input is selected.</li>
    <li><strong>What is responsive web design?</strong><br>Design that adapts to different devices/screens.</li>
    <li><strong>How do you use CSS media queries?</strong><br><code>@media (max-width: 600px) { body { font-size: 14px; } }</code></li>
  </ol>
</section>

<section>
  <h2>🟠 JavaScript Questions & Answers</h2>
  <ol start="36">
    <li><strong>What is JavaScript, and what is its purpose?</strong><br>JS makes websites interactive (e.g. clicks, animations).</li>
    <li><strong>How do you declare variables in JavaScript?</strong><br>Using <code>var</code>, <code>let</code>, <code>const</code>.</li>
    <li><strong>What are the different data types in JavaScript?</strong><br>String, number, boolean, object, null, undefined.</li>
    <li><strong>How do you use operators and control structures?</strong><br>Using <code>if</code>, <code>else</code>, <code>switch</code>, <code>for</code>, etc.</li>
    <li><strong>What is the difference between null and undefined?</strong><br><code>null</code> = intentional empty; <code>undefined</code> = unassigned.</li>
    <li><strong>How do you declare and use functions in JavaScript?</strong><br><code>function greet() { alert("Hello"); }</code></li>
    <li><strong>Function declarations vs function expressions?</strong><br>Declaration: <code>function name() {}</code>, Expression: <code>const name = function() {}</code></li>
    <li><strong>What is scope in JavaScript?</strong><br>Scope defines where variables are accessible.</li>
    <li><strong>How do you use closures in JavaScript?</strong><br>A closure remembers variables from its outer function.</li>
    <li><strong>What is the purpose of the this keyword?</strong><br><code>this</code> refers to the current object context.</li>
    <li><strong>What is the DOM, and how do you manipulate it?</strong><br>DOM is the document structure; use JS like <code>getElementById()</code> to change elements.</li>
    <li><strong>How do you handle events in JavaScript?</strong><br>Using <code>addEventListener("click", callback)</code></li>
    <li><strong>What is event delegation?</strong><br>Attaching one handler to parent instead of multiple child elements.</li>
    <li><strong>How do you use JavaScript to interact with HTML forms?</strong><br>Access with <code>document.forms</code> or <code>getElementById()</code>.</li>
    <li><strong>Difference between addEventListener and attachEvent?</strong><br><code>addEventListener</code> is standard; <code>attachEvent</code> is old IE-only method.</li>
  </ol>
</section>

  </main>
  <footer>
    <p>Created by Muzamil ❤️</p>
  </footer>
</body>
</html>
