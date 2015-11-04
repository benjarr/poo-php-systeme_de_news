----------------------------------
SYSTEME DE NEWS BASIQUE EN POO PHP
----------------------------------

Cette application a été réalisé à l'aide du cours "Programmez en orienté objet en PHP" de OpenClassrooms.


Cahier des charges
------------------

Commençons par définir ce que nous allons faire et surtout, ce dont nous allons avoir besoin.

Ce que nous allons réaliser est très simple, à savoir un système de news basique avec les fonctionnalités suivantes :

    Affichage des cinq premières news à l'accueil du site avec texte réduit à 200 caractères.

    Possibilité de cliquer sur le titre de la news pour la lire entièrement. L'auteur et la date d'ajout apparaîtront, ainsi que la date de modification si la news a été modifiée.

    Un espace d'administration qui permettra d'ajouter / modifier / supprimer des news. Cet espace tient sur une page : il y a un formulaire et un tableau en-dessous listant les news avec des liens modifier / supprimer. Quand on clique sur « Modifier », le formulaire se pré-remplit.

Pour réaliser cela, nous allons avoir besoin de créer une table news


Installation
------------

1) Télécharger l'application dans votre serveur web (XAMPP, WAMP, MAMP, ...)
2) Créez une base de données nomée "news"
3) Importez la structure de la table news (bdd/structure.sql) dans la base de données créée ci-dessus.
4) Enjoy !