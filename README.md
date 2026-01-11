📦 Projet Base de données d'un site e-commerce en france avec analyse décisionnelle.
Ce projet présente la conception et l’analyse d’une base de données relationnelle pour une plateforme e-commerce en France, en utilisant Python (Jupyter Notebook), Oracle SQL Developer, JMerise/Looping, Power BI et Git/GitHub.
Il couvre la modélisation de la base, l’intégration des données, la génération de tableaux de bord et l’analyse décisionnelle, permettant de produire des indicateurs clés et insights sur la performance commerciale et opérationnelle.

Le projet démontre des compétences en Python, SQL, modélisation de données et visualisation, avec un focus sur la prise de décision basée sur les données dans un contexte e-commerce.

🗂️ Database Structure
The database consists of 8 core entities:

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
| Geolocalisation   | Contient les coordonnées géographiques des clients 
                     et des fournisseurs pour optimiser la livraison et 
                     l’analyse logistique                               |

🧱 Main Steps of the Project
1️⃣ Database Design
Identified entities and relationships
Created a complete Entity-Relationship Diagram (ERD)
Defined primary keys (PK) and foreign keys (FK)
2️⃣ Database Creation (PostgreSQL)
Built all tables using SQL DDL
Added constraints: PK, FK, CHECK, UNIQUE
3️⃣ SQL Analysis & Business Queries
Performed advanced queries to extract key insights:

Best-selling product category
Overall delivery rate
Top customers by spending
Revenue per supplier
Product performance analysis
Payment success vs. failure rates
Shipment delays & delivery efficiency
Monthly sales trends
These queries mimic real-world e-commerce analytics and help in decision-making.

🛠️ Technologies Used
PostgreSQL / pgAdmin 4
SQL: DDL, DML, CTEs, JOINs, Aggregations
📖 Project Goals
Demonstrate strong database modeling skills
Perform data cleaning and integration
Develop advanced SQL queries for analytics
Gain insights into e-commerce operations and performance metrics
⚡ How to Use
Clone or download this repository.
Load the CSV data into PostgreSQL using the provided SQL scripts.
Execute the SQL queries in pgAdmin to explore analytics.
📝 Notes
All data has been cleaned and validated before loading.
Queries are designed to be scalable for larger datasets.
Database schema ensures data integrity and avoids redundancy.
