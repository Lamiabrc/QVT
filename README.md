# QVT Box – Application Flutter

**QVT Box** est une application Flutter conçue pour améliorer la qualité de vie au travail en permettant aux entreprises de proposer des box bien-être personnalisées à leurs salariés.

## 🚀 Fonctionnalités principales

- Connexion entreprise / salarié
- Sélection de box par thématique (Télétravail, Bureau, Retraite, Itinérant, etc.)
- Personnalisation des box (choix de produits physiques et virtuels)
- Ajout de produits payants en option via la boutique
- Rappels bien-être et actions humaines
- Système d’abonnement entreprise

## 📦 Structure technique

- Framework : Flutter 3.29.2
- Plateformes cibles : Web + Mobile (iOS / Android via PWA)
- Backend : Firebase (authentification, base de données, hébergement)
- Langage : Dart
- Design : Logo et charte inspirés de QVT Box

## 🛠️ Installation et test local (Web)

```bash
flutter pub get
flutter build web
cd build/web
python -m http.server 8080
