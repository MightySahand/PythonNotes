# Lists In Python

## Declaration 

Lists are used to store multiple items in a single variable.
There are basicaly 4 different built-in data types for storing collections in python:
1. List
2. Dictionary
3. Set 
4. Tuple

This is how you should declare a new list(using brackets):

```python 
games = ["GTA", "RED Dead", "Crash", "NBA"]
print(games)
```

As you may know, list indexing starts from 0.

### Characteristic 

1. Ordered
2. Changeable
3. Allows Duplicates
4. Unlike arrayLists in other languages, here you can add different types to the same list



## Length

Use len()

for e.g:

```python
games = ["GTA", "RED Dead", "Crash", "NBA"]
print(len(games))
```

## Access Items

Use indexes to acces items

_Negative indexing means start from the end_

for e.g:

```python
games = ["GTA", "RED Dead", "Crash", "NBA"]
print(games[0], games[-1])
```

## Slicing List

You can specify a range of indexes by specifying where to start and where to end the range.
It is obvious that you can use negative indexing too.

_[start(included) : end(excluded)]_

for e.g: 

```python
games = ["GTA", "RED Dead", "Crash", "NBA"]
print(games[1:2])
```

## Check existence of an item in the list

To Check if a specified item is present in a list use the in keyword:

```python
games = ["GTA", "RED Dead", "Crash", "NBA"]
if "Fifa" in games:
    print("You Like Soccer!")
```

## Insert Items 

You can insert items into the list at the desired index.

```python
games = ["GTA", "RED Dead", "Crash", "NBA"]
games.insert(2, "Fifa")
```

## Append

Appending is like inserting at the end.

```python
games = ["GTA", "RED Dead", "Crash", "NBA"]
games.append("Fifa")
```

## Extend

You can extend the list with any iterable:

```python 
my_games = ["GTA", "RED Dead", "Crash", "NBA"]
your_games = ["Fifa", "NBA", "Mortal Combat"]
my_games.extend(your_games)
```

## Removing element 

There are multiple options for removing elements from a list

### remove

You can use remove() which removes the first occurance of the element.

```python 
my_games = ["GTA", "RED Dead", "Crash", "NBA", "GTA"]
my_games.remove("GTA")
```

### pop

You can also use pop() too. If you specify an index in the method then the index's element will be removed, and if not the last one will.

```python
my_games = ["GTA", "RED Dead", "Crash", "NBA", "GTA"]
my_games.pop("GTA")
my_games.pop()
```

### del

Deleting the whole list or an index of the list.

```python
my_games = ["GTA", "RED Dead", "Crash", "NBA", "GTA"]
# Only deletes the first element of the list
del my_games[0]
# Deletes the whole list
del my_games
```

### Clear

Wipes out the whole list.

```python
my_games = ["GTA", "RED Dead", "Crash", "NBA", "GTA"]
my_games.clear()
```

## Sort
