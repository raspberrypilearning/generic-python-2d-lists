Une liste Python peut contenir n'importe quel nombre d'éléments :

``` python
top_row = ['X', 'O', 'X']
```

Une liste 2D est une liste qui contient un certain nombre de listes :

``` python
tableau = [['X', 'O', 'X'],
         ['O', 'X', 'O'],
     ['X', 'O', 'O']]
```

Les listes à l'intérieur de la liste 2D sont accessibles à l'aide d'un index :

``` python
>>> tableau[0]
['X', 'O', 'X']
```

Tu peux également consulter un élément spécifique dans l'une des listes : utilise l'index de la liste, puis l'index de l'élément dans cette liste.

``` python
>>> tableau[1][1]
'X'
```

Si tu souhaites parcourir une liste 2D, tu peux utiliser une boucle **imbriquée** for.

``` python
for ligne in tableau:
    for element in ligne:
        print(element)
```
