# ProLigue Data Analysis — SQL & Power BI

Français | English

---

## Français

### Présentation

Ce projet consiste à concevoir une plateforme de données autour de la **ProLigue**, la 2ᵉ division française de handball.

L'objectif est de structurer les données sportives afin de permettre leur exploitation et leur analyse à travers **SQL et Power BI**.

Le projet couvre l'ensemble du processus, de la **modélisation de la base de données** jusqu'à la **visualisation des performances**.

Les données utilisées dans ce projet sont récupérées depuis le **site officiel de la Ligue Nationale de Handball (LNH)**.

### Objectifs

- Structurer les données de la ProLigue dans une base relationnelle
- Gérer les clubs, joueurs, matchs, salles, saisons et statistiques
- Automatiser la mise à jour du classement
- Analyser les performances individuelles et collectives
- Créer des dashboards interactifs avec Power BI

### Base de données

La base de données est composée de **8 tables normalisées**, permettant de représenter les principales entités du championnat :

- Clubs
- Joueurs
- Salles
- Saisons
- Matchs
- Contrat
- Statistiques joueurs
- Classement
- Relations entre les différentes entités

Un **trigger SQL** permet notamment de mettre automatiquement à jour le classement lors de l'ajout d'un nouveau match.

### Power BI

Les données sont ensuite exploitées dans Power BI à travers plusieurs pages :

- **Accueil** - principaux KPIs
- **Clubs & Salles** - localisation et informations
- **Joueurs** — profils et caractéristiques
- **Matchs** - résultats et calendrier
- **Classement** - classement du championnat
- **Statistiques** - performances individuelles

### Technologies

- SQL
- Oracle Database
- Oracle SQL Developer
- Power BI
- Data Modeling
- Data Visualization

### Compétences mises en œuvre

**Data Engineering**
- Modélisation relationnelle
- Normalisation
- Contraintes et relations
- Triggers SQL
- Création de vues

**Data Analysis & BI**
- KPIs
- Analyse de performances
- Data visualization
- Dashboards interactifs
- Exploration de données sportives

---

# English

### Overview

This project focuses on building a data platform around **ProLigue**, the second division of French handball.

The goal is to structure sports data and make it exploitable through **SQL and Power BI**.

The project covers the complete workflow, from **database design and data modeling** to **performance analysis and visualization**.

The data used in this project is collected from the **official website of the French Handball League (LNH)**.

### Objectives

- Structure ProLigue data in a relational database
- Manage clubs, players, matches, venues, seasons and statistics
- Automate league standings updates
- Analyze individual and team performances
- Build interactive Power BI dashboards

### Database

The database consists of **8 normalized tables** representing the main entities of the championship:

- Clubs
- Players
- Venues
- Seasons
- Matches
- Player statistics
- League standings
- Relationships between entities

A **SQL trigger** automatically updates the league standings when a new match is inserted.

### Power BI

The data is explored through several Power BI dashboard pages:

- **Home** — main KPIs
- **Clubs & Venues** — locations and information
- **Players** — player profiles and characteristics
- **Matches** — results and fixtures
- **Standings** — league table
- **Statistics** — individual performances

### Technologies

- SQL
- Oracle Database
- Oracle SQL Developer
- Power BI
- Data Modeling
- Data Visualization

### Skills Demonstrated

**Data Engineering**
- Relational database design
- Data normalization
- Constraints and relationships
- SQL triggers
- SQL views

**Data Analysis & BI**
- KPI development
- Performance analysis
- Data visualization
- Interactive dashboards
- Sports data analysis

---

## Project Structure

```text
ProLigue/
│
├── 📂 Documentation/
│   ├── Specifications.pdf
│   ├── MCD Proligue.jpg
│   └── MLD Proligue.pdf
│
├── 📂 SQL/
│   ├── 01_creation_table.sql
│   │ 
│   ├── 02_insertion_teams.sql
│   ├── 03_insertion_arena.sql
│   ├── 04_insertion_players.sql
│   ├── 05_insertion_season.sql
│   ├── 06_insertion_contract.sql
│   ├── 07_inserttion_matchs.sql
│   ├── 08_insertion_standings.sql
│   ├── 09_insertion_statistics.sql
│   │ 
│   ├── 10_trigger.sql
│   │ 
│   └── 11_views.sql
│
├── 📂 PowerBI/
│   └── ProLigue.pbix
│
└── README.md
