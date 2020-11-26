# Python Zero to Mastery Notes

### Fundamental Data Types

1. int
2. float
3. bool
4. str
5. list
6. tuple
7. set
8. dict

### Classes -> Custom Types

### Specialized Data Types

### [Math functions](https://www.programiz.com/python-programming/modules/math)

- round: Round float number to up, example `round(3.9)` => `4`
- abs: Absolute number value, example `abs(-20)` => `20`
- bin: Binary number value, example `bin(5)` => `0b101`

### [Python Keywords](https://www.w3schools.com/python/python_ref_keywords.asp)

### List Unpacking

```python
a, b, c, *other, d = [1, 2, 3, 4, 5, 6, 7, 8, 9]

print(a) => 1
print(b) => 2
print(c) => 3
print(other) => [4, 5, 6, 7, 8]
print(d) => 9
```

### Dictionary

Un diccionario es como un objeto de javascript pero se accede al valor de su key como una lista.

```python
dictionary = {
    'a': 1,
    'b': 2
}

print(dictionary['b']) => 2

dictionary2 = {
    'a': [1, 2, 3],
    'b': 'Hello',
    'c': True
}

dictionary_list = [
    {
        'a': [1, 2, 3],
        'b': 'Hello',
        'c': True
    },
    {
        'a': [1, 2, 3],
        'b': 'Bye',
        'c': False
    },
]

print(dictionary_list[0]['a']) => [1, 2, 3]
```
