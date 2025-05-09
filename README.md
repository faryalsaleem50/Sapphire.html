# Sapphire.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cloth Gallery</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }

    /* Navbar */
    nav {
      background-color: #333;
      color: white;
      padding: 15px 20px;
      text-align: center;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav .nav-links {
      display: flex;
      gap: 30px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 16px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Search Bar */
    .search-bar input {
      padding: 8px;
      font-size: 16px;
      border-radius: 5px;
      border: none;
      outline: none;
      margin-left: 20px;
    }

    /* Image Gallery */
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
      padding: 30px;
    }

    .gallery img {
      width: 300px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">Contact</a>
    </div>
    <!-- Search Bar -->
    <div class="search-bar">
      <input type="text" placeholder="Search..." id="searchInput">
    </div>
  </nav>

  <!-- Image Gallery -->
  <div class="gallery">
    <!-- Image 1 -->
    <img src="https://www.w3schools.com/w3images/jeans1.jpg" alt="Cloth 1">
    <!-- Image 2 -->
    <img src="https://www.w3schools.com/w3images/jeans2.jpg" alt="Cloth 2">
    <!-- Image 3 -->
    <img src="https://www.w3schools.com/w3images/jeans3.jpg" alt="Cloth 3">
    <!-- Image 4 -->
    <img src="https://www.w3schools.com/w3images/jeans4.jpg" alt="Cloth 4">
  </div>

</body>
</html>
