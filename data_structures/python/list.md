# Lists
```python
squares = [1, 4, 9, 16, 25]
```

**Length**
\
*Time Complexity: O(1)*
```python
len(letters)
```

**Count**
\
Return the number of times x appears in the list.
```python
fruits.count('tangerine')
```

**Sort**
\
*Time Complexity: O(n log n)*
\
Sort the items of the list in place 
```python
letters.sort()
```

**Slice / Copy**
\
*Time Complexity: O(n)*
\
Returns shallow copy

```python
squares-copy = squares[:]
```

```python
squares-copy = squares.copy()
```

**Concatenation**
\
*Time Complexity: O(k)*
```python
squares + [36, 49, 64, 81, 100]
```

**Append**
\
*Time Complexity: O(1)*
\
Add an item to the end of the list. Equivalent to a[len(a):] = [x].
```python
cubes.append(216)
```

**Extend**
\
*Time Complexity: O(k)*
\
Extend the list by appending all the items from the iterable. Equivalent to a[len(a):] = iterable.

```python
list1.extend(iterable)
```

**Insert**
\
*Time Complexity: O(n)*
\
Insert an item at a given position. The first argument is the index of the element before which to insert, so a.insert(0, x) inserts at the front of the list, and a.insert(len(a), x) is equivalent to a.append(x).

```python
letters.insert(3, 'o')
```

**Clear**
\
*Time Complexity: O(n)*
\
Remove all items from the list. Equivalent to del a[:]
```python
squares.clear()
```


**Assingment to slice**
```python
# replace some values
letters[2:5] = ['C', 'D', 'E']

# now remove them
letters[2:5] = []

# clear the list by replacing all the elements with an empty list
letters[:] = []
```