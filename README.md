<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Be Cool</title>

  <!-- Roboto font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700;900&display=swap" rel="stylesheet">

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
      font-family: 'Roboto', sans-serif;
    }

    .container {
      text-align: center;
    }

    h1 {
      font-size: 64;
      font-weight: 900;
      letter-spacing: 0.04;
      margin: 0;
    }

    .tagline {
      font-size: 0.85;
      font-weight: 300;
      letter-spacing: 0.18;
      opacity: 0.75;
      margin-top: 0.75;
      text-transform: lowercase;
    }

    .tagline + .tagline {
      margin-top: 0.25
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
