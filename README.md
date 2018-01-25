# Morpion

POUR COMPRENDRE LE FICHIER : 

Commencer à lire à partir de l'initialisation :
1. On demande leurs noms au joueur et on les enregistre comme des nouvelles instances de la classe Player avec les paramètres de leur noms et de leurs signes (la classe player est tout en haut) 
2. On affiche la grille avec le board.display (display = méthode de la classe Board), chaque case est un numéro de l'array @@position
3. on lance la boucle While pour faire alterner les 2 tours tant qu'il n'y pas de Board.winner = true 
4. A chaque tour ou appelle la méthode turn de la classe Board, avec laquelle on enregistre la position que le marker du joueur doit prendre, vérifie que la position est available (méthode checkConflict(position) de la classe Board) puis on update le tableau 
5. la boucle While vérifie qu'il n'y a pas de winner et passe au tour suivant jusqu'à ce qu'une situation de winner se présente. 
