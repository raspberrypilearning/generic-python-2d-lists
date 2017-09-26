A Python list holds a number of items.

``` python
top_row = ['X', 'O', 'X']
```

A 2D list is a list that holds a number of lists.

``` python
board = [['X', 'O', 'X'],
         ['O', 'X', 'O'],
		 ['X', 'O', 'O']]
```

This lists can then be accessed using an index.

``` python
>>> board[0]
['X', 'O', 'X']
```

Or you can look at a specific item in one of the lists, by using the index of the list, and then the index of the item in that list.

``` python
>>> board[1][1]
'X'
```

If you want to loop over a 2D list, you could use a **nested** for loop.

``` python
for row in board:
    for item in row:
	    print(item)
```
