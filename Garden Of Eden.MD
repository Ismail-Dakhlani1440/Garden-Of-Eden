# 🌱 Garden of Eden

## 📌 Présentation

**Garden of Eden** est une application web de type **Digital Garden** développée en **PHP 8 procédural**. Elle permet à chaque utilisateur de créer un compte et de gérer un **jardin numérique personnel et privé**, composé de **thèmes** et de **notes**.

Le but de l’application est d’offrir une manière simple, claire et visuelle d’organiser ses idées, projets et informations personnelles.

Ce projet a été réalisé dans un **cadre pédagogique** afin de mettre en pratique les bases du développement web full‑stack avec PHP et MySQL.

---

## 🎯 Objectifs pédagogiques

À travers ce projet, j’ai travaillé sur :

* La logique **PHP procédural** (conditions, fonctions, includes)
* La gestion des **sessions et de l’authentification**
* La création et l’utilisation d’une **base de données relationnelle**
* La mise en place d’un **CRUD complet**
* La **sécurité web** (SQL Injection, XSS, validation)
* L’organisation du code et la méthodologie de travail

---

## 🛠️ Technologies utilisées

### Backend

* PHP 8 (procédural)
* MySQL
* MySQLi (requêtes préparées)
* Sessions PHP

### Frontend

* HTML5 / CSS3
* Bootstrap ou Tailwind CSS
* JavaScript (validation et interactions simples)

### Outils

* Git / GitHub
* Jira (gestion des tâches)
* UML (diagrammes de conception)

---

## 🔐 Fonctionnalités

### Authentification

* Inscription avec validation côté client et serveur
* Connexion sécurisée
* Ouverture et gestion de session
* Redirections automatiques selon l’état de connexion

### 🌼 Gestion des thèmes

* Ajouter, modifier et supprimer des thèmes
* Choix obligatoire d’une couleur
* Ajout de tags (optionnel)
* Affichage du nombre de notes par thème

### 📝 Gestion des notes

* Création, modification et suppression
* Importance de 1 à 5
* Association obligatoire à un thème
* Filtres par :

  * thème
  * importance
  * mot‑clé

---

## 🔒 Sécurité

* Utilisation de **requêtes préparées** pour éviter les injections SQL
* Validation et nettoyage des données utilisateur
* Protection contre les attaques XSS
* Accès limité aux données de l’utilisateur connecté uniquement

---

## 📂 Arborescence du projet

```
digital-garden/
│── index.php
│── login.php
│── register.php
│── dashboard.php
│── themes.php
│── notes.php
│
│── config/
│   └── database.php
│
│── includes/
│   ├── header.php
│   ├── footer.php
│   └── auth.php
│
│── public/
│   ├── css/
│   └── js/
│
└── sql/
    └── schema.sql
```

---

## 🗄️ Base de données

La base de données contient :

* `users`
* `themes`
* `notes`
* (optionnel) tables liées aux tags

Les relations sont sécurisées avec des **clés étrangères**.
Le script SQL est disponible dans le dossier `/sql`.

---

## 📊 UML

Les diagrammes suivants sont fournis :

* Diagramme de cas d’utilisation
* Diagramme de classes
* Diagramme de séquence (optionnel)

---

## ⚡ Performance et bonnes pratiques

* Requêtes SQL optimisées
* Pas de duplication de code (principe DRY)
* Fichiers séparés et bien organisés
* Connexion à la base ouverte uniquement lorsque nécessaire
* Messages d’erreur clairs sans afficher d’informations sensibles

---

## ▶️ Installation locale

1. Cloner le repository :

   ```bash
   git clone https://github.com/Ismail-Dakhlani1440/Garden-Of-Eden.git
   ```
2. Importer le fichier `schema.sql` dans MySQL
3. Configurer la connexion à la base de données dans `config/database.php`
4. Lancer le projet avec un serveur local (XAMPP, WAMP, Laragon)

---

## 👤 Auteur

Projet réalisé par **Ismail Dakhlani**
Dans le cadre d’un projet pédagogique Full‑Stack PHP

---

## 📅 Informations

* Lancement du brief : **04/12/2025**
* Date limite de soumission : **19/12/2025**

---

Ce projet m’a permis de consolider mes bases en développement web et de mieux comprendre la structure complète d’une application PHP sécurisée.
