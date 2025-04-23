<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>All HTML Tags Example</title>
  <style>
    body { font-family: Arial; background-color: #f2f2f2; padding: 20px; }
    table, th, td { border: 1px solid black; border-collapse: collapse; padding: 5px; }
    nav, section, article, aside, footer { margin-top: 20px; padding: 10px; background: #fff; }
  </style>
</head>
<body>

  <!-- Headings -->
  <h1>Main Heading (h1)</h1>
  <h2>Subheading (h2)</h2>
  <h3>Section Heading (h3)</h3>
  <h4>Subsection (h4)</h4>
  <h5>Smaller Heading (h5)</h5>
  <h6>Smallest Heading (h6)</h6>

  <!-- Paragraph and text formatting -->
  <p>This is a <b>bold</b>, <strong>strong</strong>, <i>italic</i>, <em>emphasized</em> text.</p>
  <p><mark>Highlighted</mark>, <u>underlined</u>, <small>small</small>, <del>deleted</del>, and <ins>inserted</ins> text.</p>
  <p>Superscript: x<sup>2</sup>, Subscript: H<sub>2</sub>O</p>

  <!-- Hyperlink -->
  <a href="https://www.google.com" target="_blank">Visit Google</a>

  <!-- Image -->
  <p><img src="https://via.placeholder.com/150" alt="Placeholder Image"></p>

  <!-- List -->
  <ul>
    <li>Unordered Item 1</li>
    <li>Unordered Item 2</li>
  </ul>
  <ol>
    <li>Ordered Item 1</li>
    <li>Ordered Item 2</li>
  </ol>
  <dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
  </dl>

  <!-- Table -->
  <table>
    <tr><th>Name</th><th>Age</th></tr>
    <tr><td>Vinay</td><td>23</td></tr>
    <tr><td>John</td><td>25</td></tr>
  </table>

  <!-- Form -->
  <form action="#" method="POST">
    <label>Name: <input type="text" name="name"></label><br><br>
    <label>Email: <input type="email" name="email"></label><br><br>
    <label>Password: <input type="password" name="password"></label><br><br>
    <label>Gender:</label>
    <input type="radio" name="gender" value="male"> Male
    <input type="radio" name="gender" value="female"> Female <br><br>
    <label>Hobbies:</label>
    <input type="checkbox" name="hobby" value="reading"> Reading
    <input type="checkbox" name="hobby" value="sports"> Sports <br><br>
    <label>City:
      <select name="city">
        <option>Bangalore</option>
        <option>Chennai</option>
      </select>
    </label><br><br>
    <textarea name="message" rows="4" cols="30">Enter message...</textarea><br><br>
    <input type="submit" value="Submit">
  </form>

  <!-- Multimedia -->
  <video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <!-- Semantic Elements -->
  <nav>Navigation Bar</nav>
  <section>
    <article>
      <h2>Article Title</h2>
      <p>This is an article section.</p>
    </article>
  </section>
  <aside>Sidebar or note</aside>
  <footer>Footer info here</footer>

  <!-- Other tags -->
  <hr>
  <br>
  <code>console.log("Hello World");</code>
  <pre>
    This is preformatted
    Text in block
  </pre>
  <blockquote cite="https://example.com">
    This is a blockquote from another source.
  </blockquote>
  <!-- This is a comment -->

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Complete HTML & CSS Demo</title>
  <style>
    /* Internal CSS */
    body {
      background-color: #f4f4f4;
      font-family: Arial, sans-serif;
      margin: 20px;
      padding: 20px;
      color: #333;
    }

    h1, h2, h3 {
      color: #007acc;
    }

    a {
      color: green;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    table, th, td {
      border: 1px solid black;
      border-collapse: collapse;
      padding: 8px;
    }

    table {
      width: 100%;
      background-color: #fff;
    }

    form {
      background: #fff;
      padding: 15px;
      border: 1px solid #ccc;
      margin-top: 20px;
    }

    nav, section, article, aside, footer {
      background: #e9e9e9;
      margin: 10px 0;
      padding: 10px;
      border-radius: 8px;
    }

    img {
      width: 150px;
      height: auto;
      border-radius: 8px;
    }

    .highlight {
      color: red;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>All-in-One HTML + CSS Example</h1>
  <h2 class="highlight">Subheading Styled with Class</h2>
  <h3 style="color: purple;">Inline Styled Heading</h3>

  <p>This is a <b>bold</b>, <i>italic</i>, <u>underlined</u>, <mark>highlighted</mark> paragraph.</p>
  <p>Text with <sup>superscript</sup> and <sub>subscript</sub>.</p>

  <!-- Links and Images -->
  <a href="https://www.w3schools.com" target="_blank">Visit W3Schools</a>
  <br><br>
  <img src="https://via.placeholder.com/150" alt="Sample Image">

  <!-- Lists -->
  <ul>
    <li>Unordered item</li>
    <li>Another item</li>
  </ul>

  <ol>
    <li>Ordered item 1</li>
    <li>Ordered item 2</li>
  </ol>

  <!-- Table -->
  <table>
    <caption>User Info</caption>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
    <tr>
      <td>Vinay</td>
      <td>23</td>
    </tr>
    <tr>
      <td>Alice</td>
      <td>25</td>
    </tr>
  </table>

  <!-- Form -->
  <form>
    <label>Name: <input type="text" name="name"></label><br><br>
    <label>Email: <input type="email"></label><br><br>
    <label>Gender:
      <input type="radio" name="gender"> Male
      <input type="radio" name="gender"> Female
    </label><br><br>
    <label>Hobbies:
      <input type="checkbox"> Reading
      <input type="checkbox"> Coding
    </label><br><br>
    <label>Country:
      <select>
        <option>India</option>
        <option>USA</option>
      </select>
    </label><br><br>
    <textarea rows="4" cols="30">Write something...</textarea><br><br>
    <input type="submit" value="Submit">
  </form>

  <!-- Semantic Elements -->
  <nav>Navigation Bar</nav>
  <section>
    <article>
      <h2>Article Title</h2>
      <p>This is an article inside a section.</p>
    </article>
  </section>
  <aside>Sidebar or extra content</aside>
  <footer>Footer content &copy; 2025</footer>

  <!-- Multimedia -->
  <video width="320" controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <br><br>
  <audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <!-- Code block and blockquote -->
  <pre>
function helloWorld() {
  console.log("Hello, World!");
}
  </pre>

  <blockquote cite="https://example.com">
    This is a quoted statement from a source.
  </blockquote>

  <hr>
  <!-- Comment: This is an HTML comment -->

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>All-in-One HTML + CSS + JS</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      padding: 20px;
    }
    h1 {
      color: #0077cc;
    }
    .highlight {
      color: red;
      font-weight: bold;
    }
    button {
      background-color: #28a745;
      color: white;
      padding: 8px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    input, select, textarea {
      margin: 5px 0;
      padding: 5px;
    }
  </style>
</head>
<body>

  <h1>HTML + CSS + JavaScript Full Demo</h1>
  <p>This is a <span class="highlight">highlighted</span> paragraph.</p>

  <h2>Image and Link</h2>
  <a href="https://www.google.com" target="_blank">Visit Google</a><br><br>
  <img src="https://via.placeholder.com/150" alt="Sample Image"><br><br>

  <h2>Form and JavaScript Interactivity</h2>
  <form id="userForm">
    Name: <input type="text" id="nameInput"><br>
    Age: <input type="number" id="ageInput"><br>
    <button type="button" onclick="displayInfo()">Submit</button>
  </form>

  <h3>Output:</h3>
  <p id="outputText">Your info will appear here.</p>

  <h2>Click to Change Color</h2>
  <button onclick="changeColor()">Change Background</button>

  <h2>List and Table</h2>
  <ul>
    <li>Item One</li>
    <li>Item Two</li>
  </ul>

  <table border="1">
    <tr><th>Name</th><th>Age</th></tr>
    <tr><td>Vinay</td><td>23</td></tr>
  </table>

  <h2>JS-powered Counter</h2>
  <p id="counter">0</p>
  <button onclick="increaseCounter()">+1</button>
  <button onclick="resetCounter()">Reset</button>

  <script>
    // JS Function for Form Output
    function displayInfo() {
      let name = document.getElementById("nameInput").value;
      let age = document.getElementById("ageInput").value;
      document.getElementById("outputText").innerText = `Hello, ${name}. You are ${age} years old.`;
    }

    // JS Function to Change Background
    function changeColor() {
      document.body.style.backgroundColor = "#e0ffe0";
    }

    // Counter Logic
    let count = 0;
    function increaseCounter() {
      count++;
      document.getElementById("counter").innerText = count;
    }
    function resetCounter() {
      count = 0;
      document.getElementById("counter").innerText = count;
    }
  </script>

</body>
</html>
