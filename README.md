# 🛒 Mini Projet SQL — E-commerce Sénégal

## 📌 Description

Ce projet est un **mini système de base de données e-commerce** développé avec **PostgreSQL**.
Il a été créé dans le but de pratiquer les **bases du langage SQL** à travers un cas réel inspiré d'une boutique en ligne au Sénégal.

La base de données permet de gérer :

* les **clients**
* les **produits**
* les **commandes**
* les **ventes**

Le projet contient les scripts SQL nécessaires pour **créer la base de données, les tables relationnelles, et insérer des données réalistes** afin de pouvoir pratiquer différentes requêtes SQL.

Ce projet est idéal pour les **débutants en SQL** qui souhaitent s'entraîner avec :

* SELECT
* WHERE
* ORDER BY
* LIMIT
* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()
* GROUP BY
* HAVING

---

## 🗂 Structure de la base de données

La base de données **ecommerce_senegal** contient 4 tables principales :

### 1️⃣ clients

Contient les informations des clients.

| colonne | description                  |
| ------- | ---------------------------- |
| id      | identifiant unique du client |
| nom     | nom du client                |
| prenom  | prénom du client             |
| ville   | ville du client              |
| pays    | pays du client               |

---

### 2️⃣ produits

Contient les produits vendus dans la boutique.

| colonne     | description            |
| ----------- | ---------------------- |
| id          | identifiant du produit |
| nom_produit | nom du produit         |
| categorie   | catégorie du produit   |
| prix        | prix du produit        |
| stock       | quantité disponible    |

---

### 3️⃣ commandes

Contient les commandes effectuées par les clients.

| colonne       | description                       |
| ------------- | --------------------------------- |
| id            | identifiant de la commande        |
| client_id     | client ayant effectué la commande |
| date_commande | date de la commande               |
| statut        | statut de la commande             |

---

### 4️⃣ ventes

Contient les détails des produits vendus dans chaque commande.

| colonne     | description       |
| ----------- | ----------------- |
| id          | identifiant       |
| commande_id | commande associée |
| produit_id  | produit vendu     |
| quantite    | quantité vendue   |

---

## 🎯 Objectif pédagogique

L'objectif de ce projet est de permettre de pratiquer :

* la **création de bases de données**
* la **création de tables relationnelles**
* l'utilisation de **clés primaires et étrangères**
* les **requêtes SQL d'analyse de données**

---

## 🧠 Exemples de questions analytiques

Quelques analyses possibles avec cette base :

* Combien de produits avons-nous par catégorie ?
* Quels sont les produits les plus chers ?
* Quel est le prix moyen des produits ?
* Quelle quantité totale de produits a été vendue ?
* Combien de commandes ont été passées ?

---

## 🛠 Technologies utilisées

* **PostgreSQL**
* **SQL**

---

## 📚 Objectif du projet

Ce projet a été réalisé dans le cadre de mon **apprentissage de SQL et de l'analyse de données**.

Il sert de base d'entraînement pour comprendre comment **manipuler et analyser des données avec SQL** dans un contexte proche d'un vrai projet e-commerce.

---
