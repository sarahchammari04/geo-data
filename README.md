# geo-data
Dans ce projet il nous est demandé de repérer les meilleurs lieux pour implanté des boutiques Action : 


Dans le cadre de cette analyse, je cible principalement les catégories socio-professionnelles
défavorisées (CSP-) pour des enseignes comme Noz et Action. Ces magasins se spécialisent
dans la vente de produits à prix réduits, ce qui les rend particulièrement attractifs pour une
clientèle soucieuse de son budget.
L'objectif est donc d'identifier les zones où la demande pour ce type de commerces est la plus
forte, en prenant en compte des indicateurs socio-économiques.
Variables sélectionnées
Pour caractériser cette population cible, j’ai choisi les variables suivantes :
● Le nombre de personnes non diplômées : Un faible niveau de diplôme est souvent
corrélé à une insertion professionnelle plus précaire et à des revenus plus faibles, ce qui
peut influencer les habitudes de consommation.
● Le nombre de ménages avec enfants : Les familles, en particulier celles avec un
budget serré, cherchent des solutions économiques pour leurs achats du quotidien.
● Le nombre de CSP- (ouvriers, employés peu qualifiés, etc.) : Ces catégories sont
souvent les plus concernées par la recherche de bons plans et d’enseignes à bas prix.
● Le nombre de personnes vivant dans les HLM : Une forte densité d’occupation peut
être un indicateur de précarité, car elle traduit parfois des difficultés à accéder à un
logement plus spacieux.

Après avoir sélectionné mes variables, j’ai calculé la part de chaque variable par rapport à la
population totale afin d’obtenir un indice pour chacune d’elles.
Ensuite, j’ai déterminé trois quartiles pour chaque variable. Ces quartiles servent de seuils pour
la classification des valeurs et permettent d'attribuer un score à chaque variables.
Le calcul du score se fait de la manière suivante :
● Si l’indice est inférieur au premier quartile, le score attribué est 1.
● Si l’indice est compris entre le premier et le deuxième quartile, le score est 2.
● Si l’indice est compris entre le deuxième et le troisième quartile, le score est 3.
● Si l’indice est supérieur au troisième quartile, le score est 4.
Ainsi, plus le score est élevé, plus la population étudiée correspond à notre cible.
Enfin, pour obtenir un score total, j’ai additionné les scores obtenus pour chaque variable sur
l’ensemble des observations.


Pour aller plus loin on pourrais réaliser des visualisations à partir de ce tableau.
