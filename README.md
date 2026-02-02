<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>will you be my valentine??</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main class="container" role="main">
    <h1>will you be my valentine??</h1>

    <div class="buttons" role="group" aria-label="Answer choices">
      <button id="yesBtn" class="btn btn-yes">Yes</button>
      <button id="noBtn" class="btn btn-no">No</button>
    </div>

    <div id="message" aria-live="polite" class="message"></div>
  </main>

  <canvas id="fireworks" aria-hidden="true"></canvas>

  <script src="script.js" defer></script>
</body>
</html>
