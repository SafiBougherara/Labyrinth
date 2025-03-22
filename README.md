# Jeu de Labyrinthe en PHP

## Description
Ce projet est un jeu de labyrinthe développé en PHP et HTML. Le joueur contrôle un personnage qui doit naviguer dans un labyrinthe, collecter des objets et atteindre la sortie. Le jeu utilise une matrice pour représenter le terrain et gère les déplacements en fonction des touches pressées.

## Concept de la Matrice
Une matrice est un tableau à deux dimensions utilisé pour structurer des données sous forme de grille. Dans ce projet, elle représente le labyrinthe où chaque case peut contenir un mur, un passage libre, un objet ou le personnage. Voici un exemple simplifié :

```
O O O O O
O C _ K O
O _ O _ O
O _ E _ O
O O O O O
```

- `O` : Mur
- `_` : Chemin libre
- `C` : Personnage
- `E` : Epée
- `K` : Clé

Le personnage peut se déplacer sur les chemins libres et doit récupérer des clés pour progresser.

## Fonctionnalités
- Déplacement du personnage avec gestion des collisions.
- Collecte d'objets (clés, épées, etc.).
- Réinitialisation du labyrinthe.
- Effets sonores lors des déplacements.

## Technologies utilisées
- **PHP** : Gestion de la logique du jeu (déplacements, session).
- **HTML & CSS** : Interface du jeu.
- **JavaScript (optionnel)** : Effets interactifs.

## Installation et Exécution
1. Assurez-vous d'avoir un serveur local (XAMPP, WAMP, etc.).
2. Placez les fichiers du projet dans le dossier `htdocs` (ou équivalent).
3. Ouvrez un navigateur et accédez à `http://localhost/jeu`

## Auteurs
- Safi

Bon jeu ! 🎮

![{8AE0A165-1878-4B54-B926-1448BECA7933}](https://github.com/user-attachments/assets/0d635127-e28d-4432-8488-3a10bae4e02c)

![{7930D426-9DB3-456E-9C6B-A3CCF4492F14}](https://github.com/user-attachments/assets/32b3485a-0571-4319-94b3-a3f812a507e8)

![{FCAB89A5-8617-4DA4-B8A1-28305069E963}](https://github.com/user-attachments/assets/ade5d109-94b4-49d5-b663-345371bcc818)

![{1B036A0F-37DC-4A11-BCCC-C592CD3B7D92}](https://github.com/user-attachments/assets/7d725e98-3c2f-49a1-b261-ca9d67a864f8)
