<!DOCTYPE html>
<html lang="en">
<head>
  <title>Slot Machine</title>
  <meta charset="utf-8" />
  <meta name="theme-color" content="#000000" />
  <meta name="viewport" content="width=480,initial-scale=1, maximum-scale=1" />
  <link rel="icon" href="https://n1md7.github.io/slot-game/img/img/Cherry.png" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Black+Ops+One&family=Permanent+Marker&family=Roboto:ital,wght@1,300&display=swap" />
</head>
<body>
  <div>
    <a class="github-button" href="https://github.com/n1md7" data-color-scheme="no-preference: dark; light: dark; dark: dark;" data-size="large" data-show-count="true" aria-label="Follow @n1md7 on GitHub">Follow @n1md7</a>
    <a class="github-button" href="https://github.com/n1md7/slot-game" data-color-scheme="no-preference: dark; light: dark; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star n1md7/slot-game on GitHub">Star</a>
    <a class="github-button" href="https://github.com/n1md7/slot-game/fork" data-color-scheme="no-preference: dark; light: dark; dark: dark;" data-icon="octicon-repo-forked" data-size="large" data-show-count="true" aria-label="Fork n1md7/slot-game on GitHub">Fork</a>
  </div>
  <div class="game-container">
    <!-- Winner Display -->
    <div class="winner-display mb-3">
      <span>WIN: <span id="win-amount">$</span></span>
    </div>

    <!-- Canvas Placeholder -->
    <canvas id="slot" width="440" height="240"></canvas>
