# Projet-BI-1 : Analyse des Tendances du Secteur de la Data

# 1.Contexte du Projet
Ce projet analyse une enquête menée auprès de professionnels de la data (Data Scientists, Analystes, Ingénieurs, etc.). L'objectif est d’identifier les tendances du secteur, les compétences les plus demandées, les niveaux de salaire, ainsi que le bien-être des travailleurs.
# 2.Objectifs
- Identifier les compétences et technologies les plus prisées
- Analyser la satisfaction des professionnels selon plusieurs critères
- Étudier la distribution des salaires en fonction des rôles et de l’expérience
- Construire un tableau de bord interactif avec Power BI
# 3.Étapes de la conception du Dashboard
# a.Préparation des Données
- Renommage des variables pour une meilleure lisibilité
- Suppression des colonnes inutiles ("Browser", "OS", "City", "Country", "Referrer")
- Traitement des valeurs manquantes :
  o	Remplacement des valeurs manquantes par "Not specified" pour certaines variables
  o	Suppression ou reclassification des réponses "Other"
# b.Création des KPI & Visualisations
# •	KPI 1 : Salaire moyen par rôle
    o	Variables utilisées : Current Role Title, Current Yearly Salary
    o	Visualisation : Graphique en barres pour comparer les salaires moyens
    o	Approche : Conversion des salaires textuels en valeurs numériques moyennes
# •	KPI 2 : Répartition des professionnels de la data par secteur d’activité
    o	Variables utilisées : Sector of Activity
    o	Visualisation : Diagramme circulaire ou histogramme
    o	Intérêt : Identifier les industries les plus attractives pour les professionnels de la data
# •	KPI 3 : Satisfaction moyenne des professionnels selon leur rôle
    o	Variables utilisées : Current Role Title, Satisfaction with current position
    o	Visualisation : Graphique en barres horizontales
    o	Intérêt : Analyser le bien-être professionnel selon le poste occupé
# •	KPI 4 : Impact du changement de carrière sur la satisfaction professionnelle
    o	Variables utilisées : Switching Careers into Data, Satisfaction with current position
    o	Visualisation : Diagramme en barres empilées
    o	Intérêt : Comprendre si une reconversion en data science améliore le bien-être au travail
# •	KPI 5 : Corrélation entre le langage de programmation favori et le salaire moyen
    o	Variables utilisées : Favorite Programming Language, Current Yearly Salary
    o	Visualisation : Nuage de points ou boîte à moustaches
    o	Intérêt : Vérifier si certaines compétences techniques sont associées à des salaires plus élevés
# •	KPI 6 : Critères les plus importants pour un nouvel emploi
    o	Variables utilisées : Criteria for New Job
    o	Visualisation : Nuage de mots ou histogramme
    o	Intérêt : Comprendre ce que recherchent les professionnels lorsqu’ils changent d’entreprise
# 4.Résultats et Insights Clés

- Les Data Scientists ont en moyenne un salaire plus élevé que les Analystes
- Un écart significatif de satisfaction existe entre les différentes catégories de postes
- Les tendances salariales varient fortement selon les pays

# 5.Structure du Projet
- Projet1.pbix → Fichier Power BI
- data/ → Contient les données sources (si possible)
- screenshots/ → Captures d'écran du dashboard
- README.md → Documentation du projet
# 6.Perspectives
- Amélioration des visualisations et ajout d'indicateurs avancés
- Comparaison avec des années précédentes pour détecter les tendances évolutives
- Exploration de nouvelles sources de données pour enrichir l'analyse
