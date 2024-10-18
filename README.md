# Data_Structures_in_python

# Python Data Structures Exercises

This repository contains exercises on fundamental data structures in Python, including lists, dictionaries, sets, and tuples. These exercises are designed to help beginners understand the basic operations and usage of these data structures.

## Table of Contents

1. [List](#list)
2. [Dictionary](#dictionary)
3. [Set](#set)
4. [Tuple](#tuple)

## List

### Exercise 1:
- **Task**: Create a list of 5 random numbers and print the list.
- **Code**:
    ```python
    import random
    random_list = [random.randint(1, 100) for _ in range(5)]
    print("Original list:", random_list)
    ```

### Exercise 2:
- **Task**: Insert 3 new values to the list and print the updated list.
- **Code**:
    ```python
    random_list.extend([10, 20, 30])
    print("Updated list:", random_list)
    ```

### Exercise 3:
- **Task**: Use a `for` loop to print each element in the list.
- **Code**:
    ```python
    for element in random_list:
        print(element)
    ```

## Dictionary

### Exercise 1:
- **Task**: Create a dictionary with keys `'name'`, `'age'`, and `'address'` and their respective values.
- **Code**:
    ```python
    person_dict = {'name': 'John', 'age': 25, 'address': 'New York'}
    print("Original dictionary:", person_dict)
    ```

### Exercise 2:
- **Task**: Add a new key-value pair to the dictionary with key `'phone'` and value `'1234567890'`.
- **Code**:
    ```python
    person_dict['phone'] = '1234567890'
    print("Updated dictionary:", person_dict)
    ```

## Set

### Exercise 1:
- **Task**: Create a set with values `1, 2, 3, 4, 5`.
- **Code**:
    ```python
    num_set = {1, 2, 3, 4, 5}
    print("Original set:", num_set)
    ```

### Exercise 2:
- **Task**: Add the value `6` to the set.
- **Code**:
    ```python
    num_set.add(6)
    print("Set after adding 6:", num_set)
    ```

### Exercise 3:
- **Task**: Remove the value `3` from the set.
- **Code**:
    ```python
    num_set.discard(3)
    print("Set after removing 3:", num_set)
    ```

## Tuple

### Exercise 1:
- **Task**: Create a tuple with values `1, 2, 3, 4`.
- **Code**:
    ```python
    num_tuple = (1, 2, 3, 4)
    print("Tuple:", num_tuple)
    ```

### Exercise 2:
- **Task**: Print the length of the tuple.
- **Code**:
    ```python
    print("Length of the tuple:", len(num_tuple))
    ```
