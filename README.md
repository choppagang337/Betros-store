# Betros-store
Bussiness 
pour dire bonjour
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Projet JavaScript</title>
</head>
<body>
    <!-- Éléments HTML à modifier avec JavaScript -->
    <p id="google">Texte original pour Google</p>
    <p id="betros">Texte original pour Betros</p>

    <!-- Intégration du code JavaScript -->
    <script>
        // Votre code JavaScript ici
        function direBonjour(nom) {
            console.log("Bonjour, " + nom + " !");
        }

        // Appeler la fonction avec des noms différents
        direBonjour("Alice");
        direBonjour("Bob");

        // Vérifier l'âge
        let age = 18;
        if (age >= 18) {
            console.log("Vous êtes majeur !");
        } else {
            console.log("Vous êtes mineur.");
        }

        // Boucle pour répéter une action
        for (let i = 0; i < 5; i++) {
            console.log("C'est la répétition numéro " + i);
        }

        // Modifier le texte d'un élément HTML (exemple avec l'ID "google")
        document.getElementById("google").innerText = "Bienvenue sur betros store !";

        // Modifier le texte d'un autre élément HTML (exemple avec l'ID "betros")
        document.getElementById("betros").innerText = "Découvrez betros store !";
    </script>
</body>
</html><!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Projet JavaScript</title>
</head>
<body>
    <!-- Éléments HTML à modifier avec JavaScript -->
    <p id="google">Texte original pour Google</p>
    <p id="betros">Texte original pour Betros</p>

    <!-- Intégration du code JavaScript -->
    <script>
        // Votre code JavaScript ici
        function direBonjour(nom) {
            console.log("Bonjour, " + nom + " !");
        }

        // Appeler la fonction avec des noms différents
        direBonjour("Alice");
        direBonjour("Bob");

        // Vérifier l'âge
        let age = 18;
        if (age >= 18) {
            console.log("Vous êtes majeur !");
        } else {
            console.log("Vous êtes mineur.");
        }

        // Boucle pour répéter une action
        for (let i = 0; i < 5; i++) {
            console.log("C'est la répétition numéro " + i);
        }

        // Modifier le texte d'un élément HTML (exemple avec l'ID "google")
        document.getElementById("google").innerText = "Bienvenue sur betros store !";

        // Modifier le texte d'un autre élément HTML (exemple avec l'ID "betros")
        document.getElementById("betros").innerText = "Découvrez betros store !";
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Description professionnelle de votre site web.">
    <meta name="keywords" content="HTML, CSS, JavaScript, Betros, Store">
    <meta name="author" content="Votre Nom">
    <title>Betros Store - Votre Boutique en Ligne</title>
    <!-- Lien vers une feuille de style CSS externe -->
    <link rel="stylesheet" href="styles.css">
    <!-- Lien vers une icône de site (favicon) -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
    <!-- En-tête de la page -->
    <header>
        <h1>Bienvenue sur Betros Store</h1>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#produits">Produits</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Section principale -->
    <main>
        <section id="accueil">
            <h2>Accueil</h2>
            <p>Découvrez notre sélection exclusive de produits.</p>
        </section>

        <section id="produits">
            <h2>Nos Produits</h2>
            <p>Explorez notre gamme de produits de haute qualité.</p>
        </section>

        <section id="contact">
            <h2>Contactez-nous</h2>
            <p>Pour toute question, n'hésitez pas à nous contacter.</p>
        </section>
    </main>

    <!-- Pied de page -->
    <footer>
        <p>&copy; 2023 Betros Store. Tous droits réservés.</p>
    </footer>

    <!-- Lien vers un fichier JavaScript externe -->
    <script src="script.js"></script>
</body>
</html>
body {
       font-family: Arial, sans-serif;
       margin: 0;
       padding: 0;
       background-color: #f4f4f4;
   }
   header {
       background-color: #333;
       color: #fff;
       padding: 10px 0;
       text-align: center;
   }
   nav ul {
       list-style: none;
       padding: 0;
   }
   nav ul li {
       display: inline;
       margin: 0 15px;
   }
   nav ul li a {
       color: #fff;
       text-decoration: none;
   }
   main {
       padding: 20px;
   }
   footer {
       background-color: #333;
       color: #fff;
       text-align: center;
       padding: 10px 0;
       position: fixed;
       width: 100%;
       bottom: 0;
   }
   // Exemple de fonction JavaScript
   function afficherMessage() {
       alert("Bienvenue sur Betros Store !");
   }
   // Appeler la fonction au chargement de la page
   window.onload = afficherMessage;
   nav ul li a:hover {
         color: #ff6347; /* Couleur au survol */
         text-decoration: underline;
     }
     /projet-betros
│
├── index.html
├── styles.css
├── script.js
└── favicon.ico
<form action="/envoyer" method="post">
         <label for="nom">Nom :</label>
         <input type="text" id="nom" name="nom" required>
         
         <label for="email">Email :</label>
         <input type="email" id="email" name="email" required>
         
         <label for="message">Message :</label>
         <textarea id="message" name="message" required></textarea>
         
         <button type="submit">Envoyer</button>
     </form>
     nav ul li a:hover {
         color: #ff6347; /* Couleur au survol */
         text-decoration: underline;
     }<a href="#top" id="retour-haut">↑ Retour en haut</a>
     #retour-haut {
         position: fixed;
         bottom: 20px;
         right: 20px;
         background-color: #333;
         color: #fff;
         padding: 10px;
         text-decoration: none;
         border-radius: 5px
         body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

nav ul li a:hover {
    color: #ff6347;
    text-decoration: underline;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}// Exemple : Afficher une alerte au chargement de la page
window.onload = function() {
    alert("Bienvenue sur Betros Store !");
};

// Exemple : Ajouter un effet de clic sur les liens de navigation
document.querySelectorAll('nav ul li a').forEach(link => {
    link.addEventListener('click', () => {
        alert(`Vous avez cliqué sur : ${link.textContent}`);
    });
});
form {
         max-width: 400px;
         margin: 0 auto;
         padding: 20px;
         background-color: #fff;
         border-radius: 8px;
         box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
     }
     label {
         display: block;
         margin-bottom: 8px;
         font-weight: bold;
     }
     input, textarea {
         width: 100%;
         padding: 10px;
         margin-bottom: 15px;
         border: 1px solid #ccc;
         border-radius: 4px;
     }
     button {
         background-color: #333;
         color: #fff;
         padding: 10px 20px;
         border: none;
         border-radius: 4px;
         cursor: pointer;
     }
     button:hover {
         background-color: #ff6347;
     }#retour-haut {
         position: fixed;
         bottom: 20px;
         right: 20px;
         background-color: #333;
         color: #fff;
         padding: 10px;
         text-decoration: none;
         border-radius: 5px;
         opacity: 0;
         transition: opacity 0.3s ease;
     }
     #retour-haut.visible {
         opacity: 1;
     }@media (max-width: 768px) {
         nav ul li {
             display: block;
             margin: 10px 0;
         }
         form {
             padding: 10px;
         }
     }<section id="galerie">
         <h2>Galerie</h2>
         <div class="galerie-images">
             <img src="image1.jpg" alt="Produit 1">
             <img src="image2.jpg" alt="Produit 2">
             <img src="image3.jpg" alt="Produit 3">
         </div>
     </section>
     .galerie-images {
           display: flex;
           flex-wrap: wrap;
           gap: 10px;
       }
       .galerie-images img {
           width: 100%;
           max-width: 300px;
           border-radius: 8px;
       }/projet-betros
│
├── index.html
├── styles.css
├── script.js
└── favicon.ico=
