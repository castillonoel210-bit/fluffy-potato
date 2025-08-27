<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Woadie</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap" rel="stylesheet"> <!-- Modern font -->
    
    <!-- EmailJS SDK -->
    <script type="text/javascript" src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <script type="text/javascript">
        (function(){
            emailjs.init("service_umowb8n"); // Replace with your EmailJS user ID
        })();
    </script>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0; /* Remove default margin */
            background-image: url('https://i.postimg.cc/BbRfFK8w/Picsart-25-08-21-18-26-14-695.jpg'); /* Background image */
            background-size: cover; /* Cover the entire viewport */
            background-position: center; /* Center the image */
            background-repeat: no-repeat; /* Do not repeat the image */
            background-attachment: fixed; /* Keep the background fixed during scrolling */
            min-height: 100vh; /* Ensure the body takes at least the full height of the viewport */
            color: white; /* Default text color */
        }
        header {
            text-align: center;
            margin-bottom: 20px;
            padding: 20px; /* Padding for header */
            border-radius: 5px;
        }
        h1 {
            color: #e2e627;
            font-size: 3em; /* Increased font size */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Shadow for depth */
            margin: 0; /* Remove default margin */
            border: 2px solid black; /* Black border */
            padding: 10px; /* Padding for the text */
            display: inline-block; /* Make the border wrap around the text */
            font-family: 'Montserrat', sans-serif; /* Modern font */
        }
        h2 {
            margin: 20px 0; /* Margin for subheadings */
        }
        .info {
            margin: 20px 0; /* Margin for the info section */
            padding: 15px; /* Padding for the info section */
            background-color: rgba(255, 255, 255, 0.8); /* Background color for info */
            color: #333; /* Text color for info */
            border-radius: 5px; /* Rounded corners */
        }
        .benefit {
            cursor: pointer;
            padding: 10px;
            margin: 10px 0;
            background-color: #e2e627; /* Shape color */
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .benefit:hover {
            background-color: #cc0000; /* Change color on hover */
        }
        .benefit-info {
            display: none; /* Hidden by default */
            padding: 10px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 5px;
            margin-top: 5px;
        }
        .engaging-info {
            margin: 20px 0;
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 5px;
            color: #333; /* Text color for the info section */
        }
        .engaging-info h2 {
            color: #cc0000; /* Header color */
        }
        /* Checkout button styles */
        .checkout-container {
            display: flex;
            justify-content: flex-end; /* Align button to the right */
            margin: 20px;
        }
        button {
            padding: 10px 20px; /* Increased padding for a larger button */
            font-size: 1.2em; /* Increased font size */
            background-color: #28a745; /* Green background for better visibility */
            color: white; /* Text color */
            border: none; /* No border */
            border-radius: 5px; /* Rounded corners */
            cursor: pointer; /* Pointer cursor on hover */
            width: 100%; /* Full width of its container */
            max-width: 200px; /* Optional: set a maximum width */
        }
        button:hover {
            background-color: #218838; /* Darker green on hover */
        }
        .product {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            width: 200px;
            text-align: center;
            background-color: #000000; /* Semi-transparent background for products */
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product h3 {
            margin: 0;
            font-size: 1.2em;
        }
        .original-product {
            color: gold; /* Unique color for Original Smart Honey */
        }
        .green-product {
            color: green; /* Color for other products */
        }
        .video-placeholder {
            width: 100%;
            max-width: 600px; /* Max width for videos */
            margin: 20px auto; /* Center the videos */
            display: block; /* Make it a block element */
            background-color: rgba(255, 255, 255, 0.9); /* Light background */
            border: 2px dashed #e2e627; /* Dashed border for placeholder */
            border-radius: 5px; /* Rounded corners */
            text-align: center; /* Center text */
            padding: 20px; /* Padding for the placeholder */
        }
        .qr-container {
            text-align: center; /* Center the QR container */
            color: yellow; 
            margin: 20px 0; /* Margin above and below QR code */
        }
        .qr-container h2 {
            color: yellow; /* Yellow color for the QR code heading */
            font-weight: bold; /* Bold font style */
            font-family: 'Montserrat', sans-serif; /* Use the modern font */
        }
        .qr-container img {
            width: 200px; /* Set width for QR code */
            height: auto; /* Maintain aspect ratio */
            border: 2px solid #e2e627; /* Border around QR code */
            border-radius: 5px; /* Rounded corners */
        }
        /* Contact form styles */
        .contact-form {
            margin: 25px 0; /* Margin for the contact form */
            padding: 15px; /* Padding for the form */
            background-color: rgb(3, 0, 0); /* Background color for contact form */
            border-radius: 10px; /* Rounded corners */
        }
        .contact-form input {
            width: 100%; /* Full width for input fields */
            padding: 10px; /* Padding for input fields */
            margin: 10px 0; /* Margin for spacing */
            border: 1px solid #ccc; /* Border for input fields */
            color: black; /* Font color */
            border-radius: 5px; /* Rounded corners for input fields */
        }
    </style>
</head>
<body>
    <header>
        <h1>Woadie</h1>        
        <p><a href="http://woadies_honey.com" target="_blank" style="color: white;">Visit our website</a></p>
    </header>
    
    <div class="info">
        <h2>About Woadie</h2>
        <p>Here in Woadie, if you or a loved one are seeking insights and guidance on the path to recovery from concussions or navigating mental health challenges, you've come to the right place. I provide information and support tailored to help individuals at all stages of life. By serving food and engaging in community jogs, I empower people to help themselves while making a difference for those in need.</p>
    </div>

    <!-- Video Placeholders moved here -->
    <div class="video-placeholder">
        <p>Video Placeholder 1</p>
        <img src="https://via.placeholder.com/560x315?text=Video+1" alt="Video Placeholder 1">
    </div>
    <div class="video-placeholder">
        <p>Video Placeholder 2</p>
        <img src="https://via.placeholder.com/560x315?text=Video+2" alt="Video Placeholder 2">
    </div>

    <!-- Engaging Information Section -->
    <div class="engaging-info">
        <h2>Why Choose Woadie Honey?</h2>
        <p>At Woadie, we believe in the power of nature. Our honey is not just a sweet treat; it’s a commitment to your well-being. Here’s why our honey stands out:</p>
        <ul>
            <li><strong>Pure & Natural:</strong> Sourced directly from the finest hives, ensuring that you get the purest form of honey without additives.</li>
            <li><strong>Health Benefits:</strong> Packed with antioxidants, vitamins, and minerals that promote overall health and wellness.</li>
            <li><strong>Supports Local Beekeepers:</strong> By choosing Woadie, you’re supporting sustainable beekeeping practices and local communities.</li>
            <li><strong>Versatile Usage:</strong> Enjoy it in your tea, on toast, or as a natural sweetener in your recipes!</li>
            <li><strong>Satisfaction Guaranteed:</strong> We stand by our products and are committed to your satisfaction. If you’re not happy, we’ll make it right!</li>
        </ul>
        <p>Join the Woadie family today and experience the sweet taste of health and wellness!</p>
    </div>

    <div class="info">
        <h2>Benefits of Woadie Honey</h2>
        <div class="benefit" onclick="toggleInfo('benefit1')">Exceeds Normal Brain Function</div>
        <div class="benefit-info" id="benefit1">Rewires and revives sophisticated processes in the brain that otherwise would not be able to activate.</div>
        
        <div class="benefit" onclick="toggleInfo('benefit2')">Stimulates Head Muscles</div>
        <div class="benefit-info" id="benefit2">Supports chewing and swallowing, helping to relive dead or dormant cells in the brain stem.</div>
        
        <div class="benefit" onclick="toggleInfo('benefit3')">Enhances Coordination</div>
        <div class="benefit-info" id="benefit3">Activates the cerebellum, linked to the coordination of movement, posture, and regulation of cardiac and respiratory centers.</div>
        
        <div class="benefit" onclick="toggleInfo('benefit4')">Natural Energy Boost</div>
        <div class="benefit-info" id="benefit4">Perfect for maintaining energy levels throughout the day.</div>
        
        <div class="benefit" onclick="toggleInfo('benefit5')">Rich in Antioxidants</div>
        <div class="benefit-info" id="benefit5">Helps combat oxidative stress and supports overall health.</div>
        
        <div class="benefit" onclick="toggleInfo('benefit6')">Supports Immune Function</div>
        <div class="benefit-info" id="benefit6">Aids in strengthening the immune system.</div>
        
        <div class="benefit" onclick="toggleInfo('benefit7')">Promotes Digestive Health</div>
        <div class="benefit-info" id="benefit7">Can assist in digestion and gut health.</div>
    </div>

    <!-- QR Code Section -->
    <div class="qr-container">
        <h2>Support Us on Cash App</h2>
        <p>Scan the QR code below to send us support via Cash App:</p>
        <img src="https://api.qrserver.com/v1/create-qr-code/?data=https://cash.app/$YourCashAppID&size=200x200" alt="Cash App QR Code">
    </div>

    <!-- Contact Information Form -->
    <div class="contact-form">
        <h2>Contact Information</h2>
        <p>Please enter your email and phone number to receive notifications:</p>
        <input type="email" id="userEmail" name="user_email" placeholder="Your Email" required>
        <input type="tel" id="userPhone" name="user_phone" placeholder="Your Phone Number" required>
        <p>📲 You can reach us via email or phone number provided above.</p>
        <button onclick="submitContactInfo()">Submit</button>
    </div>

    <main>
        <div id="product-list"></div>
        <div class="checkout-container">
            <button onclick="checkout()">Checkout</button>
        </div>
        <h2>Shopping Cart</h2>
        <div id="cart"></div>
    </main>
    <script>
        const products = [
            { id: 1, name: "Original Smart Honey", price: 50, priceId: 'price_1', className: 'original-product' },
            { id: 2, name: "Potent Smart Honey", price: 80, priceId: 'price_2', className: 'green-product' },
            { id: 3, name: "Golden Honey", price: 200, priceId: 'price_3', className: 'green-product' }
        ];

        let cart = [];

        function displayProducts() {
            const productList = document.getElementById('product-list');
            products.forEach(product => {
                const productDiv = document.createElement('div');
                productDiv.className = 'product';
                productDiv.innerHTML = `
                    <h3 class="${product.className}">${product.name}</h3>
                    <p>Price: $${product.price}</p>
                    <button onclick="addToCart(${product.id})">Add to Cart</button>
                `;
                productList.appendChild(productDiv);
            });
        }

        function addToCart(productId) {
            const product = products.find(p => p.id === productId);
            cart.push(product);
            displayCart();
        }

        function removeFromCart(productId) {
            cart = cart.filter(item => item.id !== productId); // Remove item from cart
            displayCart(); // Update cart display
        }

        function displayCart() {
            const cartContainer = document.getElementById('cart');
            cartContainer.innerHTML = '';
            cart.forEach(item => {
                const cartItem = document.createElement('div');
                cartItem.className = 'cart-item';
                cartItem.innerHTML = `${item.name} - $${item.price} <button onclick="removeFromCart(${item.id})">Remove</button>`;
                cartContainer.appendChild(cartItem);
            });
        }

        function checkout() {
            if (cart.length === 0) {
                alert('Your cart is empty. Please add items to your cart before checking out.');
                return;
            }

            const totalAmount = cart.reduce((total, item) => total + item.price, 0);
            const cartItems = cart.map(item => `${item.name} - $${item.price}`).join('\n');

            const confirmationMessage = `
                You are about to checkout with the following items:
                ${cartItems}
                
                Total Amount: $${totalAmount}
                
                Proceed to payment?
            `;

            const proceed = confirm(confirmationMessage);
            if (proceed) {
                alert('Thank you for your purchase!');
                cart = []; // Clear the cart after checkout
                displayCart(); // Update the cart display
            }
        }

        function toggleInfo(benefitId) {
            const info = document.getElementById(benefitId);
            info.style.display = info.style.display === 'none' || info.style.display === '' ? 'block' : 'none';
        }

        function submitContactInfo() {
            const email = document.getElementById('userEmail').value;
            const phone = document.getElementById('userPhone').value;

            const templateParams = {
                user_email: email,
                user_phone: phone
            };

            emailjs.send('service_umowb8n', 'template_72qnjzg', templateParams)
                .then(function(response) {
                    alert('Notification sent successfully!');
                    // Clear the input fields
                    document.getElementById('userEmail').value = '';
                    document.getElementById('userPhone').value = '';
                }, function(error) {
                    alert('Failed to send notification, please try again.');
                    console.error('FAILED...', error);
                });
        }

        displayProducts(); // Call the function to display products
    </script>
</body>
</html>