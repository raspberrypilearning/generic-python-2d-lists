Een Python-lijst kan een willekeurig aantal items bevatten:

``` python
bovenste_rij = ['X', 'O', 'X']
```

Een 2D-lijst is een lijst met een aantal lijsten:

``` python
bord = [['X', 'O', 'X'],
         ['O', 'X', 'O'],
     ['X', 'O', 'O']]
```

De lijsten in de 2D-lijst kunnen worden geopend met behulp van een index:

``` python
>>> bord[0]
['X', 'O', 'X']
```

Je kunt ook naar een specifiek item in een van de lijsten kijken: gebruik de index van de lijst en vervolgens de index van het item in die lijst.

``` python
>>> bord[1][1]
'X'
```

Als je een 2D-lijst wilt doorlopen, kun je een **geneste** for lus gebruiken.

``` python
for rij in bord:
    for item in rij:
        print(item)
```
