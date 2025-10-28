#    Job Listings Application

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6?style=flat\&logo=css3\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E?style=flat\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)


---

## **Description**

Job Listings Application est une application Front-End moderne permettant de gérer des offres d’emploi. Elle offre une interface interactive, des fonctionnalités avancées de recherche et filtrage, et un système de favoris avec persistance des données via `localStorage`.

**Fonctionnalités clés :**

* Recherche et filtrage d’offres par mots-clés, compétences, type de contrat et localisation.
* Gestion complète des offres (CRUD).
* Système de favoris persistant.
* Gestion du profil utilisateur avec compétences.
* Interface responsive et intuitive sur mobile et desktop.

---



---

## **Fonctionnalités principales**

### 1. Profil utilisateur

* Créer et modifier un profil (nom, poste, compétences).
* Validation de formulaire avec feedback instantané.
* Sauvegarde automatique dans `localStorage`.

### 2. Gestion des offres (CRUD)

* Ajouter, modifier et supprimer des offres via modals.
* Affichage des offres sous forme de cartes responsive.
* Validation des champs obligatoire pour garantir l’intégrité des données.

### 3. Favoris

* Ajouter ou retirer des offres des favoris.
* Onglet dédié aux favoris avec compteur dynamique.
* Persistance des favoris même après fermeture du navigateur.

### 4. Recherche et filtres

* Recherche par mots-clés dans titres, entreprises et descriptions.
* Filtres par compétences, type de contrat et localisation.
* Combinaison recherche + filtres pour affiner les résultats en temps réel.

### 5. UX & UI

* Interface moderne et responsive sur mobile et desktop.
* Modals pour visualiser les détails d’une offre et gérer les jobs.
* Feedback visuel sur les interactions (favoris, formulaire, modals).

---

## **Technologies**

* HTML5
* CSS3 (Flexbox & Grid)
* JavaScript Vanilla (ES6+)
* LocalStorage API pour la persistance des données
* JSON pour le stockage initial des offres

---

## **Installation et utilisation**

1. Cloner le repository :

```bash
git clone https://github.com/<YOUR_USERNAME>/<REPO_NAME>.git
```

2. Ouvrir `index.html` dans un navigateur moderne.
3. Tester les fonctionnalités :

   * Ajouter, modifier et supprimer des offres.
   * Marquer des offres comme favorites.
   * Rechercher et filtrer les offres.
   * Gérer le profil utilisateur et compétences.

---

## **Structure du projet**

```
job-listings-app/
│
├─ assets/
│   ├─ data/
│   │   └─ data.json        # Données initiales des offres
│   ├─ images/              # Logos et images des entreprises
│   └─ screenshots/         # Captures d'écran pour le README
│
├─ index.html               # Fichier HTML principal
├─ style.css                # Feuille de style principale
├─ script.js                # Logique JavaScript principale
└─ README.md                # Documentation complète du projet
```

---

## **User Stories**

* En tant qu’utilisateur, je veux voir des messages d’erreur si mon profil est incomplet.
* En tant qu’utilisateur, je peux ajouter, modifier et supprimer des offres d’emploi.
* En tant qu’utilisateur, je peux rechercher et filtrer les offres par mots-clés et compétences.
* En tant qu’utilisateur, je peux marquer des offres comme favorites et les retrouver ultérieurement.
* En tant qu’utilisateur, je veux que l’interface soit responsive et intuitive.

---

## **Améliorations futures**

* Validation avancée des formulaires (regex pour email, URL, etc.).
* Suggestions automatiques lors de la recherche.
* Filtres à facettes multiples pour filtrage complexe.
* Animations pour transitions et modals.
* Export des favoris en PDF ou partage de lien.
* Système de notation et classement des offres.

---

## **Licence**

Ce projet est sous licence MIT.
[MIT License](https://opensource.org/licenses/MIT)

---

## **Live Demo**

lien github pages

## **Repository**

https://github.com/Ot4man/Brief-4-.git