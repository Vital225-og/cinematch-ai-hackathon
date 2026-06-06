\# CineMatch AI Hackathon



CineMatch AI est une application développée avec Python et Streamlit dans le cadre du premier Hackathon.



L'application permet d'analyser des données liées au cinéma, de visualiser des statistiques importantes et de proposer une interface simple pour explorer les résultats.



\## Objectif du projet



L'objectif de CineMatch AI est de fournir un tableau de bord interactif permettant de mieux comprendre les données de films à travers des analyses, des visualisations et un système de recommandation.



\## Fonctionnalités



\- Dashboard interactif avec Streamlit

\- Analyse des données de films

\- Visualisation des statistiques principales

\- Prétraitement des données

\- Système de recommandation

\- Interface administrateur via `web\_admin.py`

\- Organisation du projet en plusieurs fichiers Python



\## Technologies utilisées



\- Python

\- Streamlit

\- Pandas

\- NumPy

\- Matplotlib

\- Plotly

\- Git

\- GitHub



\## Structure du projet



```text

cinematch-ai-hackathon/

│

├── analytics.py

├── dashboard.py

├── data\_generator.py

├── main.py

├── preprocessing.py

├── recommender.py

├── web\_admin.py

├── .gitignore

└── README.md

```



\## Description des fichiers



\- `web\_admin.py` : fichier principal pour lancer l'application Streamlit.

\- `analytics.py` : contient les fonctions liées aux analyses.

\- `dashboard.py` : contient les éléments du tableau de bord.

\- `data\_generator.py` : permet de générer ou préparer les données utilisées dans le projet.

\- `preprocessing.py` : contient les fonctions de nettoyage et de préparation des données.

\- `recommender.py` : contient la logique du système de recommandation.

\- `main.py` : fichier principal complémentaire du projet.



\## Installation



Clonez le dépôt GitHub :



```bash

git clone https://github.com/Vital225-og/cinematch-ai-hackathon.git

```



Entrez dans le dossier du projet :



```bash

cd cinematch-ai-hackathon

```



Installez les dépendances nécessaires :



```bash

pip install streamlit pandas numpy matplotlib plotly

```



\## Lancer l'application



Pour lancer l'application Streamlit, utilisez la commande suivante :



```bash

streamlit run web\_admin.py

```



L'application sera ensuite disponible dans le navigateur à l'adresse :



```text

http://localhost:8501

```



\## Branches GitHub



Le projet utilise deux branches principales :



\- `main` : branche principale contenant la version stable du projet.

\- `dev` : branche utilisée pour le développement et les tests.



\## Dépôt GitHub



Lien du dépôt :



```text

https://github.com/Vital225-og/cinematch-ai-hackathon

```



\## Auteurs



\- Tiomitchin Vital Coulibaly

\- KOFFI Kouamé Levi



\## Contexte



Ce projet a été réalisé dans le cadre du Hackathon organisé pendant la formation Developers Institute.



\## Statut du projet



Projet terminé et prêt pour la soumission.

