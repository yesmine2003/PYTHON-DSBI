# 🐍 Projet d'Apprentissage Python - Des Fondamentaux à l'Analyse de Données

## 📖 À propos du projet
Ce dépôt regroupe une collection de notebooks Jupyter documentant mon parcours d'apprentissage en Python. Ce projet a pour but d'explorer de manière pratique les structures de données, l'algorithmique de base, ainsi que les premières étapes de la manipulation de données (Data Science).

## 🚀 Compétences et concepts abordés

Le projet est structuré sous forme de "Challenges" progressifs :

### 1. Variables, Types et Opérations
*   Découverte, manipulation et vérification des différents types de variables (`int`, `float`, `str`, `bool`)[cite: 5].
*   Utilisation d'opérations mathématiques (puissance, modulo, division) et de la librairie `math` pour les calculs et arrondis (`floor`, `ceil`)[cite: 6].
*   Exploration des opérateurs de bits (bitwise)[cite: 6].

### 2. Structures de Données (Collections)
*   **Tuples :** Création, indexation, découpage (slicing) et concaténation[cite: 4]. Mise en évidence de l'immuabilité de cette structure[cite: 4, 5].
*   **Listes :** Création, ajout d'éléments (`append`), inversion d'ordre (`reverse`), gestion de listes imbriquées et calcul de sommes[cite: 5].
*   **Chaînes de caractères (Strings) :** Recombinaison de mots en phrases, nettoyage de texte et découpage (split) pour préparer l'analyse de données textuelles[cite: 6].
*   **Sets (Ensembles) :** Génération de listes aléatoires via la librairie `random`, conversion en `set` pour supprimer les doublons, et application d'opérations mathématiques sur les ensembles (union, intersection, différence, vérification de sous-ensembles)[cite: 7].
*   **Dictionnaires :** Création et accès aux données par clés uniques[cite: 5]. Algorithmes de tri avancés appliqués aux dictionnaires (tri par clés et par valeurs avec `operator.itemgetter`) pour analyser la fréquence d'apparition de mots dans une chanson[cite: 8].

### 3. Logique et Algorithmique (Conditions & Boucles)
*   Mise en place de structures conditionnelles (`if`/`elif`/`else`) et de boucles (`for`/`while`) pour la résolution de problèmes[cite: 10].
*   Exercices d'application concrets : identification de nombres divisibles par 3, conversion de noms de mois en nombre de jours, inversion de mots, et variantes de l'algorithme classique "FizzBuzz"[cite: 10].

### 4. Introduction à la Data Science (Pandas)
*   Configuration de l'environnement de travail (installation de `ydata_profiling`)[cite: 9].
*   Importation et lecture de bases de données depuis des fichiers Excel (`liquor_store_sales.xlsx`) en utilisant la librairie `pandas` (`read_excel`)[cite: 9].
*   Exploration initiale des DataFrames : visualisation des premières lignes avec `df.head()`, extraction de colonnes spécifiques et utilisation de `df.describe()` pour obtenir les statistiques descriptives[cite: 9].

## 🛠️ Technologies et Librairies Utilisées
*   **Langage :** Python 3
*   **Environnement :** Jupyter Notebook
*   **Librairies standards :** `math`, `random`, `operator`[cite: 6, 7, 8].
*   **Data Science :** `pandas`, `ydata_profiling`[cite: 9].

---
*Ce dépôt reflète mes connaissances pratiques en programmation Python et constitue une base solide pour des projets plus complexes en développement ou en Data Science.*
