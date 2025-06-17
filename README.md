<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MONO</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>MONO</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">Lookbook</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Minimal. Monochrome. Summer '25</h2>
    <a href="#" class="cta">Shop Now</a>
  </section>

  <section class="features">
    <div class="feature">
      <img src="black-tee.jpg" alt="Black Tee">
      <h3>Black Essentials</h3>
    </div>
    <div class="feature">
      <img src="white-shorts.jpg" alt="White Shorts">
      <h3>White Heat</h3>
    </div>
    <div class="feature">
      <img src="grey-set.jpg" alt="Grey Set">
      <h3>Summer Greys</h3>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 MONO Streetwear</p>
  </footer>

</body>
</html>

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Helvetica Neue', sans-serif;
  background-color: #fff;
  color: #111;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background: #fff;
  border-bottom: 1px solid #ddd;
}

header h1 {
  font-size: 24px;
  letter-spacing: 2px;
}

nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

.hero {
  background: #111;
  color: #fff;
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

.cta {
  display: inline-block;
  padding: 10px 30px;
  background: #fff;
  color: #111;
  text-transform: uppercase;
  text-decoration: none;
  border: 1px solid #fff;
  transition: all 0.3s ease;
}

.cta:hover {
  background: transparent;
  color: #fff;
}

.features {
  display: flex;
  justify-content: space-around;
  padding: 60px 20px;
}

.feature {
  text-align: center;
}

.feature img {
  width: 100%;
  max-width: 300px;
  height: auto;
  margin-bottom: 10px;
}

footer {
  text-align: center;
  padding: 30px;
  background: #f5f5f5;
  font-size: 14px;
}
