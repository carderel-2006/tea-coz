# The Tea Cozy

Page web d'un salon de thé fictif à Portland (Maine), réalisée en HTML et CSS à partir d'une maquette annotée. L'objectif du projet est de reproduire fidèlement la maquette : dimensions, couleurs, typographie et espacements.

## Aperçu

La page présente :

- **Un header fixe** avec le logo et la navigation (Mission, Featured Tea, Locations)
- **Our Mission** : une grande image d'accueil avec le message de la marque
- **Tea of the Month** : une sélection de 5 thés et pâtisseries de saison
- **Locations** : les trois adresses (Downtown, East Bayside, Oakdale)
- **Un footer** avec les coordonnées et le copyright

## Technologies

- HTML5
- CSS3 (Flexbox, media queries)

## Structure du projet

    tea-cozy/
    ├── index.html
    ├── style.css
    └── img/
        ├── logo.png
        ├── mission.jpg
        ├── fall-berry.jpg
        ├── spiced-rum.jpg
        ├── donuts.jpg
        ├── myrtle.jpg
        ├── bedford.jpg
        └── locations.jpg

## Installation et utilisation

1. Télécharge ou clone le projet.
2. Place les images dans le dossier `img/` avec les noms indiqués ci-dessus.
3. Ouvre `index.html` dans ton navigateur.

## Choix de design

- Police : Helvetica, 22px
- Couleur du texte : `seashell` sur fond noir
- Header fixe de 69px avec une bordure basse de 1px
- Sections centrées, avec des largeurs de 1000px et 1200px
- Images des thés en 300 × 200px
- Cartes des adresses de 300px espacées de 40px

## Responsive

Une media query (`max-width: 768px`) adapte la page aux téléphones et aux petites tablettes :

- Navigation sur deux lignes
- Cartes des adresses empilées
- Images en pleine largeur

## Améliorations possibles

- Ajouter des animations au survol des liens
- Rendre la navigation cliquable avec un défilement fluide (`scroll-behavior: smooth`)
- Ajouter un formulaire de contact

## Auteur

Projet réalisé dans le cadre d'un exercice d'intégration web.