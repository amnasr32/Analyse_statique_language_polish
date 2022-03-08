Projet PF5 2021 : Polish
========================



## Compilation et lancement


1) Pour la compilation :  $ make
  - `make` sans argument lancera la compilation `dune` de `polish.exe`,
    c'est-à-dire votre programme en code natif.

  - `make clean` pour effacer le répertoire provisoire `_build`
    produit par `dune` lors de ses compilations.


 
2) Enfin pour lancer votre programme: `./run arg1 arg2 ...`

- Pour réafficher le programme en partant de la syntaxe abstraite obtenueet suivant les règles indiquées de syntaxe concrète :
   $ ./run -reprint exemples/nom_du_fichier

- Pour évaluer le programme :
   $ ./run -eval  exemples/nom_du_fichier

- Pour simplifier le programme :
   $ ./run -simpl  exemples/nom_du_fichier

- Pour afficher les variables de ce programme (toutes les variables + les non-initialisées):
   $ ./run -vars  exemples/nom_du_fichier

- Pour afficher les signes de variables de ce programme et déterminer le risque de division par zéro :

   $ ./run -sign  exemples/nom_du_fichier
