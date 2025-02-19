# Titanic Dataset Visualisation

Ce projet analyse les données du Titanic pour visualiser divers aspects des passagers et leurs chances de survie.

## Contenu du dépôt

- `Titanic.ipynb` : Un notebook Jupyter contenant l'analyse des données et les visualisations.
- `titanic.csv` : Le jeu de données utilisé pour l'analyse.

## Prérequis

Assurez-vous d'avoir installé les bibliothèques suivantes :

```bash
pip install pandas numpy matplotlib seaborn
```

## Utilisation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/Labrini-Ouiam/titanic_dataset_visualisation.git
   ```
2. Ouvrez le notebook `Titanic.ipynb` avec Jupyter Notebook ou Jupyter Lab :
   ```bash
   jupyter notebook Titanic.ipynb
   ```
3. Exécutez les cellules pour voir les résultats de l'analyse.

## Fonctions principales

Le notebook inclut plusieurs fonctions pour analyser et visualiser les données :

- `load_data(filepath)`: Charge les données depuis un fichier CSV.
- `data_summary(df)`: Affiche un résumé des données, y compris les valeurs manquantes.
- `plot_survival_by_class(df)`: Visualise le taux de survie selon la classe des passagers.
- `plot_survival_by_gender(df)`: Analyse la survie en fonction du genre.
- `age_distribution(df)`: Affiche la distribution des âges des passagers.
- `correlation_heatmap(df)`: Génère une heatmap pour montrer les corrélations entre les variables.

## Auteur

- **Labrini Ouiam** - [Profil GitHub](https://github.com/Labrini-Ouiam)

