<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Be Cool</title>
  <style>
    html, body {
      height: 100%;
      margin: 0;
    }
    body {
      background-color: #000;
      color: #FFD400;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: Arial, Helvetica, sans-serif;
    }
    .container {
      text-align: center;
    }
    h1 {
      font-size: clamp(3rem, 10vw, 8rem);
      font-weight: 800;
      letter-spacing: 0.05em;
      margin: 0;
    }
    .tagline {
      font-size: 0.9rem;
      letter-spacing: 0.15em;
      opacity: 0.8;
      margin-top: 0.75rem;
      text-transform: lowercase;
    }
    .tagline + .tagline {
      margin-top: 0.25rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Be Cool</h1>
    <div class="tagline">to yourself</div>
    <div class="tagline">to each other</div>
  </div>
</body>
</html>
