# boooking-online-for-Bussiness-computer-appplication

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Explore Japan - Tour Packages</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f0f2f5;
    }
    header {
      background-color: #d32f2f;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    .container {
      padding: 2rem;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .card {
      background: white;
      border-radius: 10px;
      width: 300px;
      margin: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.02);
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .card-content {
      padding: 1rem;
    }
    .card-content h3, .card-content p {
      margin: 0.5rem 0;
    }
    footer {
      text-align: center;
      background-color: #222;
      color: #ccc;
      padding: 1rem;
      margin-top: 2rem;
    }
    .edit-btn {
      display: inline-block;
      margin-top: 10px;
      padding: 0.3rem 0.6rem;
      background: #1976d2;
      color: white;
      border: none;
      cursor: pointer;
      font-size: 0.8rem;
    }
  </style>
</head>
<body>

<header>
  <h1 contenteditable="true">Explore Japan: Tour Packages</h1>
  <p contenteditable="true">Discover the best cities and experiences in Japan with our curated tours.</p>
</header>

<div class="container">

  <!-- Tokyo -->
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Tokyo_Tower_and_surrounding_buildings.jpg" alt="Tokyo">
    <div class="card-content">
      <h3 contenteditable="true">Tokyo Adventure</h3>
      <p contenteditable="true">5 Days | Modern cityscapes, tech, shopping & food tours.</p>
      <button class="edit-btn" onclick="alert('Redirect to booking page or CMS')">Book Now</button>
    </div>
  </div>

  <!-- Kyoto -->
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Kiyomizu-dera_in_Kyoto%2C_Japan.jpg" alt="Kyoto">
    <div class="card-content">
      <h3 contenteditable="true">Cultural Kyoto</h3>
      <p contenteditable="true">3 Days | Temples, Geisha shows, and traditional cuisine.</p>
      <button class="edit-btn" onclick="alert('Redirect to booking page or CMS')">Book Now</button>
    </div>
  </div>

  <!-- Osaka -->
  <div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/15/Osaka_Castle_Nishinomaru_Garden.jpg" alt="Osaka">
    <div class="card-content">
      <h3 contenteditable="true">Osaka Explorer</h3>
      <p contenteditable="true">4 Days | Nightlife, street food, and castle tours.</p>
      <button class="edit-btn" onclick="alert('Redirect to booking page or CMS')">Book Now</button>
    </div>
  </div>

</div>

<footer>
  <p contenteditable="true">© 2025 Explore Japan Tours. All rights reserved.</p>
</footer>

</body>
</html>
