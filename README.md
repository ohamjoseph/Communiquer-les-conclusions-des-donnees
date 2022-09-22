# (Explporation des données du système  Ford Gobike)
## by (your name here)


## Dataset

> Cet ensemble de données comprend des informations sur 174952 trajets individuels ainsi que la durée de chaque trajet effectué dans un système de partage de vélos couvrant la grande région de la baie de San Francisco. L'ensemble contient aussi d'autres caractéristiques que l'âge, le status des clients, les dates de début et de fin de trajets et d'autres informations.

## Summary of Findings

> Au cours de l'exploration, j'ai constaté que la relation entre l'âge et la durée n'était pas linéaire, cela était bien visible après la transformation d'échelle de l'âge et de la durée des trajets. Mais lorsqu'on ajoutait les autres caractéristiques c’est-à-dire les heures, les jours le sexent ainsi que les type de clients, j'ai pu constater des relations assez claires. Il y a plus de trajets encours de semaine avec un pic le jeudi, mais les longs trajets sont effectués pendant les week-ends trajets.
Les longs trajets sont effectués généralement par des femmes et personnes moins âgées. Les plus âgés sont plus les hommes et effectuent de court trajet. Cela a été plus clair après avoir divisé l'ensemble de données selon deux catégories d'âges.  On peut tenir l'hysope que les jeunes utilisent le système pour les loisirs et les personnes pour le travail qui expliquerait que le nombre de trajets est plus dense en début et fin de journée. Ce qui correspond à l'ouverture et fermeture des services.

> Il avait d'autres caractéristiques telles que les informations de localisation. Ils avaient une forte corrélation entre ces caractéristiques, mais elles avaient une corrélation faible avec la durée. En plus, du fait que les données concernent une même région, je n'ai pas plus exploré ses caractéristiques de localisation.


## Key Insights for Presentation

Pour la présentation, je me concentre uniquement sur l'influence du sexe, l'âge, des jours, des heures et le type de clients sur la durée des trajets et laisse de côté la plupart des dérivations intermédiaires. Je commence par introduire la variable
variable de durée, suivie par le modèle de distribution des âges, puis je trace le diagramme de dispersion transformé.

Ensuite, j'introduis chacune des variables catégoriels sexes, type de client, heure et jour. Pour commencer,
j'utilise les diagrammes de violon des durées par rapport aux variables catégorielles. 
Je vais pour suivre avec  les graphiques ponctuelles pour voir les différentes catégories d'âge.