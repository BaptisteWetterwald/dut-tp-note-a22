L'interface AntFacadeController ne permet pas de fixer des paramètres différents (quantité de phéromone déposée et quantité de nourriture portée) selon la Colony (à cause du prototype de setParameters() qui n'a pas de paramètre identifiant une Colony).

De la même manière, l'interface utilise des "rows" et des "columns" en paramètres de ses fonctions, ce qui ne s'adapterait pas à un graphe qui ne serait pas sous la forme d'une grille.

Il faut utiliser le principe Open-Closed
