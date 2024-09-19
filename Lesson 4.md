# TUPLES


```python
mytup1=("hello world",24,"Carole Mugure") #A Tuple is a sequence of immutable Python objects like floating number, string, etc. 
#immutable means tuples cannot be changed while a tuple is a sequeence of immutable objects, a list is a sequence of mutable python objects.
#Tuples are sequences, just like Lists; Allows duplicate members.

```


```python

```


```python

```

## Tuple Operations

### Addition 


```python
mytup1=("a","b","c")
```


```python
mytup1
```




    ('a', 'b', 'c')




```python
mytup1+"d"
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[13], line 1
    ----> 1 mytup1+"d"
    

    TypeError: can only concatenate tuple (not "str") to tuple



```python
mytup1+("d")
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[15], line 1
    ----> 1 mytup1+("d")
    

    TypeError: can only concatenate tuple (not "str") to tuple



```python
mytup1+"(d)"
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[17], line 1
    ----> 1 mytup1+"(d)"
    

    TypeError: can only concatenate tuple (not "str") to tuple



```python
mytup1+("d","e") #Addition in a tuple does concatenation.
```




    ('a', 'b', 'c', 'd', 'e')




```python

```


```python

```

### Repetition


```python
mytup2=("a","b","c")
```


```python
mytup2
```




    ('a', 'b', 'c')




```python
mytup2*3
```




    ('a', 'b', 'c', 'a', 'b', 'c', 'a', 'b', 'c')




```python
mytup2
```




    ('a', 'b', 'c')




```python
mytup3=mytup2*3
```


```python
mytup3
```




    ('a', 'b', 'c', 'a', 'b', 'c', 'a', 'b', 'c')




```python

```


```python

```

### Indexing a Tuple


```python
mytup3
```




    ('a', 'b', 'c', 'a', 'b', 'c', 'a', 'b', 'c')




```python
mytup3[0]
```




    'a'




```python
mytup3[-1]
```




    'c'




```python
mytup3[2]
```




    'c'




```python
mytup3[-5]
```




    'b'




```python
mytup3[-6]
```




    'a'




```python

```


```python

```

### Slicing


```python
mytup3
```




    ('a', 'b', 'c', 'a', 'b', 'c', 'a', 'b', 'c')




```python
mytup3[2:6]
```




    ('c', 'a', 'b', 'c')




```python
mytup3[-2:4]
```




    ()




```python
mytup3[2:5]
```




    ('c', 'a', 'b')




```python
mytup3[5:8]
```




    ('c', 'a', 'b')




```python
mytup3[-4:-1]
```




    ('c', 'a', 'b')




```python
mytup3[-4:8]
```




    ('c', 'a', 'b')




```python
mytup3[-7:5]
```




    ('c', 'a', 'b')




```python

```


```python

```


```python

```

# LISTS


```python
# A list is a sequence of mutable Python objects like floating number, string, literals, etc.
# Lists use square brackets.
mylist1=["hello world",6790,"Sonek",23.87]
```


```python
mylist1
```




    ['hello world', 6790, 'Sonek', 23.87]




```python
mylist2=["Wednesday",234,mylist1] #This is a list containing a string,number and list.
```


```python
mylist2
```




    ['Wednesday', 234, ['hello world', 6790, 'Sonek', 23.87]]




```python

```


```python

```

## List Specific Operations


```python
mylist3=[1,"a",2.5]
```


```python
mylist3
```




    [1, 'a', 2.5]



### list.append()


```python
mylist3.append("b")
```


```python
mylist3
```




    [1, 'a', 2.5, 'b']




```python
mylist3.append("c",8) #List.append can only add 1 item at a time.
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[98], line 1
    ----> 1 mylist3.append("c",8)
    

    TypeError: list.append() takes exactly one argument (2 given)



```python

```


```python

```

### list.extend([])


```python
mylist3
```




    [1, 'a', 2.5, 'b']




```python
mylist3.extend("r",9)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[102], line 1
    ----> 1 mylist3.extend("r",9)
    

    TypeError: list.extend() takes exactly one argument (2 given)



```python
mylist3.extend(["r",9])
```


```python
mylist3
```




    [1, 'a', 2.5, 'b', 'r', 9]




```python

```


```python

```

### list.insert()


```python
mylist3
```




    [1, 'a', 2.5, 'b', 'r', 9]




```python
mylist3.insert(0,"k")
```


```python
mylist3
```




    ['k', 1, 'a', 2.5, 'b', 'r', 9]




```python
mylist3.insert(2,"z")
```


```python
mylist3
```




    ['k', 1, 'z', 'a', 2.5, 'b', 'r', 9]




```python
mylist3.insert(-3,8)
```


```python
mylist3
```




    ['k', 1, 'z', 'a', 2.5, 8, 'b', 'r', 9]




```python

```


```python

```

### list.pop()


```python
#list,pop() deletes the last item from your list.
```


```python
mylist3 
```




    ['k', 1, 'z', 'a', 2.5, 8, 'b', 'r', 9]




```python
mylist3.pop()
```




    9




```python
mylist3
```




    ['k', 1, 'z', 'a', 2.5, 8, 'b', 'r']




```python
mylist3.pop(-3) #popping/deleting the item on index "-3"
```




    8




```python
mylist3
```




    ['k', 1, 'z', 'a', 2.5, 'b', 'r']




```python

```


```python

```


```python

```

# SETS


```python
myset={"Karkar",678.97,"Learning Python at Sonek"} # A Set is an unordered collection of items.
# Every element is unique (no duplicates) and must be immutable (which cannot be changed).
# Set items are enclosed with curly braces { }
```


```python
myset
```




    {678.97, 'Karkar', 'Learning Python at Sonek'}




```python

```


```python

```

## Set Specific Operations 


```python
# Union - A list of all the items in the sets e.g what is in set A and what is in set B without duplicates
#Intersection -The common items between the sets e.g what is in set A and also set B

```


```python
myset1={1,2,"c"}
```


```python
myset2={1,"b","c"}
```

### set union 


```python
#set union 
myset1 | myset2
```

### Set Intersection


```python
myset1 & myset2
```




    {1, 'c'}



### Set difference


```python
myset1 - myset2
```




    {2}




```python
myset2 - myset1
```




    {'b'}




```python
myset1
```




    {1, 2, 'c'}




```python
myset2
```




    {1, 'b', 'c'}




```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
