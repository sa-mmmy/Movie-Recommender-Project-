
# Movie Recommender System

Un système de recommandation de films combinant le Collaborative Filtering (CF) et le Content-Based Filtering afin de proposer des recommandations personnalisées et pertinentes.
Le projet intègre également des améliorations futures telles qu’une interface interactive avec Streamlit et une meilleure représentation sémantique du texte via Word2Vec ou LSTM.

## Fonctionnalités

Recommandation de films basée sur le Collaborative Filtering

Recommandation basée sur le contenu (genres, descriptions, mots-clés)

Approche hybride combinant CF et content-based

Système extensible et modulaire

# Approches utilisées

 ## Collaborative Filtering

Analyse des interactions utilisateurs-films

Recommandations basées sur la similarité entre utilisateurs ou items

Gestion du cold start partiellement résolue via le content-based

#" Content-Based Filtering

Analyse des métadonnées des films

Vectorisation des descriptions et genres

Calcul de similarité entre films

# Améliorations prévues

Interface utilisateur avec Streamlit

Recherche de films

Affichage interactif des recommandations

Amélioration de la tokenisation et de la compréhension sémantique

Word2Vec pour des embeddings plus riches

LSTM pour capturer le contexte des descriptions de films

# Optimisation des performances et de la précision des recommandations

Stack technique

Python

Pandas / NumPy

Scikit-learn

NLP (TF-IDF, Word2Vec, LSTM)

Streamlit (interface utilisateur – à venir)

# Installation

## Cloner le dépôt :

```sql
git clone https://github.com/votre-utilisateur/movie-recommender-system.git
cd movie-recommender-system
````


## Installer les dépendances :

pip install -r requirements.txt


# Lancer le projet :
```sql
python recommender.py

```


# (Optionnel – Interface Streamlit)
```sql
streamlit run app.py
```

Objectifs du projet

Comprendre et implémenter différents types de systèmes de recommandation

Combiner plusieurs approches pour améliorer la pertinence

Explorer des techniques avancées de NLP et de deep learning
