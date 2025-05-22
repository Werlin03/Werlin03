<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>W-Resellzzz</nutech>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background-color: #111; color: #fff; }
    header { display: flex; align-items: center; padding: 1rem; background: #000; }
    header img { height: 50px; }
    nav { margin-left: auto; }
    nav a { color: #fff; margin: 0 1rem; text-decoration: none; font-weight: bold; }
    .hero { text-align: center; padding: 4rem 1rem; }
    .hero h1 { font-size: 3rem; margin: 0; }
    .hero p { font-size: 1.2rem; color: #ccc; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px,1fr)); gap: 1rem; padding: 2rem; }
    .card { background: #222; border-radius: 8px; overflow: hidden; }
    .card img { width: 100%; display: block; }
    .card-content { padding: 1rem; }
    .card-content h3 { margin: 0 0 0.5rem; }
    .price { font-size: 1.1rem; font-weight: bold; }
    footer { background: #000; text-align: center; padding: 1rem; font-size: 0.9rem; }
    .bio { padding: 2rem 1rem; text-align: center; }
    .bio p { margin: 0.5rem 0; }
  </style>
</head>
<body>
  <header>
    <!-- Placeholder logo URL -->
    <img src="https://via.placeholder.com/150x50?text=W-Resellzzz" alt="W-Resellzzz logo" />
    <nav>
      <a href="#clothes">Clothes</a>
      <a href="#perfumes">Perfumes</a>
      <a href="#airpods">AirPods</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>W-Resellzzz</h1>
    <p>Fashion | Perfumes | AirPods<br>Shipping available<br>DM for prices & orders</p>
  </section>

  <section id="clothes" class="products">
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Street+T-Shirt" alt="Street T-Shirt" />
      <div class="card-content">
        <h3>Street T-Shirt</h3>
        <p class="price">$25.00</p>
      </div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Denim+Jacket" alt="Denim Jacket" />
      <div class="card-content">
        <h3>Denim Jacket</h3>
        <p class="price">$60.00</p>
      </div>
    </div>
  </section>

  <section id="perfumes" class="products">
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Eau+de+Parfum" alt="Eau de Parfum" />
      <div class="card-content">
        <h3>Signature Scent</h3>
        <p class="price">$45.00</p>
      </div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Cologne" alt="Cologne" />
      <div class="card-content">
        <h3>Premium Cologne</h3>
        <p class="price">$50.00</p>
      </div>
    </div>
  </section>

  <section id="airpods" class="products">
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=AirPods+Pro" alt="AirPods Pro" />
      <div class="card-content">
        <h3>AirPods Pro</h3>
        <p class="price">$199.00</p>
      </div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=AirPods+3" alt="AirPods 3" />
      <div class="card-content">
        <h3>AirPods 3</h3>
        <p class="price">$169.00</p>
      </div>
    </div>
  </section>

  <section id="contact" class="bio">
    <h2>Contact</h2>
    <p>DM for prices & orders</p>
    <p>Fast Shipping Available</p>
    <p>#WResellzzz | #OnlineStore | #FastShipping</p>
  </section>

  <footer>
    &copy; 2025 W-Resellzzz • All Rights Reserved
  </footer>
</body>
</html>
