# Basics-of-web-development
<!DOCTYPE html>
<html>
<head>
  <title>My Basic Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      color: #000;
      padding: 20px;
    }

    h1 {
      color: #3333cc;
    }

    h2 {
      color: #cc3333;
    }

    img {
      width: 300px;
      height: auto;
    }

    a {
      color: blue;
    }

    button {
      padding: 10px 15px;
      background-color: green;
      color: white;
      border: none;
      cursor: pointer;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <!-- 1. Headings, Paragraphs, Images, and Links -->
  <h1>Welcome to My Webpage</h1>
  <p>This is a simple webpage made with HTML. It includes basic content and a clickable button.</p>

  <h2>About</h2>
  <p>This section tells you a bit about the webpage.</p>

  <h2>Sample Image</h2>
  <img src="https://via.placeholder.com/300" alt="Sample Image" />

  <h2>Links</h2>
  <p>Visit <a href="https://www.google.com" target="_blank">Google</a> for more information.</p>

  <!-- 3. Button with Alert -->
  <button onclick="showAlert()">Click Me</button>

  <script>
    function showAlert() {
      alert("Hello! You clicked the button.");
    }
  </script>

</body>
</html>
