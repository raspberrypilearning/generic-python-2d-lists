Una lista de Python puede contener cualquier número de elementos:

``` python
top_row = ['X', 'O', 'X']
```

Una lista 2D es una lista que contiene un número de listas:

``` python
tablero = [['X', 'O', 'X'],
         ['O', 'X', 'O'],
     ['X', 'O', 'O']]
```

Se puede acceder a las listas dentro de la lista 2D utilizando un índice:

``` python
>>> tablero[0]
['X', 'O', 'X']
```

También puedes ver un elemento específico en una de las listas: usa el índice de la lista, y luego el índice del elemento de esa lista.

``` python
>>> tablero[1][1]
'X'
```

Si deseas recorrer una lista 2D, puedes usar un bucle "for" **anidado**.

``` python
for fila in tablero:
    for elemento in fila:
        print(elemento)
```
