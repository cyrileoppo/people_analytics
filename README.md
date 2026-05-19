# people_analytics

Notebook principal : `/home/runner/work/people_analytics/people_analytics/people_analytics_projet.ipynb`

## Structure
1. **Partie 1 — EDA** : qualité des données, distributions, corrélations, facteurs liés à l'attrition.
2. **Partie 2 — KPI & Analyse RH** : turnover, management/culture, burn-out/bore-out, équité.
3. **Partie 3 — Machine Learning** : pipeline robuste, gestion du déséquilibre (class_weight vs SMOTE), comparaison de modèles, interprétabilité.

## Principaux constats
- Attrition fortement déséquilibrée (~2.6%), ce qui rend l'accuracy seule insuffisante.
- Les dimensions management, sécurité psychologique et charge de travail sont des leviers majeurs de prévention.
- Le modèle est destiné à l'aide à la décision collective, avec garde-fous éthiques (humain dans la boucle).
