<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Skin Care Haven</title>
<style>
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    background: #fafafa;
    color: #333;
}

header {
    background: #ff85a2; /* Soft Pink */
    color: white;
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.container {
    display: flex;
    padding: 20px;
    max-width: 1200px;
    margin: auto;
}

/* PRODUCTS */
.products {
    width: 70%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    border: 1px solid #ffe1e9;
    transition: transform 0.2s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
}

.card h2 { font-size: 40px; margin: 10px 0; }

.card button {
    background: #ff85a2;
    color: white;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
    border-radius: 20px;
    font-weight: bold;
    width: 100%;
}

.card button:disabled {
    background: #ddd;
    cursor: not-allowed;
}

/* CART */
.cart {
    width: 30%;
    margin-left: 20px;
    background: white;
    padding: 20px;
    border-radius: 15px;
    height: fit-content;
    position: sticky;
    top: 20px;
    border: 1px solid #eee;
}

.cart-item {
    border-bottom: 1px solid #f1f1f1;
    padding: 15px 0;
}

button.small {
    padding: 5px 10px;
    margin: 5px 2px;
    border-radius: 5px;
    border: 1px solid #ff85a2;
    background: white;
    color: #ff85a2;
    cursor: pointer;
}

button.small:hover {
    background: #ff85a2;
    color: white;
}

.clear-btn {
    background: #555;
    color: white;
    border: none;
    padding: 10px;
    width: 100%;
    border-radius: 5px;
    margin-top: 10px;
    cursor: pointer;
}
</style>
</head>

<body>

<header>
    <h1>✨ Skin Care Haven</h1>
    <p>Glowing items in basket: <span id="cart-count">0</span></p>
</header>

<div class="container">

    <!-- PRODUCTS -->
    <div class="products" id="product-list"></div>

    <!-- CART -->
    <div class="cart">
        <h2>🛒 Your Routine</h2>
        <div id="cart-items"></div>
        <hr>
        <h3>Total: ₱<span id="total">0</span></h3>
        <button class="clear-btn" onclick="clearCart()">Empty Basket</button>
    </div>

</div>

<script>
// MGA BAGONG PRODUKTO (SKIN CARE)
const products = [
    { id: 1, name: "Hyaluronic Serum", price: 450, emoji: "🧪" },
    { id: 2, name: "Sunscreen SPF50", price: 380, emoji: "☀️" },
    { id: 3, name: "Retinol Cream", price: 520, emoji: "🌙" },
    { id: 4, name: "Facial Cleanser", price: 290, emoji: "🧼" },
    { id: 5, name: "Vitamin C Glow", price: 480, emoji: "🍊" },
    { id: 6, name: "Sheet Mask Set", price: 150, emoji: "🎭" }
];

let cart = [];

function displayProducts() {
    const productList = document.getElementById("product-list");
    productList.innerHTML = "";

    products.forEach(product => {
        const inCart = cart.find(item => item.id === product.id);

        productList.innerHTML += `
            <div class="card">
                <h2>${product.emoji}</h2>
                <h3>${product.name}</h3>
                <p style="color: #ff85a2; font-weight: bold;">₱${product.price}</p>
                <button onclick="addToCart(${product.id})" ${inCart ? "disabled" : ""}>
                    ${inCart ? "Added to Routine" : "Add to Routine"}
                </button>
            </div>
        `;
    });
}

function addToCart(id) {
    const product = products.find(p => p.id === id);
    cart.push({ ...product, qty: 1 });
    updateCart();
}

function updateCart() {
    const cartItems = document.getElementById("cart-items");
    const totalDisplay = document.getElementById("total");
    const countDisplay = document.getElementById("cart-count");

    cartItems.innerHTML = "";

    if (cart.length === 0) {
        cartItems.innerHTML = "<p style='color: #999;'>Your routine is empty...</p>";
    }

    let total = 0;
    let count = 0;

    cart.forEach(item => {
        const subtotal = item.price * item.qty;
        total += subtotal;
        count += item.qty;

        cartItems.innerHTML += `
            <div class="cart-item">
                <strong>${item.name}</strong><br>
                <small>₱${item.price} each</small><br>
                <strong>₱${subtotal}</strong><br>
                <button class="small" onclick="changeQty(${item.id}, -1)">-</button>
                <span>${item.qty}</span>
                <button class="small" onclick="changeQty(${item.id}, 1)">+</button>
                <button class="small" style="color:red; border-color:red;" onclick="removeItem(${item.id})">×</button>
            </div>
        `;
    });

    totalDisplay.textContent = total.toLocaleString();
    countDisplay.textContent = count;

    displayProducts();
}

function changeQty(id, change) {
    const item = cart.find(i => i.id === id);
    item.qty += change;

    if (item.qty <= 0) {
        removeItem(id);
    } else {
        updateCart();
    }
}

function removeItem(id) {
    cart = cart.filter(item => item.id !== id);
    updateCart();
}

function clearCart() {
    if(confirm("Are you sure you want to clear your routine?")) {
        cart = [];
        updateCart();
    }
}

displayProducts();
</script>

</body>
</html>