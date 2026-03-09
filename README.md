# Learn Snake – Pallier 3

Prototype mobile-first de l’application **Make Your Own Snake**.

Ce pallier ajoute un vrai flow d’onboarding avant le jeu Snake.

## Fonctionnalités

- écran d’accueil avec :
  - titre **Make Your Own Snake 🐍**
  - bouton **Get Started**
  - texte **I already have an account**

- choix de la langue avec :
  - Français
  - English
  - Deutsch
  - cartes visuelles avec drapeaux SVG

- création de compte avec :
  - nom
  - email
  - mot de passe

- connexion via **I already have an account**

- sauvegarde locale des données avec `localStorage`

- écran de jeu Snake :
  - bouton **START**
  - le bouton disparaît après clic
  - le serpent et la nourriture n’apparaissent qu’au démarrage
  - déplacement avec wrap-around
  - game over uniquement sur auto-collision

- fond animé :
  - grille de points
  - mini serpents lumineux aléatoires
  - petits déplacements avec virages à angle droit

## Fichiers

- `index.html`
- `style.css`
- `script.js`

## Objectif

Construire progressivement une application d’apprentissage du code inspirée de Mimo / Duolingo, où l’utilisateur apprend en créant son propre Snake.

## Suite prévue

- boutons retour dans l’onboarding
- premier écran de leçon
- progression utilisateur
- traductions complètes plus tard
