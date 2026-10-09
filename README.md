# Elan-Fitness
*# 🏋️‍♂️ Élan Fitness — Migration d'un site One-Pager vers un site Multipage

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![W3C Validated](https://img.shields.io/badge/W3C-Validated-brightgreen?style=for-the-badge)
![Responsive Design](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-blue?style=for-the-badge)

## 📌 Contexte du Projet

Dans le cadre du développement de sa présence numérique, la société **Élan Fitness** souhaite moderniser son identité en migrant d'un site à page unique (*One-Pager*) vers une architecture **Multipage**. 

En tant qu'**Intégrateur Web**, l'objectif de ce projet est de restructurer le contenu, de créer une expérience utilisateur fluide et cohérente (UX/UI), et d'assurer une parfaite adaptabilité sur l'ensemble des écrans (Responsive Design).

---

## 🎯 Objectifs & Fonctionnalités Implémentées

### 🎨 1. Conception & Identité Visuelle
- **Analyse du contenu :** Redéfinition et répartition du contenu One-Pager en 4 pages d'atterrissage distinctes.
- **Identité graphique :** Proposition d'un logo moderne respectant la charte graphique d'Élan Fitness.
- **Gestion des médias :** Intégration de visuels et contenus textuels libres de droits, attractifs et pertinents.

### 💻 2. Développement Front-End & Multipage
- **Page Accueil (`accueil.html`) :** Présentation globale de la salle, mise en avant des points forts et appel à l'action (CTA) vers les programmes.
- **Page Programmes (`programme.html`) :** Présentation détaillée des cours (Musculation, Yoga, Cardio, Boxe) et des formules d'abonnement (Essentiel, Premium, Duo).
- **Page À propos (`propos.html`) :** Présentation de l'histoire de la salle, de ses valeurs fondamentales et de l'équipe de coachs.
- **Page Contact (`contact.html`) :** Formulaire de message interactif, coordonnées complètes et informations d'accès.
- **Système de Navigation :** Menu fixe et responsive avec indicateur visuel de la page active (`.lien-actif`).

### 🚀 3. Bonus & Optimisations Avancées
- **📱 Design Responsive complet :**
  - Grand écran d'ordinateur ($\ge$ 1280px)
  - Petit écran d'ordinateur (1024px – 1279px)
  - Tablette (768px – 1023px)
  - Mobile ($\le$ 767px) avec menu burger interactif
- **✨ Transitions & Animations CSS :**
  - Transitions douces au survol des liens et boutons (`transition`, `transform: scale()`).
  - Effet de survol avec élévation et ombrage dynamique (`box-shadow`, `translateY`) sur les cartes de programmes.
- **🔍 SEO (Référencement Naturel) :**
  - Balises méta optimisées (`description`, `viewport`, `charset`).
  - Structure sémantique HTML5 complète (`header`, `nav`, `main`, `section`, `article`, `footer`).
  - Attributs `alt` systématiques et explicites sur toutes les images.

---

## 🛠️ Technologies Utilisées

- **HTML5** (Structure sémantique et conforme WCAG)
- **CSS3** (Flexbox, CSS Grid, Media Queries, Keyframes & Transitions)
- **Git / GitHub** (Gestion de versions et hébergement via GitHub Pages)

---

## 📂 Structure du Repository

```text
elan-fitness/
├── index.html          # Page d'accueil principale
├── accueil.html        # Redirection / Clone d'accueil
├── propos.html         # Page À propos
├── programme.html      # Page des programmes et tarifs
├── contact.html        # Page de contact
├── style.css           # Feuille de style CSS principale
├── img/                # Dossier des images et icônes
│   ├── bar.jpg         # Logo principal
│   ├── logo.jpg        # Favicon
│   ├── musculation.jpg
│   ├── yoga.jpg
│   ├── cardio.jpg
│   ├── boxe.jpg
│   ├── bronz.jpg
│   ├── sulvre.jpg
│   └── gold.jpg
└── README.md           # Documentation du projet
