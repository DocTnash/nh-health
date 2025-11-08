# nh-health
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>New Horizons Health Platform</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>New Horizons Health</h1>
    <p>Empowering frontline care across Zimbabwe and beyond</p>
    <nav>
      <button onclick="toggleLanguage()">🌍 Language</button>
      <button onclick="simulateLogin()">🔐 Login</button>
      <button onclick="simulateOffline()">📱 Offline Mode</button>
    </nav>
  </header>

  <main class="container">
    <input type="text" id="searchInput" placeholder="Search 100+ health topics..." />
    <div id="cardGrid" class="card-grid"></div>
  </main>

  <footer>
    &copy; 2025 New Horizons Health. Built for impact, powered by knowledge.
  </footer>

  <script src="topics.js"></script>
  <script src="app.js"></script>
</body>
</html>