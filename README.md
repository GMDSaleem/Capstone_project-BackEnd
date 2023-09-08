# Capstone_project-BackEnd
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- ... (Rest of the head content) -->
</head>
<body>
    <h1 class="main-heading">Metered Calculator</h1>
    <div class="container">
        <div class="calculator">
            <!-- ... (Existing calculator content) -->

            <div class="calculator-results">
                <div class="calculator-result-box">
                    <p class="result-label">Points:</p>
                    <p id="resultPoints" class="result-value"></p>
                </div>
                <div class="calculator-result-box">
                    <p class="result-label">Cost:</p>
                    <p id="resultCost" class="result-value"></p>
                </div>
            </div>

            <div class="note-points">
                <!-- Note points here -->
            </div>
        </div>
        
        <div class="cart">
            <h2>Your Cart</h2>
            <div id="cartList" class="cart-list">
                <!-- Cart items here -->
            </div>
            <div class="cart-total-box">
                <p class="cart-total-label">Total Cost:</p>
                <p id="cartTotal" class="cart-total-value"></p>
            </div>
            <div class="discount-input">
                <!-- Discount input and buttons here -->
            </div>
            <div class="note-points">
                <!-- Note points here -->
            </div>
        </div>
    </div>

    <button id="resetPageBtn" class="button">Reset Page</button>

    <script src="script.js"></script>
</body>
</html>
