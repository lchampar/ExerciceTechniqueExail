# Penalty Prototype – Unreal Engine 5.7.4

## Contexte

Je n'ai jamais utilisé Unreal Engine auparavant et ce projet est ma première utilisation d’Unreal Engine.
Temps consacré au projet : Entre la découverte de l'environnement, la compréhension et la réalisation du projet, environ 1h30/2h.


## Présentation de l'exercice

Ce projet est un prototype simple de tir au but fait avec Unreal Engine 5.7.4 et développé entièrement en Blueprint.

Le joueur utilise la souris pour viser une zone située dans le but, puis clique gauche afin de tirer le ballon dans la direction choisie.

Les objectifs du projet sont de :

- découvrir et prendre en main Unreal Engine
- comprendre le fonctionnement du moteur et des différents éléments
- découvrir les Blueprints (structuration, lisibilité)


## Fonctionnalités

- On a une caméra fixe orientée vers le but
- On peut sélectionner un point de visée avec la souris
- Tir au clic gauche
- Calcul de la direction entre le ballon et le point visé (pour savoir dans quel sens part le ballon)
- Application d’une impulsion physique au ballon pour le faire avancer
- Décor simple réalisé avec les formes de base d’Unreal Engine (cube, cylindre, sphère)


## Choix techniques

Le choix technique du langage était plus personnel : bien que je possède des connaissances en C++, j’ai choisi le Blueprint afin de découvrir ce système de programmation.


## Fonctionnement du Blueprint

- La partie du haut sert à initialiser l'affichage du curseur de la souris et s'exécute au lancement de l'application.

- Le tir est construit selon les étapes suivantes :

	1. Récupération des coordonnées du point sélectionné avec la souris
	2. On récupère les coordonnées du ballon
	3. On calcule le vecteur entre le ballon et le point visé (avec le -)
	4. Normalisation de ce vecteur afin de ne garder que l’orientation
	5. On multiplie l'orientation par une valeur qui sert de puissance au tir
	6. On applique le vecteur obtenu au ballon sous forme d’impulsion

## Installation et lancement

### Prérequis

- Unreal Engine 5.7.4
- Git, pour cloner le dépôt

### Procédure

1. Cloner le dépôt
2. Ouvrir le dossier du projet.
3. Double-cliquer sur le fichier ".uproject".
4. Vérifier que le projet est lancé avec Unreal Engine 5.7.4.
5. La carte du jeu se charge normalement automatiquement, sinon :
	5.1. "Fichier"
	5.2. "Ouvrir un niveau"
	5.3. Et choisir "PenaltyProjet"
6. Cliquer sur le bouton "Play" dans l’éditeur.


## Ressources utilisées

Le prototype utilise :

- les formes géométriques fournies par Unreal Engine
- les systèmes de collision et de physique intégrés au moteur
- les Blueprints d’Unreal Engine
- Aucune ressource externe complexe n’est nécessaire au fonctionnement du projet.


## Utilisation de l’intelligence artificielle

Intelligence artificielle : ChatGPT 5.6 Sol a été utilisé comme assistant pour :

- rechercher les nœuds Blueprint
- organiser la logique de tir
- détecter et résoudre certains problèmes rencontrés


## Améliorations pensées

Des évolutions pourraient être ajoutées :

- remise en place automatique du ballon avec clic droit ou autre touche
- réglage de la puissance du tir lors du jeu
- afficher un viseur
- détection d'un but marqué
- compteur de score
- ajouter tireur + gardien
- matériaux et environnement plus jolis


## Appréciation

Même si ce n'est pas demandé, je pense tout de même que c'est intéressant que je donne mon avis sur ce premier projet.
De mon côté, j'ai apprécié ce projet et ça permet à ceux qui n'ont jamais utilisé l'environnement de le découvrir et de savoir dans quoi on met les pieds.
De plus, c'est la même méthode que mon précédent chef avait faite lors de mon stage en développement sur Windev.
Comme je l'ai expliqué, j'ai bien aimé ce premier projet que ce soit l'environnement de travail et le fait de créer en 3D. Pour le langage, je n'ai pas encore d'avis définitif, je n'ai rien fait de très complexe encore dessus.
Et pour finir, je suis motivé pour en découvrir plus à l'avenir si je suis retenu pour la suite des candidatures.

## Auteur

Loïc Champarnaud

