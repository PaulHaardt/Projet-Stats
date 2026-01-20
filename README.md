# Introduction

Nous avons décidé d'étudier l'existence d'un lien entre le temps d'écran moyen quotidien et la moyenne générale des élèves d'une tranche d'âge spécifique.

## Données

Les données utilisées dans cette étude proviennent d'une enquête menée auprès de 537 élèves âgés de 8 à 14 ans. Les variables collectées incluent :
- Temps d'écran moyen quotidien (en heures)
- Moyenne générale (sur 100)
- Âge
- Sexe

### Origine des données

Les données sont été collectées sur le site [disponible sur ce lien](https://figshare.com/articles/dataset/Data_for_Screentime_among_School_Children/27291969).

## Hypothèse

Nous définissons notre hypothèse nulle (H0) et notre hypothèse alternative (H1) comme suit :
- H0 : Il n'existe pas de lien significatif entre le temps d'écran moyen quotidien et la moyenne générale des élèves.
- H1 : Il existe un lien significatif entre le temps d'écran moyen quotidien et la moyenne générale des élèves.

# Tests

Pour tester notre hypothèse, nous avons utilisé les tests statistiques suivants :
1. Test de corrélation de Pearson + Spearman pour évaluer la relation linéaire entre le temps d'écran et la moyenne générale.
2. Régression linéaire pour modéliser l'impact du temps d'écran sur la moyenne générale.
3. TODO RETIRER SI NON UTILISÉ Analyse de variance (ANOVA) pour comparer les moyennes générales entre différents groupes de temps d'écran.

# Méthodologie

Il y a 3 notebooks Jupyter associés à ce projet :
- Paul.ipynb : analyse de la corrélation entre le temps d'écran et la moyenne générale.
- Corentin.ipynb : régression linéaire pour modéliser l'impact du temps d'écran sur la moyenne générale, et calculs des R² sur d'autres variables pour explorer d'autres facteurs potentiels qui impactent la performance académique.
- Charly.ipynb : TODO

Chaque notebook contient des explications détaillées sur les étapes de l'analyse, les résultats obtenus, ainsi que des visualisations pour illustrer les conclusions.

## Sources et bibliographie
- https://numiqo.fr/tutorial/pearson-correlation
- https://datascientest.com/correlations-de-pearson-et-de-spearman
- https://fr.wikipedia.org/wiki/Corr%C3%A9lation_de_Spearman
- https://pubmed.ncbi.nlm.nih.gov/40352281/
- https://www.scaswebsite.com/portfolio/scas-child-overview/
- https://pspp.benpfaff.org/ pour convertir les données SPSS en CSV.
- https://numiqo.fr/tutorial/pearson-correlation
- https://medium.com/@lamunozs/dealing-with-high-skewed-data-a-practical-guide-part-iii-19fc38a10a7c pour corriger la skewness des données.

# Résultats

Les résultats complets de l'analyse sont disponibles dans les notebooks Jupyter associés. Ce que l'on peut retenir de chaque analyse est résumé ci-dessous :
- Paul.ipynb : Il existe une corrélation négative significative entre le temps d'écran et la moyenne générale des élèves. Le test de Spearman est plus approprié que celui de Pearson en raison de la non-normalité des données.

    **Donc, H0 est rejetée, on ne peut pas affirmer qu'il n'y a pas de lien entre le temps d'écran et la moyenne générale des élèves.**
- Corentin.ipynb : TODO
- Charly.ipynb : TODO