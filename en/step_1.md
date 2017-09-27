A Python list can hold any number of items:

``` python
top_row = ['X', 'O', 'X']
```

A 2D list is a list that holds a number of lists:

``` python
board = [['X', 'O', 'X'],
         ['O', 'X', 'O'],
	 ['X', 'O', 'O']]
```

The lists inside the 2D list can be accessed using an index:

``` python
>>> board[0]
['X', 'O', 'X']
```

You can also look at a specific item in one of the lists: use the index of the list, and then the index of the item in that list.

``` python
>>> board[1][1]
'X'
```

If you want to loop over a 2D list, you can use a **nested** for loop.

``` python
for row in board:
    for item in row:
	    print(item)
```
