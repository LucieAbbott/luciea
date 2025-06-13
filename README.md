<html>
<head>
  <style>
    .container {
      display: flex;
      height: 100vh;
    }
    iframe {
      border: none;
      height: 100%;
    }
    .left {
      width: 25%;
    }
    .right {
      width: 75%;
    }
  </style>
</head>
<body>
  <div class="container">
    <iframe class="left" src="frame_a.html"></iframe>
    <iframe class="right" src="frame_b.html" name="Showframe"></iframe>
  </div>
</body>
</html>
