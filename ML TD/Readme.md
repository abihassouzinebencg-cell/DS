# Analyse des Données FIFA 21 : Joueurs et Performances

L’analyse des données dans le football professionnel est une discipline émergente qui transforme profondément la manière dont les clubs, entraîneurs, joueurs et autres acteurs prennent leurs décisions. Au-delà de la simple observation visuelle du jeu, cette approche repose sur la collecte, le traitement et l’interprétation de données quantitatives et qualitatives liées aux performances sportives. L’analyse vise à fournir des informations objectives et précises qui peuvent influencer les choix tactiques, améliorer la préparation physique des joueurs et optimiser la gestion globale de l’équipe.

Dans un environnement où la marge entre la victoire et la défaite est souvent très fine, l’analyse des données offre un avantage compétitif en rendant possible une prise de décision fondée sur des preuves solides plutôt que sur des impressions subjectives. De plus, cette démarche permet un gain de temps important dans le travail des analystes grâce à l’automatisation des processus et à l’utilisation d’outils technologiques avancés. Elle s’inscrit aujourd’hui comme un élément incontournable à tous les niveaux du football professionnel, participatif à la fois à la performance sportive et à la stratégie globale des clubs.

---

## Analyse exploratoire des données

L’examen initial du dataset met en lumière une distribution majoritaire des notes globales autour de 65-75, avec des variations selon l’âge, la position et les attributs physiques et techniques. Cette diversité permet d’explorer les facteurs influençant la performance globale des joueurs.

---

## Justification des choix techniques

La régression linéaire a été utilisée pour expliquer la variation continue de la note globale en fonction d’attributs mesurables, tandis que la régression logistique a servi à classifier les joueurs selon une catégorie de performance binaire. Ces modèles sont simples, efficaces et offrent une bonne interprétabilité pour le contexte sportif.

---

## Graphes de la régression linéaire et logistique

![Régression linéaire](linear_regression.png)  
*Graphique : Régression linéaire illustrant la relation entre une variable indépendante et la note des joueurs, avec la ligne de tendance.*

![Régression logistique](logistic_regression.png)  
*Graphique : Courbe sigmoïde de la régression logistique montrant la probabilité de classification selon la variable indépendante.*

---

## Présentation des métriques et analyse des erreurs du modèle

- **Régression linéaire** : Le coefficient de détermination \(R^2\) et la MSE montrent une bonne capacité à capturer les tendances globales.
- **Régression logistique** : La précision, le rappel et l’AUC révèlent une classification correcte avec quelques erreurs dues aux profils atypiques.

L’erreur s’explique partiellement par la complexité des performances footballistiques qui ne sont pas totalement captées par ces modèles linéaires simples.

---

## Conclusion : Limites et pistes d’amélioration

Les modèles linéaires sont limités face à la complexité des dynamiques sportives. L’utilisation de modèles plus avancés (forêts aléatoires, boosting, deep learning) serait une piste importante à explorer. Ajouter des données contextuelles et temporelles améliorerait également la richesse des analyses. Enfin, un suivi continu et une mise à jour régulière des modèles permettraient d’adapter la prédiction aux évolutions du football professionnel.

---

Ce rapport présente une vue claire et visuelle de l’analyse des performances des joueurs de FIFA 21 grâce à l’intégration de modèles statistiques classiques et de leurs visualisations clés.

