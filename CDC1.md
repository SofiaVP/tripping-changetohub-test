# Cahier des charges - Projet Tripping 
=======================================

1. Fondements du projet 
-----------------------
* But du projet 
...Ce projet est dévéloppé dans le cadre de ma formation d'Architechte logiciel. 

...Le thème étant libre, j'ai choisi de dévélopper le projet **Tripping** : une application permettant à l'utilisateur de générer une liste personalisée d'items à prendre avec soit pendant un voyage. 

* Personnes et organismes impliqués dans les enjeux du projet
...*Maître d’ouvrage* : Isika (????)
...*Equipe de dévéloppeurs* : Sofia Vayas Pedersen (moi)

* Utilisateurs du produit
...Tout public

1. Contraintes sur le projet
----------------------------
*Contraintes sur la conception de la solution
...Il nous est demandé de réaliser une solution complète d'un projet en reprenant les notions vues au cours des modules **Devops, Java JEE, RIA et Cloud**. 

...Il nous est demandé de donner accès: 
...- Au projet sur un repository Git, qui permettra d’accéder à un pipeline, au code source et à un git tree
...- A l'application afin que le jury puisse vérifier sons déploiement en production.

*Environnement de fonctionnement du système 
...- un front Angular, qui se connecte à un backend via une API rest
...- un backend Java Spring sur lequel Angular viendra se connecter
...- une base de données MySQL pour stocker les informations métiers du backend
...- une base de données MongoDB pour stocker les informations « data » (data scraping)
...- une partie server-side en NodeJS qui devra récolter des données sur une source externe, les traiter et les insérer dans la base de données MongoDB

...Le projet complet degra être hébergés dans le Cloud Amazon (AWS). 
...Le code doit être disponible sur internet et devra donc pourvoir être consultable via une URL. Il devra être hébergé par sur un gestionnaire de source Git.

...Il faudra mettre en place un ou plusieurs pipelines de livraison de votre code, depuis votre environnement de développement local jusqu’à la production (sur Amazon AWS).

...En plus de l’intégration continue, le projet devra respecter les règles principales de qualimétrie (test et clean code).

*Applications « partenaires » (avec lesquelles le produit doit collaborer)
...[Weather API](https://openweathermap.org/api)
...[Nomade list](https://nomadlist.com/)

*De combien de temps les développeurs disposent-ils pour le projet ?
...*Phase de dévéloppent* :du vendredi 12 juin au mercredi 22 juillet (6 semaines environ)

...*Présentation orale devant un jury* : le 24 juillet


1. Exigences fonctionelles
===========================
*La situation actuelle
...Il extiste une multitude de application permettant de créer des listes. 

...Sur googlePlay, il existe PackPoint Travel packing list. 
...Dans la section commentaires de cet application, plusieurs suggestions d'améliorations sont proposées ([cliquer ici](https://play.google.com/store/apps/details?id=com.YRH.PackPoint&hl=en) pour visulaiser les commentaires).
...Je ne connaissait pas cette application avant. Heureusement nous ne sommes pas évalué sur l'originalité de notre thème. Je vais me familiariser avec cette application, voici mes commentaires: 
...- likes 👍
......- 
......-
......-
......- 
...- dislikes 👎
......-Listes trop longues
......-
......-
......-


*Exigences fonctionelles 
...- Auto-générer une liste per

*Cas d'utilisation

1. Exigences non-fonctionelles
===============================



1. Evolutions possibles ( ͡° ͜ʖ ͡°)
====================================














