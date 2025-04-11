<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Сайт Флоры 🌸</title>
  <link rel="stylesheet" href="Flora.css">
</head>
<body>

  <!-- Меню навигации -->
  <nav>
    <ul>
      <li><a href="#audio" class="nav-link">Аудио</a></li>
      <li><a href="#video" class="nav-link">Видео</a></li>
      <li><a href="#map" class="nav-link">Карта</a></li>
      <li><a href="#animation" class="nav-link">Анимация</a></li>
    </ul>
  </nav>

  <!-- Раздел Аудио -->
  <div id="audio" class="section">
    <h2>Аудио</h2>
    <audio controls>
      <source src="assets/audio/music.mp3" type="audio/mpeg">
    </audio>
  </div>

  <!-- Раздел Видео -->
  <div id="video" class="section">
    <h2>Видео</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/R9JnBjoCy7c?si=6U092zCr29C7siO5"
      title="YouTube video player" frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
    </iframe>
    <p style="margin-top: 10px; font-style: italic;">Сделано Флорой</p>
  </div>

  <!-- Раздел Карта -->
  <div id="map" class="section">
    <h2>Карта</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3023.248348603787!2d-74.00601548459223!3d40.71277577933156!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c25a3159b028f7%3A0x8e960cd1b325b83e!2sNew%20York%20City%2C%20NY!5e0!3m2!1sen!2sus!4v1629880748942!5m2!1sen!2sus"
      width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy">
    </iframe>
  </div>

  <!-- Раздел Анимация -->
  <div id="animation" class="section">
    <h2>Анимация</h2>
    <p class="animate">Пример текста с анимацией.</p>
  </div>

  <script src="script.js"></script>
</body>
</html>
