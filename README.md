<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VogueUnique - Beauté et Mode</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>VogueUnique</h1>
        <nav>
            <a href="#shop">Boutique</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="shop">
        <h2>Nos Produits</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Produit 1">
                <h3>Produit 1</h3>
                <p>€30.00</p>
                <button onclick="addToCart('Produit 1', 30)">Ajouter au panier</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Produit 2">
                <h3>Produit 2</h3>
                <p>€45.00</p>
                <button onclick="addToCart('Produit 2', 45)">Ajouter au panier</button>
            </div>
            <!-- Ajouter plus de produits ici -->
        </div>
    </section>

    <section id="cart">
        <h2>Panier</h2>
        <ul id="cart-items"></ul>
        <p>Total : €<span id="total-price">0.00</span></p>
    </section>

    <footer>
        <p>© 2024 VogueUnique - Tous droits réservés</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
