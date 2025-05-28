<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hraj hry zadarmo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #007bff, #ff4136, #2ecc40);
      color: white;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    .search-box {
      margin: 1rem auto;
      text-align: center;
    }
    .search-box input {
      padding: 0.5rem;
      width: 50%;
      border: none;
      border-radius: 5px;
    }
    .games-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      padding: 1rem;
    }
    .game {
      background-color: rgba(0, 0, 0, 0.5);
      border-radius: 10px;
      padding: 1rem;
      width: 200px;
      text-align: center;
    }
    .game button {
      margin-top: 0.5rem;
      padding: 0.5rem 1rem;
      background-color: white;
      color: black;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .game button:hover {
      background-color: #ddd;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hraj hry zadarmo</h1>
  </header>

  <div class="search-box">
    <input type="text" placeholder="Hľadaj hru..." oninput="filterGames(this.value)">
  </div>

  <div class="games-container" id="games">
    <div class="game"><h3>Minecraft</h3><button onclick="window.open('https://classic.minecraft.net', '_blank')">Hraj</button></div>
    <div class="game"><h3>Fortnite</h3><button onclick="window.open('https://www.fortnite.com', '_blank')">Hraj</button></div>
    <div class="game"><h3>Roblox</h3><button onclick="window.open('https://www.roblox.com', '_blank')">Hraj</button></div>
    <div class="game"><h3>Krunker</h3><button onclick="window.open('https://krunker.io', '_blank')">Hraj</button></div>
    <div class="game"><h3>Crazy Games</h3><button onclick="window.open('https://www.crazygames.com', '_blank')">Hraj</button></div>
    <div class="game"><h3>Poki</h3><button onclick="window.open('https://poki.com', '_blank')">Hraj</button></div>
  </div>

  <script>
    function filterGames(search) {
      const query = search.toLowerCase();
      const games = document.querySelectorAll('.game');
      games.forEach(game => {
        const title = game.querySelector('h3').textContent.toLowerCase();
        game.style.display = title.includes(query) ? 'block' : 'none';
      });
    }
  </script>
</body>
</html>
