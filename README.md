# game-help// Een eenvoudige functie die kan worden toegevoegd voor interactie
document.addEventListener('DOMContentLoaded', function() {
    alert("Welkom op de Game Promoties website!");
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Promoties</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welkom op de Game Promoties Website!</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Aanbiedingen</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <h2>Nieuwste Game Aanbiedingen</h2>
        <p>Bekijk de nieuwste promoties voor games die je kunt kopen!</p>
    </section>

    <footer>
        <p>&copy; 2025 Game Promoties. Alle rechten voorbehouden.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<section>
    <h2>Nieuwste Game Aanbiedingen</h2>
    <p>Bekijk de nieuwste promoties voor games die je kunt kopen!</p>
</section>

<footer>
    <p>&copy; 2025 Game Promoties. Alle rechten voorbehouden.</p>
</footer>

<script src="script.js"></script>
/* Algemene styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: absolute;
    width: 100%;
    bottom: 0;
}

