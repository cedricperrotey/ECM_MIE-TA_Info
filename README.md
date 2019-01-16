# ECM_MIE-TA_Info
TA 1 Informatique

Il s'agit d'un sudoku que nous avons fait entièrement nous même avec la réflexion suivante :
- 1/ Il faut une grille avec des "trous"
- 2/ Il faut que ces trous soient des champs de texte que l'on puisse remplir
- 3/ Il faut pouvoir comparer à la solution --> Un bouton "check" et un affichage avec un code couleur (rouge/vert)

Pour améliorer ce programme, nous pourrions imaginer :
- Autoriser seulement les chiffres (de 1 à 9) dans les champs de texte --> Vérifier le type OU faire un "clavier numérique" 
avec les chiffres de 1 à 9


-----------------------------------------------------------------------------------------------------------------------------------

Comment utiliser le programme :

Ce programme de base de possède qu'un seul sudoku (variable game_to_solve) et sa correction (game_solution).
1) Une fois le programme lancé, la grille de sudoku apparaît.
2) Le sudoku possède des champs non modifiables et des champs modifiable. l'utilisateur est amené à remplir l'ensemble des champs de texte avec les chiffres manquant en suivant les règles du Sudoku.
3) Une fois que tous les champs de texte sont remplis (ou seulement une partie), l'utilisateur peut obtenir une correction de son sudoku en cliquant sur le bouton "check."
4) une grille de correction apparaît, l'utilisateur peut vérifier son travail en suivant le code couleur :
  - texte écrit en blanc : chiffre déjà donné dans la grille vide
  - texte en vert : le numéro rentré est le correcte
  - texte en rouge : le numéro rentré est incorrecte
