<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eternal Bloom - Platinum Love Bands</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;700&family=Montserrat:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src=https://i.pinimg.com/564x/83/ce/34/83ce3455f05d8df352e27d0718e4e6f0.jpg alt="Eternal Bloom Logo">
                Eternal Bloom
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#collection">Collection</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="hero-content">
                <h1>Love Blooms Eternal</h1>
                <p>Discover our exquisite collection of platinum love bands</p>
                <a href=https://i.pinimg.com/564x/56/36/b6/5636b6c352144eea749757a54275312c.jpg class="cta-button">Explore Collection</a>
            </div>
        </section>

        <section id="about" class="about">
            <div class="about-content">
                <h2>Our Eternal Promise</h2>
                <p>At Eternal Bloom, we craft timeless symbols of love using the purest platinum. Each ring is a testament to enduring commitment, unparalleled quality, and the eternal beauty of your love story.</p>
                <div class="features">
                    <div class="feature">
                        <i class="fas fa-gem"></i>
                        <h3>Premium Quality</h3>
                        <p>Only the finest platinum</p>
                    </div>
                    <div class="feature">
                        <i class="fas fa-heart"></i>
                        <h3>Lifetime Warranty</h3>
                        <p>Love that lasts forever</p>
                    </div>
                    <div class="feature">
                        <i class="fas fa-award"></i>
                        <h3>Expert Craftsmanship</h3>
                        <p>Artisans with passion</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="collection" class="collection">
            <h2>Our Blooming Collection</h2>
            <div class="ring-gallery">
                <div class="ring-item">
                    <img src=https://i.pinimg.com/564x/f7/5b/47/f75b476186d4c079fa9e37f7573e2651.jpg alt="Classic Elegance Ring">
                    <h3>Classic Elegance</h3>
                    <p>Timeless design for every love story</p>
                </div>
                <div class="ring-item">
                    <img src=https://i.pinimg.com/564x/ce/94/d7/ce94d7629a3d89224598b9c03decbe5f.jpg alt="Modern Romance Ring">
                    <h3>Modern Romance</h3>
                    <p>Contemporary styles for bold couples</p>
                </div>
                <div class="ring-item">
                    <img src=https://i.pinimg.com/736x/bd/3c/52/bd3c526987e8415f0fad4e3c1c1820c9.jpg alt="Vintage Bloom Ring">
                    <h3>Vintage Bloom</h3>
                    <p>Inspired by eternal love tales</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <div class="contact-content">
                <h2>Let Your Love Story Bloom</h2>
                <form>
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content">
            <p>&copy; 2024 Eternal Bloom. All rights reserved.</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-pinterest"></i></a>
            </div>
        </div>
    </footer>
</body>
</html>
///css/////
/* Reset and base styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Montserrat', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #fff;
}

h1, h2, h3 {
    font-family: 'Cormorant Garamond', serif;
}

/* Header and Navigation */
header {
    background-color: rgba(255, 255, 255, 0.9);
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    position: fixed;
    width: 100%;
    z-index: 1000;
    transition: background-color 0.3s ease;
}

header.scrolled {
    background-color: #fff;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 5%;
    max-width: 1200px;
    margin: 0 auto;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: #333;
    display: flex;
    align-items: center;
}

.logo img {
    height: 40px;
    margin-right: 10px;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 2rem;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #d4af37;
}

/* Hero Section */
.hero {
    background-image: url('https://i.pinimg.com/564x/56/36/b6/5636b6c352144eea749757a54275312c.jpg');
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    align-items: center;
    text-align: center;
    color: #fff;
    position: relative;
}

.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0,0,0,0.5);
}

.hero-content {
    position: relative;
    z-index: 1;
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem;
}

.hero h1 {
    font-size: 4rem;
    margin-bottom: 1rem;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-button {
    display: inline-block;
    background-color: #d4af37;
    color: #fff;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 50px;
    font-weight: bold;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.cta-button:hover {
    background-color: #c19b26;
    transform: translateY(-3px);
}

/* About Section */
.about {
    padding: 5rem 10%;
    background-color: #f9f9f9;
}

.about-content {
    max-width: 1000px;
    margin: 0 auto;
    text-align: center;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #333;
}

.about p {
    font-size: 1.1rem;
    margin-bottom: 2rem;
}

.features {
    display: flex;
    justify-content: space-around;
    margin-top: 3rem;
}

.feature {
    flex-basis: 30%;
    padding: 2rem;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

.feature:hover {
    transform: translateY(-10px);
}

.feature i {
    font-size: 3rem;
    color: #d4af37;
    margin-bottom: 1rem;
}

/* Collection Section */
.collection {
    padding: 5rem 10%;
    background-color: #fff;
}

.collection h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
}

.ring-gallery {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.ring-item {
    flex-basis: calc(33.333% - 2rem);
    margin-bottom: 2rem;
    text-align: center;
    background-color: #f9f9f9;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

.ring-item:hover {
    transform: translateY(-10px);
}

.ring-item img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 1rem;
}

.ring-item h3 {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
}

/* Contact Section */
.contact {
    padding: 5rem 10%;
    background-image: url;
    background-size: cover;
    background-position: center;
    position: relative;
}

.contact::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(255,255,255,0.9);
}

.contact-content {
    position: relative;
    max-width: 600px;
    margin: 0 auto;
    text-align: center;
}

.contact h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    color: #333;
}

form {
    display: flex;
    flex-direction: column;
}

input, textarea {
    margin-bottom: 1rem;
    padding: 0.75rem;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: 'Montserrat', sans-serif;
}

button {
    background-color: #d4af37;
    color: #fff;
    padding: 0.75rem;
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease;
    font-weight: bold;
    font-family: 'Montserrat', sans-serif;
}

button:hover {
    background-color: #c19b26;
    transform: translateY(-3px);
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 2rem;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.social-icons a {
    color: #fff;
    font-size: 1.5rem;
    margin: 0 0.5rem;
    transition: color 0.3s ease;
}

.social-icons a:hover {
    color: #d4af37;
}

/* Responsive Design */
@media (max-width: 768px) {
    nav {
        flex-direction: column;
    }

    nav ul {
        margin-top: 1rem;
    }

    nav ul li {
        margin-left: 0;
        margin-right: 1rem;
    }

    .hero h1 {
        font-size: 3rem;
    }

    .features {
        flex-direction: column;
    }

    .feature {
        margin-bottom: 2rem;
    }

    .ring-gallery {
        flex-direction: column;
    }

    .ring-item {
        flex-basis: 100%;
    }

    .footer-content {
        flex-direction: column;
    }

    .social-icons {
        margin-top: 1rem;
    }
}
