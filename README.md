# Kenbak-1 Web Tools

Une collection de trois outils web dédiés au **Kenbak-1**, considéré comme l'un des premiers ordinateurs personnels de l'histoire.

## 🇫🇷 Français

### Présentation

Ce dépôt contient trois applications HTML autonomes fonctionnant directement dans un navigateur web, sans installation ni dépendance externe :

- **Emulator** : émulateur graphique du Kenbak-1.
- **Assembly** : assembleur permettant de convertir un programme source en code machine Kenbak-1.
- **Colorize** : outil de coloration syntaxique destiné à préparer des listings pour PowerPoint ou des documents pédagogiques.

---

### 1. Kenbak-1 Emulator

L'émulateur reproduit l'apparence et le fonctionnement du Kenbak-1 de 1971.

#### Fonctionnalités

- Reproduction fidèle du panneau avant.
- Registres A, B, X et P visibles en permanence.
- Mémoire complète de 256 octets.
- Saisie via les boutons du panneau.
- Exécution continue avec vitesse réglable.
- Mode pas à pas.
- Breakpoints simples.
- Chargement de programmes en format octal.
- Plusieurs exemples intégrés :
  - Compteur binaire
  - Jeu « Plus ou Moins »
  - Suite de Syracuse

---

### 2. Kenbak-1 Assembler

Assembleur moderne pour le langage machine du Kenbak-1.

#### Fonctionnalités

- Écriture de programmes avec mnémoniques lisibles.
- Gestion des étiquettes (labels).
- Directives :
  - ORG
  - DB
  - EQU
  - START
- Support des constantes :
  - Octal
  - Décimal
  - Hexadécimal
  - Binaire
- Détection des erreurs de syntaxe.
- Affichage du code généré avec adresses et octets en octal.
- Copie directe vers le chargeur de l'émulateur.

---

### 3. Colorize

Outil de coloration syntaxique destiné aux supports de cours et présentations.

#### Fonctionnalités

- Coloration automatique des listings Kenbak-1.
- Couleurs entièrement personnalisables.
- Choix de la police et de la taille.
- Aperçu en temps réel.
- Copie au format HTML enrichi.
- Conservation des couleurs lors du collage dans PowerPoint.

---

### Utilisation

Téléchargez les fichiers :

- `emulator.html`
- `assembly.html`
- `colorize.html`

Puis ouvrez simplement le fichier souhaité dans votre navigateur.

Aucun serveur web