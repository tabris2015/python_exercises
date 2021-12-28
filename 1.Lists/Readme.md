# 1. Lists 
This directory contains some python exercises regarding lists and some other collections.

## 1.1. print_list.py
Given two lists of student names and grades:

```python
student_names = ["juan", "ana", "jose", "raul", "sara", "thais"]
student_grades = [90, 60, 70, 60, 55, 40]
```

Write a function called `print_students` that receives both lists and prints the data as follows:

```python
>>> print_students(names, grades)
Students:
1. juan: 90
2. ana: 60
3. jose: 70
4. raul: 60
5. sara: 55
6. thais: 40
>>> 
```

## 1.2. filter_list.py
Given a list of tuples `(str,int)` of products and prices:

```python
products = [("iron", 90), ("hammer", 70), ("paper", 10), ("solder", 5)]
```

Write a function called `filter_cheap_no_s` that returns a list that 
**only** contains products with a **cost less than 50** and doesn't contain any 
letter **s** in the product name.

```python
>>> filter_cheap_no_s(products)
[("paper", 10)]
```

## 1.3. generate_names.py
Given a list of names and surnames such as:

```python
names = ["juan", "ana", "raul", "sara", "arturo", "sandra"]
surnames = ["alcazar", "alcon", "petersen", "ramirez", "fernandez", "aviles", "rivera"]
```

Write a function called `generate_random_names` that generates random combinations
of names and surnames. the function should accept three parameters `generate_random_names(names, surnames, length)`, 
where `names` is the names list, `surnames` the surnames list and `length` is the size of 
the generated list. 

The function should return a list of strings of size `length` with **capitalized, random** combinations 
of names and surnames. Below an example:

```python
>>> generate_random_names(names, surnames, 3)
["Juan Petersen", "Sara Rivera", "Ana Fernandez"]
```

