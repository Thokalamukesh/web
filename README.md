HTML (index.html)
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Business</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Welcome to Your Business</h1>
            <!-- Your homepage content -->
        </section>

        <section id="about">
            <h2>About Us</h2>
            <!-- Information about your business -->
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <!-- Details about the services you offer -->
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <!-- Contact form or contact information -->
        </section>
    </main>

    <footer>
        <!-- Footer content -->
        <p>&copy; 2023 Your Business</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
CSS (styles.css)
This is a basic example of how you might style your website.

css
Copy code
/* Reset default browser styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

a {
    text-decoration: none;
    color: #fff;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: absolute;
    bottom: 0;
    width: 100%;
}
