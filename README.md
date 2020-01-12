# Tennis_de_table

### 1 : equipes_de _4_repartition_des_tables.ods
```
Tableau donnant les possibilités pour faire jouer les équipes de 4 joueurs :
- 2 rencontres sur 3 tables
- 3 rencontres sur 4 tables
```
### 2 : tournoi.ods
```
Feuilles de saisie des joueurs d'un tournoi et de calcul automatique des poules
```
```
Les feuilles des tableaux Ko T16 T32 T64 sont indépendantes
Il n’y a pas de fonction de saisie des résultats des poules avec remplissage automatique des tableaux
Ces tableaux peuvent paraitre peu lisibles , mais ils permettent un suivi très simple de tout le tableau
Le gagnant prend le numéro le plus bas du match , le perdant prend le numéro le haut
```
```
Le fichier sert à générer automatiquement les poules :
– la feuille « Joueurs » sert à la saisie des joueurs et des paramètres
– la feuille « Poules » donne automatiquement les poules
– les feuilles « Poules de 3 » et « Poules de 4 » donne les poules à imprimer
– la feuille « Numéros » permet de calculer la position des joueurs dans les poules
– la feuille « Tables » permet de calculer le nombre de joueurs par poules conseillé
                        3 ou 4 en fonction du nombre de tables
                        2 est donné si le nombre de joueurs est trop important
                        pour 2 il n'y a plus de poules , mais un avant-tour avec les 2 joueurs qualifiés 
```
```
Sur la feuille « Joueurs » , il faut saisir :
– Les joueurs et la trier
– Tableau : le nom du tableau
– Nombre de table   -> permet de calculer : Nombre de joueurs par poule conseillé
– Joueurs par poule -> peut être modifié 3 ou 4
Le reste est calculé automatiquement , nombre de match à jouer …..
```
```
Les formules de calcul des poules sont :
- pour un nombre pair de poules   : tableaux standards
- pour un nombre impair de poules : les poules sont faites avec le serpent
                                    le resultat donne directement la position dans le tableau final
```
```
Chaque joueur à un numéro initial
Le résultat des poules donne le nouveau numéro de chaque joueur en fonction de sa place
Les joueurs sont placés dans le tableau avec ce numéro
Dans une poule :
- le premier   ne peut pas rencontrer le deuxième et le troisième avant la finale
- le deuxième  ne peut pas rencontrer le troisième avant la demi-finale
- le quatrième ne peut pas rencontrer le deuxième et le troisième avant la finale
- le quatrième ne peut pas rencontrer le premier avant la demi-finale

```
```
Pour gérer plusieurs tableaux :
Il faut créer un fichier par tableau en copiant le fichier d’origine
Par exemple en tournoi.date.classement , tournoi.2020.01.12.1500
```
```
Pour ceux qui veulent développer pour ajouter des fonctions , le mot de passe est : azerty
```
