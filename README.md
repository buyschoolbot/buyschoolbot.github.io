<Doctype HTML>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schoolbot</title>
    <script>
        // This will show the message when the page loads
        window.onload = function() {
            alert("Are you ready to buy the schoolbot click ok to continue???");
        };
    </script>
</head>
<body>
    <h1>Welcome to the Schoolbot Page!</h1>
    <p>Let us know if you're interested in buying the schoolbot We will get to you quickly ASAP.</p>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buy Button</title>
    <style>
        .buy-button {
            background-color: green;
            color: white;
            font-size: 16px;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        .buy-button:hover {
            background-color: darkgreen;
        }
    </style>
</head>
<body>

    <button class="buy-button" onclick="redirectToPage()">Buy</button>

    <script>
        function redirectToPage() {
            window.location.href = "https://cdn.prod.website-files.com/605826c62e8de87de744596e/66b32d74582ffd86a10745e7_65f00977f2b5330cc634090c_1-65f007c88e75b.webp";
        }
    </script>

</body>
</html>


    <button class="buy
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coupon Code Validation</title>
    <style>
        .valid {
            color: green;
        }
        .invalid {
            color: red;
        }
    </style>
</head>
<body>

    <h1>Coupon Code</h1>
    <p>Enter coupon code:</p>

    <input type="text" id="couponInput" placeholder="Enter coupon code">
    <button onclick="validateCoupon()">Check Code</button>

    <p id="result"></p>

    <script>
        function validateCoupon() {
            var coupon = document.getElementById("couponInput").value;
            var resultText = document.getElementById("result");

            if (coupon === "Ilikeschoolbot") {
                resultText.textContent = "30% Coupon Applied";
                resultText.className = "valid";
            } else {
                resultText.textContent = "Invalid code.";
                resultText.className = "invalid";
            }
        }
    </script>

</body>
</html>
