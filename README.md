# Website-E-commerce
Website E-commerce
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stroopwafels</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigatiebalk -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#producten">Producten</a></li>
                <li><a href="#over-ons">Over Ons</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Homepagina -->
    <section id="home">
        <h1>Welkom bij [Bedrijfsnaam] Stroopwafels</h1>
        <p>Ontdek onze handgemaakte, verse stroopwafels!</p>
        <a href="#producten" class="cta-button">Bestel Nu</a>
    </section>

    <!-- Productenpagina -->
    <section id="producten">
        <h2>Onze Stroopwafels</h2>
        <div class="product">
            <img src="stroopwafel1.jpg" alt="Stroopwafel">
            <h3>Traditionele Stroopwafel</h3>
            <p>Heerlijke traditionele stroopwafels, perfect bij de koffie.</p>
            <button class="buy-button">Bestel</button>
        </div>
        <div class="product">
            <img src="stroopwafel2.jpg" alt="Chocolade Stroopwafel">
            <h3>Chocolade Stroopwafel</h3>
            <p>Een heerlijke variatie met een laagje chocolade.</p>
            <button class="buy-button">Bestel</button>
        </div>
    </section>

    <!-- Over Ons -->
    <section id="over-ons">
        <h2>Over Ons</h2>
        <p>[Bedrijfsnaam] is een familiebedrijf dat al sinds [jaartal] de lekkerste stroopwafels maakt volgens traditioneel recept.</p>
    </section>

    <!-- Contactpagina -->
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="naam">Naam:</label>
            <input type="text" id="naam" name="naam" required>
            
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="bericht">Bericht:</label>
            <textarea id="bericht" name="bericht" required></textarea>

            <button type="submit">Verstuur</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 [Bedrijfsnaam]. Alle rechten voorbehouden.</p>
    </footer>
</body>
</html>
