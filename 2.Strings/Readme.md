# 2. Strings

This directory contains some exercises on strings in Python, a `string` is sequence of 
characters. In Python, you can define a string using single or double quotes like this:

```python
name = "Juan Perez"
address = '234 calle A'
```

## 2.1 count_char.py

Given a string and a character, write a function that returns the
count of occurrences of the character in the string.

```python
input_str = "Arriba las manos"
query_char = "a"

count = count_char(input_str, query_char)

print(count)
# output: 4
```

The function should not consider upper and lower case character, this means that both
`"A"` and `"a"` count as a single occurrence.

If there are no occurrences, the function should return `0`

## 2.2 reverse_string.py

Given a string, write a function that returns the input string reversed.

```python
input_str = "bazinga"

output_str = reverse_string(input_str)

print(output_str)
# output: 'agnizab'
```

## 2.3 count_word.py

Given a string, write a function that returns the count of occurrences of
a word in the string.

```python
input_str = "no todo es dinero en el dinero"
word = "dinero"
count = count_word(input_str, word)
print(count)
# output: 2
```

Consider a word as a sequence of letters surrounded by spaces, assume input string only
contains letters and spaces, not numbers or symbols.

Ignore extra spaces between words and at the beginning and at the end.

If the query contains several words, only use the first word. Example:

```python
input_str = "no todo es dinero en el dinero"
word = "dinero no"    # only use first word 'dinero'
count = count_word(input_str, word)
print(count)
# output: 2
```
