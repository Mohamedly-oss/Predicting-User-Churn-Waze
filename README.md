# Predicting-User-Churn-Waze
Analyse de la rétention des utilisateurs Waze et modélisation par régression logistique binomiale pour prédire l'attrition (churn).

# Analyse de l'attrition des utilisateurs (Waze User Churn)

## Présentation du projet
 L'objectif est de construire un modèle de régression logistique binomiale pour prédire si un utilisateur va désinstaller l'application ou cesser de l'utiliser (churn).

## Données et Méthodologie
- **Analyse Exploratoire (EDA) :** Étude des corrélations et visualisation des comportements de conduite.
- **Modélisation :** Utilisation d'un modèle de régression logistique pour identifier les facteurs clés influençant le départ des utilisateurs.
- **Outils :** Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn).

## Résultats Clés
- La variable `activity_days` (nombre de jours d'activité par mois) est le prédicteur le plus important : plus un utilisateur est actif, moins il risque de partir.
- Le modèle actuel montre un rappel (recall) faible, suggérant que des données supplémentaires sur l'interaction réelle des utilisateurs seraient nécessaires pour améliorer les prédictions.

## Contenu du dépôt
- `Waze_project.ipynb` : Notebook complet avec le code Python et les analyses.
- `Waze_executive_summary_anglais.pdf` : Résumé synthétique des résultats destiné à la direction.
