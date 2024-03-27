<!DOCTYPE html>
<html>
<head>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
  min-height: 100vh;
  position: relative; 
}


header {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

main {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  padding: 50px 0;
}

.product-info {
  flex: 1;
  max-width: 400px;
  text-align: center;
  padding: 20px;
}

.product-info h2 {
  color: #333;
}

.product-info p {
  color: #666;
  margin-bottom: 20px;
}

.product-info button {
  background-color: #333;
  color: #fff;
  border: none;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.product-info button:hover {
  background-color: #555;
}

.product-image {
  flex: 1;
  max-width: 400px;
}

.product-image img {
  max-width: 100%;
  height: auto;
  display: block;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
  width: 100%; 
  position: fixed; 
  bottom: 0; 
}
</style>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Product Unveiling</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Unveiling the Future: The All-New Audi </h1>
    <p>Experience Innovation</p>
  </header>
  <main>
    <section class="product-info">
      <h2>Introducing Our Latest Innovation</h2>
      <p>Be the first to explore our groundbreaking new product.<br>Get ready to witness automotive innovation like never before as Audi proudly introduces its latest masterpiece - the all-new Audi</p>
      <button>Learn More</button>
    </section>
    <section class="product-image">
      <img src="C:\Users\DEVENDER\Downloads\Audi-TT-RS-2018-main.jpg" alt="Product Image">
    </section>
  </main>
  <footer>
    <p>&copy; 2024 Product Unveiling. All rights reserved.</p>
  </footer>
</body>
</html>
