# useless-site
useless-site<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Take Me Somewhere Weird</title>
  <style>
    body {
      background-color: #ff69b4;
      color: white;
      font-family: Arial, sans-serif;
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    button {
      background-color: white;
      color: #ff69b4;
      border: none;
      padding: 20px 40px;
      font-size: 24px;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      transition: transform 0.2s ease;
    }

    button:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <h1>Click for a Useless Site 😜</h1>
  <button onclick="goToRandomSite()">Take me!</button>

  <script>
    const sites = [
      "https://www.rrrgggbbb.com/",
      "https://smashthewalls.com/",
      "https://www.partridgegetslucky.com/",
      "https://longdogechallenge.com/",
      "https://heeeeeeeey.com/",
      "https://eelslap.com/",
      "https://corndog.io/",
      "https://cat-bounce.com/",
      "https://alwaysjudgeabookbyitscover.com/",
      "https://thezen.zone/"
    ];

    function goToRandomSite() {
      const index = Math.floor(Math.random() * sites.length);
      window.location.href = sites[index];
    }
  </script>
</body>
</html>
