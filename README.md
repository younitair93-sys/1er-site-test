<!DOCTYPE html>

<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Site Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #444;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
        }
        nav a:hover {
            background-color: #555;
        }
        main {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur mon site</h1>
    </header>

```
<nav>
    <a href="#accueil">Accueil</a>
    <a href="#apropos">À propos</a>
    <a href="#contact">Contact</a>
</nav>

<main>
    <section id="accueil">
        <h2>Accueil</h2>
        <p>Ceci est la page d'accueil de mon site.</p>
        <button onclick="alert('Bienvenue !')">Clique-moi</button>
    </section>

    <section id="apropos">
        <h2>À propos</h2>
        <p>Je crée ce site pour apprendre le HTML, CSS et JavaScript.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Tu peux me contacter par email : exemple@mail.com</p>
    </section>
</main>

<footer>
    &copy; 2025 Mon Site Web
</footer>
```

</body>
</html>
