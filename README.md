## Prédiction des Pourboires des Taxis à New York

*<div align="right">
  *Par Serigne Dame LO*
</div>

# *Aperçu*

L'objectif de ce projet était de créer un modèle de forêt aléatoire pour prédire si un client laisserait un pourboire élevé ou non. Ce projet a utilisé les trajets des taxis jaunes effectués à New York en 2017. Le modèle final de forêt aléatoire a obtenu une précision de 71 % et une précision de 69 % pour déterminer quelles caractéristiques étaient les plus importantes pour distinguer les petits pourboires des gros pourboires. Selon le modèle, l'identifiant du fournisseur, le montant de la course, la durée et la distance étaient les plus influents pour déterminer un client généreux (>20 %) par rapport à un client non-généreux (<20 %).

# *Compréhension du Business*

Selon [salary.com](https://www.salary.com/), le salaire moyen d'un chauffeur de taxi à New York est d'environ 45 000 $. Ce salaire est considérablement bas par rapport à une valeur médiane de loyer de 6 500 $ par mois. Il est important de comprendre quels facteurs incitent les clients à laisser des pourboires afin d'aider les chauffeurs à obtenir un salaire décent.

# *Compréhension des Données*

Les données de la Commission des Taxis et Limousines de NYC proviennent de [NYC.gov](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). Les données comprenaient environ 23 000 trajets uniques et 18 caractéristiques. Les fonctionnalités incluaient des informations sur la durée du trajet et la destination, le fournisseur utilisé, les informations sur les péages et le type de paiement. Le graphique à barres ci-dessous montre la répartition entre les clients généreux (>20 %) et les clients non-généreux dans l'ensemble de données.

![data_undestand.png](https://github.com/losdame/Pr-diction-des-Pourboires-des-Taxis-New-York/blob/main/data_undestand.png?raw=true)

En lien avec cela, une caractéristique a été conçue pour représenter si un trajet a été effectué pendant les heures de pointe ou non. Plusieurs colonnes redondantes ont été supprimées et reformattées dans le bon type de données.

# *Modélisation et Évaluation*

Un modèle de forêt aléatoire composé de 100 arbres de décision a été utilisé pour déterminer l'importance des caractéristiques concernant ceux qui laisseraient un pourboire généreux ou non. Le graphique ci-dessous montre que la durée du trajet, la distance et le coût de la course étaient les trois facteurs les plus importants pour déterminer un client généreux par rapport à un client non-généreux. Le modèle global a obtenu une précision de 71 % et une précision de 69 %.

![importance_feature.png](https://github.com/losdame/Pr-diction-des-Pourboires-des-Taxis-New-York/blob/main/importance_feature.png?raw=true)

# *Conclusion*

Ce modèle peut aider les chauffeurs de taxi à savoir s'ils seront généreusement pourboisés ou non; cependant, l'utilisation d'un modèle paramétrique pour déterminer comment chaque variable influencera le montant réel du pourboire serait bénéfique. À l'avenir, l'ajout d'informations sur le comportement de pourboire passé d'un client pourrait également être utile pour aider les parties prenantes à résoudre leur problème commercial.

