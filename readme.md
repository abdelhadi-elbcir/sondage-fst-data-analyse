# Projet analyse de données : Sondage FST

## Réalisé par :
- EL BCIR Abdelhadi : IRISI2
- AHTOUTE Wissam : IFA2

## Description du projet

Ce projet vise à analyser les données issues d'un sondage réalisé à la FST. L'objectif est de comprendre les tendances et les relations entre différentes variables telles que le sexe, la formation, et les pratiques mises en œuvre par les étudiants.

## Importation des librairies

Pour ce projet, nous avons utilisé les librairies suivantes :
- `numpy`
- `pandas`
- `sklearn.preprocessing`
- `datetime`
- `matplotlib`
- `pandas_datareader`

## Importation du dataset

Les données ont été importées à partir d'un fichier Excel nommé `FST Sondage.xlsx`. 

## Analyse de fréquence

### Répartition Masculin-Féminin

Nous avons analysé la répartition des sexes dans le sondage et visualisé les résultats à l'aide d'un graphique en barres.

### Répartition de la formation

Nous avons également analysé la répartition des formations suivies par les participants et visualisé les résultats à l'aide d'un graphique en camembert.

## Traitement de personnalité

Nous avons ajouté des colonnes pour le score et la personnalité des participants en fonction de leurs réponses à certaines questions du sondage.

## Les tests 2D

### Analyse de la relation entre formation et parcours après diplôme

Nous avons utilisé une table de contingence pour analyser la relation entre la formation suivie et le parcours après l'obtention du diplôme.

### Analyse de la relation entre sexe et présence

Une table de contingence a été utilisée pour analyser la relation entre le sexe des participants et leur présence en cours.

### Analyse de la relation entre personnalité et formation

Nous avons utilisé une table de contingence et un test du chi-deux pour analyser la relation entre la personnalité des participants et leur formation.

## Analyse des correspondances multiples (ACM)

Nous avons réalisé une analyse des correspondances multiples (ACM) en utilisant les variables suivantes :
- Sexe
- Formation
- Pratiques mises en œuvre (e.g., noter les cours, poser des questions, etc.)
- Parcours après diplôme
- Entourage (âge et niveau)
- Intégration

### Résultats de l'ACM

Les résultats de l'ACM ont été visualisés à l'aide de graphiques représentant les coordonnées principales des lignes et des colonnes.

## K-means

Nous avons appliqué l'algorithme de classification K-means sur les coordonnées individuelles des observations issues de l'ACM pour identifier des clusters parmi les participants.

## Conclusion

Ce projet a permis de réaliser une analyse approfondie des données du sondage de la FST, en mettant en lumière des tendances et des relations importantes entre différentes variables. Les résultats obtenus peuvent être utilisés pour mieux comprendre les comportements et les attentes des étudiants de la FST.

## Instructions pour l'exécution du projet

1. Assurez-vous d'avoir installé toutes les librairies nécessaires en exécutant :
   ```bash
   pip install numpy pandas scikit-learn matplotlib pandas_datareader prince seaborn
