# Qu'y a-t'il dans ce donjon ?

## Notions abordées
Cette activité a pour but de faire découvrir les algorithmes de parcours de graphes en largeur et en profondeur.
Elle peu être utilisé comme première approche pour les graphes et/ou les algorithmes.

## Public
Cette activité nécessite/développe un certain pouvoir d'abstraction.
Les élèves devront incarner des personnages et s'imaginer à leurs places.

Cette activité a été testée à distance dans un cadre de confinement auprès d'élèves de Primaire (CM2) et Collèges (5ème), ainsi qu'auprès du public cible : des Terminales S n'ayant pas encore étudié les graphes et les algorithmes de parcours.

## Materiel
- Des feuilles
- Un stylo
- Un jeton
- Plusieurs graphes planaires (dont les arêtes ne se croisent pas). Vous pourrez trouver des graphes de différentes difficultées ici ([Facile](https://github.com/TabaryM/Mediation_Graphes/blob/master/DonjonsSimple/donjons_faciles_tous.pdf),
[Moyen](https://github.com/TabaryM/Mediation_Graphes/blob/master/DonjonsMoyens/donjons_moyen_tous.pdf),
[Difficiles](https://github.com/TabaryM/Mediation_Graphes/blob/master/DonjonsDifficiles/donjons_difficiles_tous.pdf))

## Principe
Cette activité s'inspire de jeux de rôle du genre [Dungeon Crawler](https://fr.wikipedia.org/wiki/Dungeon_crawler), où le joueur doit explorer et cartographier son environnement.<br>
Cette activité va donc se faire par groupes de deux élèves, l'un devant incarner l'Aventurier, l'autre le Maître du Jeu. Les élèves changeront de rôles au cours de l'activité.

L'objectif de l'aventurier est de trouver tous les trésors du donjon, et d'être sûr de n'en rater aucuns.
Le Maître du Jeu n'a pas d'objectif, il doit juste décrire l'environnement à l'Aventurier, ils ne sont ni alliés ni enemis.

Au début de l'exploration d'un donjon, on donnera au Maître du Jeu la carte d'un donjon. Seul lui à le droit de la voir. Il devra dire où l'aventurier doit mettre la salle d'entrée sur sa feuille, ainsi que le nombre et la direction des portes de la salle d'entrée.<br>
L'aventurier explorera les différentes salles en annonçant au Maître du Jeu la salle qu'il quitte et la porte qu'il emprunte.<br>
Le Maître du Jeu devra expliquer la distance parcourue dans le couloir (entre les deux salles), l'orientation de la porte de sortie du couloir (par rapport au centre de la salle d'arrivée). Une fois dans la salle, le Maître du Jeu va donner le nom de la salle, le nombre de portes et leurs directions.

Une fois que l'aventurier aura dessiné la nouvelle salle sur sa carte, il devra y déplacer son pion, car c'est la qu'il est désormais.
Si l'Aventurier souhaite explorer une porte d'une salle où il n'est pas il va devoir se déplacer avec son pion jusqu'à cette salle.<br>
Cette dernière contrainte permet d'aider les élèves à trouver un algorithme de parcours en profondeur.<br>

Pour faire découvrir le parcours en largeur, on peut retirer cette dernière contrainte (i.e : ne plus utiliser le jeton), et demander aux élèves de calculer la plus courte distance depuis l'entrée et n'importe quelle salle.

## Extensions
Il est possible de décliner cette activité afin de faire découvrir d'autres algorithmes et théories sur les graphes. Par exemple :
- Les graphes orientés : en expliquant que les portes sont a sens uniques (des portes styles "sorties de secours" qui empêchent de faire marche arrière).
- Les graphes pondérés : en situant les donjons dans une caverne, ou un terrain accidenté, ainsi emprunter un chemin accidenté est plus long (a un coût en temps).  
Avec une telle configuration, il est possible de faire des recherches de chemin à coût minimum.

## Liens
- Vous trouverez le document décrivant l'activité en détails [ici](https://github.com/TabaryM/Mediation_Graphes/blob/master/Atelier/atelier_donjons.pdf) avec un exemple d'exploration d'un donjon assez petit, une exeplication sur les distances à exprimer pour les couloirs fourbes, ainsi que qu'un algorithme de parcours en profondeur et un agorithme de parcours en largeur, tout deux utilisés pour faire les "corrections" des parcours des donjons [Facile](https://github.com/TabaryM/Mediation_Graphes/blob/master/DonjonsSimples/donjons_faciles_tous.pdf),
[Moyen](https://github.com/TabaryM/Mediation_Graphes/blob/master/DonjonsMoyens/donjons_moyens_tous.pdf),
[Difficiles](https://github.com/TabaryM/Mediation_Graphes/blob/master/DonjonsDifficiles/donjons_difficiles_tous.pdf)
- D'autres activité de médiations de sciences informatiques sans ordinateur : [Médiation](https://members.loria.fr/MDuflot/files/med/)

## Partage et droits

Ce document et les documents liés sont mis à disposition selon les termes de la licence Creative Commons “Attribution - Partage dans les mêmes conditions 4.0 International”<br>
[![License: CC BY SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)<br>


Cette activité a été créée par Mathieu Tabary.
Vous pouvez trouver la version originale sur son [GitHub](https://github.com/TabaryM/Mediation_Graphes/blob/master/README.md)
