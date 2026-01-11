📦 Projet Base de données d'un site e-commerce en france avec analyse décisionnelle. 

Ce projet présente la conception et l’analyse d’une base de données relationnelle pour une plateforme e-commerce en France, en utilisant Python (Jupyter Notebook), Oracle SQL Developer, JMerise/Looping, Power BI et Git/GitHub.
Il couvre la modélisation de la base, l’intégration des données, la génération de tableaux de bord et l’analyse décisionnelle, permettant de produire des indicateurs clés et insights sur la performance commerciale et opérationnelle.

Le projet démontre des compétences en Python, SQL, modélisation de données et visualisation, avec un focus sur la prise de décision basée sur les données dans un contexte e-commerce.


🗂️ Structure de la base de données

La base de données est composée de 9 entités principales :

| Nom de la table   | Description                                       |
| ----------------- | ------------------------------------------------- |
| Clients           | Stocke les informations personnelles des clients  |
| Commandes         | Contient les données de transactions par commande |
| Articles_commandes| Détaille les quantités de produits par commande   |
| Produits          | Catalogue des produits                            |
| Fournisseurs      | Informations sur les fournisseurs                 |
| Avis              | Avis clients et notes des produits                |
| Paiements         | Enregistrements des transactions de paiement      |
| Livraisons        | Suivi des livraisons et de l’état des envois      |
| Geolocalisation   | Contient la localisation clients et fournisseurs  |

🧱 Principales étapes du projet

1️⃣ Conception de la base de données

- Identification des entités et des relations
- Création d’un diagramme entité-relation complet (ERD); diagramme logique de donnée et diagramme de classe
- Définition des clés primaires (PK) et des clés étrangères (FK)

2️⃣ Création et la generation de la base de données (jupyter notebook (python); sql developer)

- Création de toutes les tables avec SQL
- Ajout de contraintes : PK, FK, CHECK, UNIQUE
- generer les fichier .csv nous permettant de faire notre analyse

3️⃣ Analyse SQL, requêtes commerciales et power BI

Réalisation de requêtes avancées pour obtenir des insights clés :

- Revenu global et évolution du chiffre d’affaires (mensuel / annuel)
- Catégorie de produits la plus vendue
- Taux global de livraison
- Clients les plus dépensiers
- Revenus par fournisseur
- Analyse de la performance des produits
- Taux de succès et d’échec des paiements
- Retards d’expédition et efficacité des livraisons
- Tendances des ventes mensuelles
- Analyse logistique basée sur la géolocalisation (distance livraison, optimisation routes)

🛠️ Technologies utilisées

1️⃣ SGBD : Oracle Database ; C’est le moteur de base de données relationnelle. ou sont Stockés toutes mes données de manière sécurisée et structurée.

2️⃣ Modélisation : JMerise ou Looping (MCD/MLD)
MCD (Modèle Conceptuel des Données) : pour représenter les entités, relations et cardinalités; 
MLD (Modèle Logique des Données) : traduction du MCD en tables et relations SQL; 
JMerise / Looping : outils pour créer visuellement ton MCD/MLD.

3️⃣ Générer des fichiers de données aléatoires : Jupyter Notebook (Python)
4️⃣ Développement SQL : SQL Developer
Tu peux créer tes tables, insérer les données, faire des jointures, vues, procédures stockées;
5️⃣ Analyse et tableaux de bord : Power BI
Crée des rapports et dashboards interactifs pour visualiser tes données.

📖 Objectifs du projet

- Démontrer de solides compétences en modélisation de bases de données
- Modéliser les données associées à ce processus
- Concevoir et alimenter une base de données relationnelle,
- Effectuer le nettoyage et l’intégration des données
- Développer des requêtes SQL avancées pour l’analyse
- Obtenir des insights sur les opérations et les performances e-commerce etronique
- Utiliser la géolocalisation pour améliorer l’efficacité logistique

⚡ Comment l’utiliser

- Cloner ou télécharger ce dépôt.
- Charger les fichiers CSV dans ton  environnement de développement du language sql en utilisant les scripts SQL fournis.
- Exécuter les requêtes SQL dans ton outil pour explorer l’analyse.

📝 Remarques

- Toutes les données ont été nettoyées et validées avant le chargement
- Les requêtes sont conçues pour être évolutives sur de plus grands ensembles de données.
- Le schéma de la base de données garantit l’intégrité des données et évite les redondances.
