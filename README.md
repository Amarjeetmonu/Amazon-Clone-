#html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Amazon Clone</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Amazon Clone</h1>
    <input type="text" id="search" placeholder="Search for products..." />
    <button>Cart (<span id="cart-count">0</span>)</button>
  </header>

  <main id="products-container">
    <!-- Products will be injected by JS -->
  </main>

  <script src="script.js"></script>
</body>
</html>
