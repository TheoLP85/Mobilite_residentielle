# Etude de la mobilité résidentielle par département en France métropolitaine entre 2016 et 2018

L'objectif de ce projet est d'étudier les causes de la mobilité résidentielle en France métropolitaine. Pour cela nous utilisons plusieurs bases de données sur des caractéristiques socio-économiques (taux de chômage, infrastructures, salaire) et géographiques(localisation) afin d'expliquer l'attractivité d'un département vis-à-vis d'un autre.

Nous avons donc mis à notre disposition en provenance l'INSEE :
- les données de l'enquête logement de l'INSEE réalisé grâce aux données du recenssement de 2018, 2013 et 2008
- les données de la Base Permanente des Equipements (BPE) en 2015 de l'INSEE
- les données du chômage par département de l'INSEE
- les données des salaires qui proviennent des déclarations annuelles de données sociales (DADS) et déclarations sociales nominatives (DSN) de l'INSEE

A cela nous avons créé une base sur deux caractéristiques géographiques des départements à savoir des indicatrices sur le fait que le département est situé sur le littoral ou sur la frontière avec un autre un autre pays.

Dans l'ordre, à faire fonctionner : 
1) Le Notebook Donnees_logement.ipynb traite les données sur le logement (nettoyage, agrégation), exporte deux base de données utiles pour les autres Notebooks et fait quelques statistiques descriptives sur celles-ci.
2) Le Notebok Donnees_regresseurs.ipynd agrège en une base de données toutes les variables intéressantes pour étudier la mobilité (equipements, salaire moyen, taux de chômage, département situé sur le littoral ou à la frontière d'un pays européen)
3) Le notebook "Statistiques descriptives et régressions" utilisent les données traitées pour réaliser des statistiques descriptives et des régressions permettant d'évaluer les effets du marché du travail (chômage et salaires), des infrastructures et de la situation géographique sur l'attractivité des départements pour les ménages.
