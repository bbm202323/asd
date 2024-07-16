<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Support Gaza</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Support Gaza</div>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#donate">Donate</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Help Gaza</h1>
        <p>Your support can make a difference.</p>
        <a href="#donate" class="cta-button">Donate Now</a>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>We are committed to providing aid and support to the people of Gaza. Your donations help us supply essential resources and medical aid to those in need.</p>
    </section>

    <section id="donate" class="donate">
        <h2>Make a Donation</h2>
        <p>Select an amount to donate:</p>
        <button onclick="donate(10)">Donate $10</button>
        <button onclick="donate(25)">Donate $25</button>
        <button onclick="donate(50)">Donate $50</button>
        <button onclick="donate(100)">Donate $100</button>
        <p id="donation-message"></p>
    </section>

    <footer>
        <p>&copy; 2024 Support Gaza | Designed with ❤️</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
