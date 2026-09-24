# bookish-pancake
Selling of cars and propreties
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Roosevelt Marketplace</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f6f8;
  color: #222;
}

header {
  background: #111827;
  color: white;
  padding: 20px 6%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.hero {
  background: #374151;
  color: white;
  padding: 60px 6%;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
}

.search {
  display: flex;
  max-width: 700px;
  margin-top: 25px;
}

.search input {
  flex: 1;
  padding: 16px;
  border: none;
  font-size: 16px;
}

.search button {
  padding: 16px 25px;
  border: none;
  background: #f59e0b;
  font-weight: bold;
}

section {
  padding: 35px 6%;
}

h2 {
  margin-bottom: 20px;
}

.categories {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
}

.category {
  background: white;
  padding: 25px 10px;
  text-align: center;
  border-radius: 12px;
  box-shadow: 0 2px 8px #0001;
  font-weight: bold;
}

.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 20px;
}

.product {
  background: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 3px 10px #0001;
}

.product-image {
  height: 160px;
  background: #e5e7eb;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 55px;
}

.product-info {
  padding: 18px;
}

.price {
  font-size: 21px;
  font-weight: bold;
}

.button {
  display: inline-block;
  margin-top: 12px;
  padding: 10px 15px;
  background: #111827;
  color: white;
  text-decoration: none;
  border-radius: 7px;
}

footer {
  background: #111827;
  color: white;
  text-align: center;
  padding: 30px;
  margin-top: 30px;
}
</style>
</head>

<body>

<header>
  <div class="logo">ROOSEVELT MARKETPLACE</div>
  <div>🛒</div>
</header>

<div class="hero">
  <h1>Find It. Buy It. Sell It.</h1>
  <p>Shop houses, cars, trucks, jewelry and more.</p>

  <div class="search">
    <input type="text" placeholder="What are you looking for?">
    <button>Search</button>
  </div>
</div>

<section>
  <h2>Browse Categories</h2>

  <div class="categories">
    <div class="category">🏠<br>Houses</div>
    <div class="category">🚗<br>Cars</div>
    <div class="category">🚚<br>Trucks</div>
    <div class="category">💎<br>Jewelry</div>
    <div class="category">📱<br>Electronics</div>
    <div class="category">👗<br>Fashion</div>
    <div class="category">📦<br>More</div>
  </div>
</section>

<section>
  <h2>Featured Listings</h2>

  <div class="products">

    <div class="product">
      <div class="product-image">🏠</div>
      <div class="product-info">
        <h3>Beautiful Family Home</h3>
        <div class="price">Contact for Price</div>
        <a class="button"
           href="mailto:H30006536@gmail.com?subject=House Listing">
           Contact Seller
        </a>
      </div>
    </div>

    <div class="product">
      <div class="product-image">🚗</div>
      <div class="product-info">
        <h3>Quality Car</h3>
        <div class="price">Contact for Price</div>
        <a class="button"
           href="mailto:H30006536@gmail.com?subject=Car Listing">
           Contact Seller
        </a>
      </div>
    </div>

    <div class="product">
      <div class="product-image">🚚</div>
      <div class="product-info">
        <h3>Pickup Truck</h3>
        <div class="price">Contact for Price</div>
        <a class="button"
           href="mailto:H30006536@gmail.com?subject=Truck Listing">
           Contact Seller
        </a>
      </div>
    </div>

    <div class="product">
      <div class="product-image">💎</div>
      <div class="product-info">
        <h3>Fine Jewelry</h3>
        <div class="price">Contact for Price</div>
        <a class="button"
           href="mailto:H30006536@gmail.com?subject=Jewelry Listing">
           Contact Seller
        </a>
      </div>
    </div>

  </div>
</section>

<section style="text-align:center;">
  <h2>Want to Sell Something?</h2>
  <p>List your house, car, truck, jewelry or another item.</p>

  <a class="button"
     href="mailto:H30006536@gmail.com?subject=New Roosevelt Marketplace Listing">
     List an Item
  </a>
</section>

<footer>
  © 2026 Roosevelt Marketplace · Find it. Buy it. Sell it.
</footer>

</body>
</html>
