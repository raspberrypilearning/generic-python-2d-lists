एक Python list में कितनी भी चीजें हो सकती हैं:

``` python
top_row = ['X', 'O', 'X']
```

एक 2D list ऐसी list है जिसमें अनेक lists हो सकती है।

``` python
board = [['X', 'O', 'X'],
         ['O', 'X', 'O'],
     ['X', 'O', 'O']]
```

एक 2D list के अंदर मौजूद lists एक क्रम-सूची का उपयोग कर पुनः प्राप्त की जा सकती हैं।

``` python
>>> board[0]
['X', 'O', 'X']
```

आप सभी lists में से किसी एक list में मौजूद एक विशिष्ट चीज़ को भी देख सकते हैं। पहले उस list की क्रम-सूची का प्रयोग करें, और फिर list में मौजूद उस चीज़ की क्रम-सूची का प्रयोग करें।

``` python
>>> board[1][1]
'X'
```

यदि आप किसी 2D list पर loop करना चाहते हैं, तो आप एक **nested** for loop का इस्तेमाल कर सकते हैं।

``` python
for row in board:
    for item in row:
        print(item)
```
