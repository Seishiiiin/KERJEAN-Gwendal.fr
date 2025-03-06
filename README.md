<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }

        nav a {
            color: #fff;
            padding: 15px 25px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #555;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
        }

        section h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #333;
        }

        .bio {
            text-align: center;
        }

        .bio img {
            width: 200px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }

        .project {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .project img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .contact-form {
            max-width: 600px;
            margin: auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-sizing: border-box;
            font-size: 1em;
        }

        .contact-form button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 15px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
            width: 100%;
        }

        .contact-form button:hover {
            background-color: #555;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            font-size: 1em;
        }

    </style>
</head>
<body>

    <header>
        <h1>Bienvenue sur mon Portfolio</h1>
    </header>

    <nav>
        <a href="#bio">À Propos</a>
        <a href="#projects">Projets</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="bio">
        <h2>À Propos de Moi</h2>
        <div class="bio">
            <img src="https://via.placeholder.com/200" alt="Ma photo">
            <p>Je suis un développeur web passionné par la création de sites et d'applications interactives. Mon expertise inclut le HTML, CSS, JavaScript et plus encore. Je suis toujours à la recherche de nouveaux défis et de projets intéressants.</p>
        </div>
    </section>

    <section id="projects">
        <h2>Mes Projets</h2>
        <div class="projects">
            <div class="project">
                <img src="https://via.placeholder.com/300" alt="Projet 1">
                <h3>Projet 1</h3>
                <p>Une description de mon premier projet. Il inclut des technologies comme HTML, CSS, et JavaScript.</p>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300" alt="Projet 2">
                <h3>Projet 2</h3>
                <p>Un autre projet intéressant sur lequel j'ai travaillé, utilisant des frameworks modernes comme React.</p>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300" alt="Projet 3">
                <h3>Projet 3</h3>
                <p>Ce projet implique des API tierces et une interface utilisateur dynamique.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contactez-moi</h2>
        <div class="contact-form">
            <form action="#">
                <input type="text" name="name" placeholder="Votre nom" required>
                <input type="email" name="email" placeholder="Votre email" required>
                <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </div>
    </section>

    <footer>
        <p>© 2025 Mon Portfolio. Tous droits réservés.</p>
    </footer>

</body>
</html>
