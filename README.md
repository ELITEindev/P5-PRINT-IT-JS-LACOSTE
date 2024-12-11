# Print-it - Site Web d'Imprimerie

## Description
Print-it est un site web d'une imprimerie familiale qui met en avant ses services d'impression de haute qualité. Le site présente les différentes prestations offertes par l'entreprise ainsi que des exemples de réalisations à travers un carrousel d'images interactif.

## Fonctionnalités
- Carrousel d'images interactif avec navigation par flèches
- Présentation des services d'impression
- Design responsive adapté à tous les écrans
- Interface utilisateur intuitive et moderne

## Technologies Utilisées
- HTML5
- CSS3
- JavaScript (Vanilla JS)

## Installation et Utilisation
1. Clonez le repository :
```bash
git clone https://github.com/votre-username/P5-PRINT-IT-JS-LACOSTE.git
```

2. Ouvrez le fichier `index.html` dans votre navigateur web préféré.

## Structure du Projet
- `index.html` : Page principale du site
- `assets/` : Dossier contenant les images et ressources
- `css/` : Fichiers de style CSS
- `js/` : Scripts JavaScript pour le carrousel et l'interactivité

## Fonctionnement du Carrousel
Le carrousel permet de naviguer entre différentes images présentant les services de Print-it :
- Utilisez les flèches gauche et droite pour naviguer entre les images
- Les points en bas du carrousel indiquent la position actuelle
- Le défilement est cyclique (retour au début après la dernière image)

## Animations et Interactivité
### Carrousel d'Images
Le carrousel est entièrement développé en JavaScript vanilla, sans utilisation de bibliothèques externes. Voici les détails techniques :

#### Fonctionnement des Animations
1. **Navigation par Flèches**
   - Les flèches sont rendues interactives via des event listeners
   - Un effet de survol (hover) est appliqué en CSS
   - Animation fluide lors du changement d'image

2. **Système de Points**
   - Points de navigation générés dynamiquement en JavaScript
   - Le point actif est mis en évidence visuellement
   - Mise à jour automatique lors du défilement

3. **Transition des Images**
   - Transition fluide entre les images avec opacity
   - Effet de fondu enchaîné (fade) entre chaque slide
   - Gestion des transitions avec requestAnimationFrame pour de meilleures performances

4. **Gestion du Défilement**
   - Défilement cyclique (retour au début après la dernière image)
   - Vérification des limites pour éviter les erreurs
   - Mise à jour dynamique des indicateurs de position

### Effets Visuels
- Utilisation de transitions CSS pour les animations fluides
- Effets hover sur les éléments interactifs
- Animations subtiles pour améliorer l'expérience utilisateur

### Code et Implémentation
```javascript
// Exemple de structure pour le carrousel
const slides = document.querySelectorAll(".slide");
const dots = document.querySelectorAll(".dot");
const arrows = document.querySelectorAll(".arrow");

// Gestion des transitions
function changeSlide(direction) {
    // Animation fluide avec opacity
    // Mise à jour des indicateurs
    // Gestion du défilement cyclique
}

// Event listeners pour la navigation
arrows.forEach(arrow => {
    arrow.addEventListener("click", () => {
        // Navigation dans le carrousel
    });
});
```

## Contribution
Ce projet a été développé dans le cadre d'un exercice de formation. Les contributions ne sont pas acceptées pour le moment.

## Auteur
Développé par [Votre Nom] dans le cadre du projet 5 du parcours Développeur Web OpenClassrooms.
