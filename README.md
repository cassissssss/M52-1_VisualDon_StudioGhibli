# README - Données sur le Studio Ghibli

## Contexte

### Kaggle - Données sur les films  
- **Auteur.trice** : Shruthi (Màj par Priyanka Panga)  
- **Contexte** : Projet personnel d'analyse  
- **Lien** : [Studio Ghibli Films Dataset](https://www.kaggle.com/datasets/priyankapanga/studio-ghibli-films-dataset)  

### GitHub - Données sur les genres et budgets  
- **Auteur.trice** : phelpsbp  
- **Contexte** : Projet d'analyse de données  
- **Lien** : [Studio Ghibli Genre Popularity Analysis](https://github.com/phelpsbp/Studio-Ghibli-Genre-Popularity-Analysis/blob/main/Studio%20Ghibli%20Genre%20Popularity.ipynb)  

### Wiki Ghibli - Encyclopédie sur le Studio  
- **Auteur.trice** : Communauté  
- **Contexte** : Projet informatif  
- **Lien** : [Wiki Studio Ghibli](https://ghibli.fandom.com/fr/wiki/Wiki_Studio_Ghibli)  

### API Studio Ghibli - Référence films, personnages, lieux, espèces, véhicules  
- **Auteur.trice** : Fan-made  
- **Contexte** : Projet pour aider les utilisateurs.trices à explorer les ressources  
- **Liens** :  
  - [Ghibli API](https://ghibliapi.vercel.app/)  
  - [Ghibli.rest API](https://ghibli.rest/docs/#/)  

### Base de données des lieux inspirants (en cours de création)  
- **Auteur.trice** : AMPLITUDES  
- **Contexte** : Répertorier les inspirations des films pour voyager  
- **Lien** : [10 lieux ayant inspiré le Studio Ghibli](https://www.amplitudes.com/blog/10-lieux-ayant-inspire-le-studio-ghibli-et-miyazaki/)  

### Historique rapide du Studio Ghibli  
- **Auteur.trice** : Wikipedia  
- **Lien** : [Wikipedia - Studio Ghibli](https://fr.wikipedia.org/wiki/Studio_Ghibli)  

---

## Description des Données

### Kaggle – Données sur les films  
- **Format** : CSV  
- **Attributs** :  
  - `title` (str) → Titre du film  
  - `original_title` (str) → Titre original en japonais  
  - `director` (str) → Réalisateur  
  - `producer` (str) → Producteur  
  - `release_date` (int) → Année de sortie  
  - `running_time` (int) → Durée en minutes  
  - `rt_score` (int) → Score Rotten Tomatoes  
  - `description` (str) → Résumé du film  
- **Types de données** :  
  - Chaîne de caractères (str) pour les noms, titres et descriptions  
  - Entier (int) pour l'année, la durée et le score  

### GitHub – Analyse des genres et budgets  
- **Format** : Jupyter Notebook (Python, CSV)  
- **Attributs (issus de l’analyse)** :  
  - `title` (str) → Nom du film  
  - `genre` (str) → Genre principal du film  
  - `budget` (int/float) → Budget du film (en yen ou dollars)  
  - `box_office` (int/float) → Revenus générés  
  - `audience_score` (int) → Score donné par le public  
- **Types de données** :  
  - Chaîne de caractères (str) pour les titres et genres  
  - Numérique (int/float) pour les budgets et revenus  

### API Studio Ghibli (GhibliAPI et Ghibli.rest)  
- **Format** : JSON  
- **Exemple de structure pour un film** :  
  ```json  
  {  
    "id": "2baf70d1-42bb-4437-b551-e5fed5a87abe",  
    "title": "Le Château dans le ciel",  
    "original_title": "天空の城ラピュタ",  
    "description": "Un jeune garçon et une fille...",  
    "director": "Hayao Miyazaki",  
    "producer": "Isao Takahata",  
    "release_date": "1986",  
    "running_time": "124",  
    "rt_score": "95"  
  }  
  ```  
- **Autres catégories disponibles dans l’API** :  
  - **Personnages (`people/`)** : nom, âge, genre, affiliation  
  - **Lieux (`locations/`)** : nom, climat, surface  
  - **Espèces (`species/`)** : nom, classification  
  - **Véhicules (`vehicles/`)** : modèle, pilote  

### Wiki Ghibli – Structure informelle  
- **Format** : Texte structuré en HTML (wiki)  
- **Attributs (varient selon les pages)** :  
  - `title` → Nom du film, personnage ou lieu  
  - `summary` → Résumé de l’œuvre ou du sujet  
  - `appearances` → Liste des films où apparaît un personnage  
  - `background` → Détails historiques et inspirations  

### Base de données des lieux inspirants (à créer)  
- **Format envisagé** : CSV ou JSON  
- **Attributs possibles** :  
  - `place_name` (str) → Nom du lieu  
  - `country` (str) → Pays où il se situe  
  - `film_reference` (str) → Film inspiré par ce lieu  
  - `latitude / longitude` (float) → Coordonnées GPS  

---

## But du Projet  
L'objectif est de faire découvrir l'univers du Studio Ghibli via le **story scrolling**, avec la possibilité d'interagir :  
- Une **chronologie des films** pour en apprendre plus sur les films d'animation.  
- Une **carte interactive** des lieux qui ont inspiré les différents films.  
- Des **anecdotes et données précises**, par exemple sur la place des femmes dans les studios Ghibli.  
- Une analyse des **types de personnages**, des genres des films, de la musique et des images.  
- Des statistiques sur les **classements et budgets** des films.  

## Références  
Les données sont principalement destinées aux fans et aux chercheurs intéressés par l’univers Ghibli. Elles sont utilisées par des plateformes comme IMDb, des chercheurs en cinéma, et des créateurs de contenu sur YouTube.  


