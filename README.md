# HR_Performance_Analysis
Analyse des performances des employés (Python + Pandas)
#  Analyse de la performance des employés

Ce projet explore un jeu de données RH avec l’objectif de :
- Étudier la répartition des scores de performance
- Identifier les écarts et les comportements atypiques (outliers)
- Trouver des facteurs liés à l’amélioration de la performance

---

##  Objectif métier

L’entreprise souhaite :
- Comprendre les écarts de performance entre employés
- Détecter les outliers (absences, projets spéciaux…)
- Trouver des leviers d’action pour optimiser la productivité

---

##  Méthodologie utilisée

- Nettoyage et exploration du dataset avec `pandas`
- Visualisation des données avec `matplotlib` et `seaborn`
- Analyse statistique descriptive (moyenne, écart-type, IQR…)
- Détection des outliers (méthode 1.5 * IQR)
- Visualisations croisées entre variables

---

##  Résultats clés

- Les scores de performance sont très concentrés autour de **"Fully Meets"**
- Le nombre d’**absences seul n’explique pas la performance**
- Les employés impliqués dans **plus de projets spéciaux sont souvent plus satisfaits**
- Les collaborateurs peu sollicités (projets = 0) peuvent être moins engagés

---

##  Ce que j’ai appris

- Manipuler un jeu de données RH réaliste
- Détecter et visualiser des outliers
- Identifier des liens entre variables (absences, satisfaction, performance)
- Présenter une analyse métier claire avec des insights utiles

---

##  Fichiers du projet

- `HR_Performance_Analysis.ipynb` → notebook principal
- `HRDataset_v14.csv` (⚠️ données anonymisées si présentes)

---

##  À suivre

- Ajouter une modélisation prédictive (prédire le score de performance)
- Créer un tableau de bord interactif (Streamlit ou Dash)
