# Compte rendu de la semaine 2

Bonjour , cela fait déjà 7 jours depuis le lancement de notre projet. Pour commencer en beauté, permettez-moi de partager une citation inspirante :

"Le vol est la liberté incarnée, mais sa gestion est la discipline de la précision." - William Langewiesche

Dans un registre plus concret, notre exploration du trafic aérien s'est poursuivie avec un accent particulier sur la gestion des retards. Nous avons ainsi développé des fonctions aléatoires permettant de prédire et de générer des données. Celles-ci nous aideront à avancer dans notre analyse des tendances des voyages, tout en nous permettant de prévoir les retards en fonction de ces tendances saisonnières.

La fonction ci-dessous "analyse_tendance_voyages", génère aléatoirement une tendance (en hausse, en baisse ou stable) pour les voyages en se basant sur les données fournies.


    tendances = ["en hausse", "en baisse", "stable"]
    tendance = random.choice(tendances)
    return tendance


Cette fonction Python, "predire_retards_par_saisons", modifie aléatoirement les retards initiaux pour chaque saison, puis prédit les retards ajustés en fonction de ces modifications. Elle illustre ensuite ces prédictions à l'aide d'un diagramme à barres, représentant les variations des retards selon les saisons.

![image](https://github.com/are-dynamic-2024-g3/Modelisation-dynamique-du-trafic-aerien.github.io/blob/main/graph.jpeg)
