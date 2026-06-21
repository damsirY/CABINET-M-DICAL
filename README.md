[readme.md](https://github.com/user-attachments/files/29181524/readme.md)
# 🏥 Application de Gestion des Soins à Domicile & Indemnités

Une application web moderne, fluide et responsive, conçue pour un **Cabinet Médical** afin d'assurer le suivi des soins à domicile prodigués par les infirmiers, ainsi que le calcul automatisé de leurs indemnités kilométriques et primes de pénibilité par le Major (Admin).

---

## 🛠️ Technologies Utilisées

* **HTML5 & CSS3** : Structure sémantique et design moderne inspiré par des palettes médicales épurées (utilisation de variables CSS, flexbox et grid).
* **JavaScript (ES6+)** : Logique métier dynamique, manipulation du DOM, et gestion du cycle de vie des sessions.
* **Web Storage (Local Storage)** : Persistance locale des données pour simuler une base de données relationnelle locale (`users` et `soins`).
* **FontAwesome (v6.4.0)** : Bibliothèque d'icônes vectorielles pour enrichir l'expérience utilisateur visuelle.

---

## 📂 Structure du Projet

```text
├── index.html        # Page d'authentification (Connexion / Inscription)
├── agent.html        # Interface Infirmier : CRUD complet des fiches de soins
├── admin.html        # Interface Major (Admin) : Calcul des indemnités & KPIs
└── style.css         # Feuille de style globale (Thème MedCare & Responsive)

