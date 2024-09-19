# PYTHON VARIABLES AND DATA TYPES

## String data types


```python
name1="Miguna"
```


```python
name1*2 #Repetition
```




    'MigunaMiguna'




```python
"Jack"+"Son" #concatination
```




    'JackSon'




```python
name1[0]
```




    'M'




```python
name1[1]
```




    'i'




```python
name1[2]
```




    'g'




```python
name1[3]
```




    'u'




```python
name1[4]
```




    'n'




```python
name1[5]
```




    'a'




```python
name1[-1]
```




    'a'




```python
name1[-2]
```




    'n'




```python
name1[-3]
```




    'u'




```python
name1[-4]
```




    'g'




```python
name1[-5]
```




    'i'




```python
name1[-6]
```




    'M'




```python
name1
```




    'Miguna'




```python
name1[0:3]
```




    'Mig'




```python
name1[2:5]
```




    'gun'




```python
name1[-4:-1]
```




    'gun'




```python
name1[-4:5]
```




    'gun'




```python

```


```python
name1.find("gun") #find() function finds where the stated string values start from i.e the index
```




    2




```python
name1.find("g")
```




    2




```python
name1.find("n")
```




    4




```python
name1.replace("Mi","Nju") #replace() function replaces specified characters with the one you want
```




    'Njuguna'




```python
name1.replace("guna","cah")
```




    'Micah'




```python
name2=name1.replace("guna","llicent")
```


```python
name1.replace("una","os")
```




    'Migos'




```python
name1.replace("guna", "chael")
```




    'Michael'




```python
print(name2)
```

    Millicent
    


```python
name2.count("l")
```




    2




```python
name2.count("i")
```




    2




```python
name2.count("M")
```




    1




```python
name2.strip()
```




    'Millicent'




```python
name3="Miguna "
```


```python
name3*2
```




    'Miguna Miguna '




```python
name3.strip() #strip() function removes any leading or trailing spaces
```




    'Miguna'




```python

```


```python

```


```python

```

# TUPLES


```python
name4=("Bildad","Aziza","Denis","Magdalene","Emmanuel","Carol","Collins") #a tuple with string values
```


```python
name4
```




    ('Bildad', 'Aziza', 'Denis', 'Magdalene', 'Emmanuel', 'Carol', 'Collins')




```python
tup1=(7,8,9,10,11) #a tuple with integer values
```


```python
tup1 
```




    (7, 8, 9, 10, 11)




```python
tup2=("Arsenal",name3,100, 100.5) #a tuple with string value, already defined variable, an integer and a float value
```


```python
tup2
```




    ('Arsenal', 'Miguna ', 100, 100.5)




```python
tup3=("Zakayo",200,tup2) #a tuple with string value, integer value and an already defined tuple variable
```


```python
tup3
```




    ('Zakayo', 200, ('Arsenal', 'Miguna ', 100, 100.5))




```python

```


```python

```
