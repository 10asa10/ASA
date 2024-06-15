<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Publications Scientifiques - [Votre Nom]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: auto;
        }
        .bio, .publications, .projects, .contact {
            margin-bottom: 40px;
        }
        .publication-item, .project-item {
            background-color: white;
            padding: 15px;
            margin: 10px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
        }
        form button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Publications Scientifiques - [Votre Nom]</h1>
</header>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#biographie">Biographie</a>
    <a href="#publications">Publications</a>
    <a href="#projets">Projets</a>
    <a href="#contact">Contact</a>
</nav>

<section id="accueil" class="container">
    <h2>Bienvenue</h2>
    <p>Bienvenue sur ma page web personnelle dédiée à mes publications et projets scientifiques. Vous trouverez ici des informations sur mon parcours, mes travaux de recherche, ainsi que des moyens de me contacter.</p>
</section>

<section id="biographie" class="container bio">
    <h2>Biographie</h2>
    <p>[Insérez votre biographie ici. Parlez de votre parcours académique, de vos domaines de recherche, de vos accomplissements et de tout autre aspect pertinent de votre carrière scientifique.]</p>
</section>

<section id="publications" class="container publications">
    <h2>Publications</h2>
    <div class="publication-item">
        <h3>Titre de la Publication 1</h3>
        <p><strong>Auteurs :</strong> Auteur 1, Auteur 2, Auteur 3</p>
        <p><strong>Journal :</strong> Nom du Journal, Année</p>
        <p><a href="lien_de_publication_1">Lien vers la publication</a></p>
    </div>
    <div class="publication-item">
        <h3>Titre de la Publication 2</h3>
        <p><strong>Auteurs :</strong> Auteur 1, Auteur 2, Auteur 3</p>
        <p><strong>Journal :</strong> Nom du Journal, Année</p>
        <p><a href="lien_de_publication_2">Lien vers la publication</a></p>
    </div>
    <!-- Ajoutez d'autres publications de la même manière -->
</section>

<section id="projets" class="container projects">
    <h2>Projets</h2>
    <div class="project-item">
        <h3>Nom du Projet 1</h3>
        <p>Description du projet 1. Expliquez brièvement les objectifs, les méthodes et les résultats obtenus.</p>
    </div>
    <div class="project-item">
        <h3>Nom du Projet 2</h3>
        <p>Description du projet 2. Expliquez brièvement les objectifs, les méthodes et les résultats obtenus.</p>
    </div>
    <!-- Ajoutez d'autres projets de la même manière -->
</section>

<section id="contact" class="container contact">
    <h2>Contact</h2>
    <form action="mailto:votremail@example.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Votre nom" required>
        <input type="email" name="email" placeholder="Votre email" required>
        <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
        <button type="submit">Envoyer</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 [Votre Nom]. Tous droits réservés.</p>
    <p>Suivez-moi sur <a href="https://www.linkedin.com" style="color: white;">LinkedIn</a>, <a href="https://twitter.com" style="color: white;">Twitter</a>, <a href="https://github.com" style="color: white;">GitHub</a>.</p>
</footer>

</body>
</html>
