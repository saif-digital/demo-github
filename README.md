# demo-github
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Self</title>
  <style>/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(to right, #f0f8ff, #e6f2ff);
  color: #333;
  padding: 20px;
  text-align: center;
}

/* Header style */
header h1 {
  font-size: 2.5rem;
  color: #2c3e50;
  margin-bottom: 20px;
  text-shadow: 1px 1px 2px #ccc;
}

/* Paragraph and main content */
main p {
  font-size: 1.2rem;
  margin: 20px auto;
  line-height: 1.6;
  max-width: 500px;
  background-color: #ffffffcc;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 0 10px #ddd;
}

/* Footer content */
footer {
  margin-top: 40px;
}

footer a {
  display: inline-block;
  margin: 10px;
  color: #0066cc;
  text-decoration: none;
  font-weight: bold;
}

footer a:hover {
  color: #ff6600;
  text-decoration: underline;
  transform: scale(1.05);
  transition: 0.3s;
}

/* Image styles */
img {
  margin: 15px 0;
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Superscript and subscript */
sub, sup {
  font-size: 0.9em;
  color: #555;
}

/* Responsive layout */
@media (max-width: 600px) {
  main p {
    font-size: 1rem;
    padding: 10px;
  }

  header h1 {
    font-size: 2rem;
  }
}
img:hover {
  transform: scale(1.05);
  transition: all 0.3s ease-in-out;
}

</style>
</head>

<body>

  <header>
    <h1>MY SELF</h1>
  </header>

  <main>
    <p>
      Name: SAIF ALI <br>
      Age: 19 <br>
      Height: 176 cm
    </p>
  </main>

  <!-- Uncomment and fix src to show your local image -->
  <!-- <img src="PicsArt_08-18-07.59.23.jpg" width="200" alt="My Photo"> -->

  <footer>
    <br>

    <!-- Instagram Link with Image -->
    <a href="https://www.instagram.com/md.saifsiddiquee?igsh=MTVjMXZ0ZGtoN3Q2eg==" target="_blank">
      <img src="PicsArt_08-18-07.59.23.jpg" alt="Instagram Profile" style="width:300px; height:auto;">
    </a>

    <p>
      H<sub>2</sub>O <br>
      A<sup>2</sup>
    </p>

    <br>
    <a href="https://www.google.com/" target="_blank">Google</a>
    <hr>

    <a href="hello.html"><i>Hello</i></a><br>
    <a href="list.html" target="_blank">List Tags</a>

    <!-- Base64 Google logo as an example -->
    <img src="data:image/png;base64,...(shortened for clarity)..." alt="Google Image" height="100">

    <br>
    <small>This is small text</small><br>
    <big>This is big text</big>

    <hr>

    <!-- Optional second image (base64 too large to include here) -->
    <!-- You can replace this with a smaller base64 or image URL -->
    <!-- <img src="data:image/jpeg;base64,..."> -->

  </footer>

</body>
</html>
