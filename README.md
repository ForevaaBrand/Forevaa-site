<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Forevaa Clothing</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #0d0d0d;
      color: #ffffff;
    }

    header {
      background-color: #111;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #fcd200;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #fcd200;
      letter-spacing: 2px;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1512436991641-6745cdb1723f') center/cover no-repeat;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      position: relative;
    }

    .hero::after {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0,0,0,0.6);
    }

    .hero h2 {
      z-index: 1;
      font-size: 2.8em;
      color: #fcd200;
      text-transform: uppercase;
      letter-spacing: 4px;
    }

    .section {
      padding: 50px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .section h3 {
      color: #fcd200;
      text-align: center;
      margin-bottom: 40px;
      font-size: 2em;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .product {
      background-color: #1a1a1a;
      padding: 20px;
      border: 1px solid #333;
      border-radius: 8px;
      text-align: center;
      transition: 0.3s;
    }

    .product:hover {
      border-color: #fcd200;
    }

    .product img {
      width: 100%;
      border-radius: 4px;
      height: 300px;
      object-fit: cover;
    }

    .product h4 {
      margin: 15px 0 5px;
      color: #fff;
    }

    .product p {
      color: #ccc;
    }

    .product button {
      margin-top: 10px;
      background-color: #fcd200;
      color: #000;
      border: none;
      padding: 10px 20px;
      font-weight: bold;
      cursor: pointer;
      border-radius: 4px;
    }

    .about {
      text-align: center;
      color: #ddd;
      max-width: 800px;
      margin: auto;
    }

    footer {
      background-color: #111;
      color: #888;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
      border-top: 1px solid #333;
    }

    a {
      color: #fcd200;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>Forevaa</h1>
  </header>

  <div class="hero">
    <h2>Born Different. Built Forevaa.</h2>
  </div>

  <section class="section">
    <h3>Shop the Drop</h3>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1520975918311-973c3c38c120" alt="Product 1" />
        <h4>Black Sheep Hoodie</h4>
        <p>$60.00</p>
        <button>Add to Cart</button>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1603575448678-b6f984cfdbc8" alt="Product 2" />
        <h4>Street Rebel Tee</h4>
        <p>$35.00</p>
        <button>Add to Cart</button>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1593032465171-d95d3fdfb3d1" alt="Product 3" />
        <h4>Built Forevaa Jacket</h4>
        <p>$90.00</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </section>

  <section class="section about">
    <h3>About Forevaa</h3>
    <p>Forevaa is for the ones who never fit in — the black sheep, the born rebels, the ones who build their own legacy. We don’t follow trends, we create our own wave. Every piece is a statement. Every stitch is built Forevaa.</p>
  </section>

  <footer>
    &copy; 2025 Forevaa. All rights reserved. | <a href="#">Instagram</a> | <a href="#">Contact</a>
  </footer>

</body>
</html>
