# Projet 02 : Custom RPG Rules & Sheets Hosting

## Introduction
Ce projet consisterait en un site présentant l'univers et les règles d'un Jeu de Role sur table ("JdR" dans la suite du document) basé sur l'univers de Star Wars, ainsi qu'un système permettant aux utilisateurs de se connecter afin de créer des fiches de personnages directement sur le site.

Cela fait écho à un précédent projet inabouti que je souhaitais réaliser lors d'une année précédente.
Les règles du jeu ont été rédigées par mes soins et, même si elles intègrent certains éléments du JdR Star Wars déjà existant, sont originales. Cela m'empêchera cette fois d'avoir des problèmes avec un client qui changerait significativement les règles au fur et à mesure et donc la structure de toute la base de données et de la présentation sur le site, comme cela avait été le cas l'année dernière.

Je suis bien conscient que ce projet pourrait poser, une fois de plus, des problèmes de droits, mais si l'API du site est adroitement réalisée, je pense que le résultat final pourrait convenir à n'importe quel type de JdR ayant une structure approchant et pas seulement à un JdR Star Wars.   
Je vois donc ce projet plutôt comme un site permettant l'hébergement de règles et la création de personnages d'un univers donné plutôt que véritablement quelque chose de spécifique à l'univers Star Wars. Cet univers licensié pourra donc être substitué au besoin.

Pour vous faire une idée de ce que représente la charge de travail relative aux règles du jeu et à la création de personnage, je ne peux que vous inviter à consulter les règles du JdR rédigées par mes soins et [disponibles à cette adresse](http://tanguyscholtes.be/StarWarsJDR/ "Star Wars JdR - Tanguy Scholtes") ainsi qu'[un exemple de fiche de personnage](http://www.pathfinder-fr.org/wiki/GetFile.aspx?File=%2fADJ%2fPathfinder-RPG%2fPFSheet.pdf "Feuille de personnage - Pathfinder-fr") tirée du système "Pathfinder - Le Jeu de Rôle".

Ce projet me tiens vraiment à coeur car j'aime beucoup le JdR, j'en fais régulièrement et la possibilité de pouvoir consulter en ligne les règles d'un jeu (même fait-maison) ainsi que de pouvoir créer simplement sa fiche de personnage pour ce système sont des choses que j'ai souhaitéées à de nombreuses reprises. Et si c'est en mon pouvoir de les concrétiser, je souhaiterai m'y atteler.
Pour ce qui est de la technologie, je souhaiterai utiliser Laravel pour tout ce que le framework apporte, notamment ses nombreux outils et la facilité de déploiement sur serveur. De même, je souhaiterai pouvoir utiliser une base de donnée en MySQL via PHPMyAdmin et Laravel le permet par défaut, ce qui rend le framework d'autant plus attrayant pour moi.

## Cahier des charges
- Hébergement des règles du jeu
- Système d'enregistrement et de connexion d'utilisateurs avec 2 niveaux de comptes : Utilisateurs et Administrateur
- Possibilité pour les visiteurs de consulter les fiches de personnages et de créer un compte Utilisateur
- Possibilité pour l'Utilisateur de créer, éditer et supprimer ses propres fiches de personnages
- Possibilité pour l'Utilisateur de modifier ou supprimer son compte et les fiches associées
- Possibilité pour l'Administrateur de gérer les règles du jeu (ajout, édition, suppression d'un élément du jeu, Ex. un objet, une compétence ou une race jouable)
- Possibilité pour l'Administrateur de gérer le site (ajout, édition, suppression d'une page du site, gestion des éléments visuels comme le fond et la bannière, ...)
