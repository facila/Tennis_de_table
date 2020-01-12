# Tennis_de_table

1 : Equipes_de _4_repartition_des_tables.ods : tableau donnant les possibilités pour faire jouer :
- 2 rencontres sur 3 tables
- 3 rencontres sur 4 tables

2 : tournoi.ods : feuilles de saisie des joueurs d'un tournoi et de calcul automatique des poules

Les feuilles des tableaux Ko T16 T32 T64 sont indépendantes.
Il n’y a pas de fonction de saisie des résultats des poules avec remplissage automatique des tableaux
Ces tableaux peuvent paraitre peu lisibles , mais ils permettent un suivi très simple de tout le tableau
Le gagnant prend le numéro le plus bas du match , le perdant prend le numéro le haut

Le fichier sert à générer automatiquement les poules :
– la feuille « Joueurs » sert à la saisie des joueurs et des paramètres
– la feuille « Poules » donne automatiquement les poules
– les feuilles « Poules de 3 » et « Poules de 4 » donne les poules à imprimer
– la feuille « Numéros » permet de calculer la position des joueurs dans les poules
– la feuille « Tables » permet de calculer le nombre de joueurs par poules 3 ou 4 en fonction du nombre de table

Sur le feuille « Joueurs » , il faut saisir :
– les joueurs et la trier
– Tableau : le nom du tableau
– Nombre de table -> permet de calculer : Nombre de joueurs par poule conseillé
– Joueurs par poule -> peut être modifié 3 ou 4
- le reste est calculé automatiquement , nombre de match à jouer …..

Les formules de calcul des poules sont :
- pour un nombre pair de poules   : tableaux standards
- pour un nombre impair de poules : les poules sont faites avec le serpent
                                    le resultat donne directement la position dans le tableau final

Chaque joueur à un numéro initial
Le résultat des poules donne le nouveau numéro de chaque joueur en fonction de sa place
Les joueurs sont placés dans le tableau avec ce numéro
Un joueur ne peut pas rencontrer un autre joueur de sa poule avant les 1/2 finales ou la finale pour le 1 et 2
