<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>My GitHub Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        text-align: center;
      }
      h1 {
        color: #333;
        margin-top: 50px;
      }
      p {
        margin-top: 20px;
        font-size: 18px;
        color: #555;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to My GitHub Page</h1>
    <p>This is a simple example of a GitHub page.</p>
    
    <script>
      function getRandomColor() {
        var letters = "0123456789ABCDEF";
        var color = "#";
        for (var i = 0; i < 6; i++) {
          color += letters[Math.floor(Math.random() * 16)];
        }
        return color;
      }
      document.body.style.backgroundColor = getRandomColor();
    </script>
  </body>
</html>
