# Data Structures in Python


## Table of Contents

1. [Lists](#lists)
2. [Tuples](#tuples)
3. [Dictionaries](#dictionaries)
4. [Sets](#sets)


## What are Data Structures?

Data structures are specialised formats for organising and storing data in a computer's memory or other storage devices. They provide efficient ways to perform various operations such as insertion, deletion, searching, and sorting on the stored data. The choice of a data structure depends on the specific requirements of the task at hand. 

Let's expolore a few of the basic data structures you will encounter.

## Lists


- Lists are ordered collections that allow for flexible manipulation, including indexing, slicing,
 appending, inserting, removing, extending, popping, counting, sorting, reversing, and clearing elements.
- Lists are mutable, meaning they can be modified, making them versatile for various operations.
- This is why these operations work for lists but not for immutable data structures like Tuples and Sets.

### Example:

Let's create a list and perform some common operations in Python.

```python
# Create a list
my_list = [1, 2, 3, 4, 5]

# Index: is used to find the index of a specific element in the list.
index = my_list.index(3)
print(index)  # What output do you get? Why?

# Access elements by indexing(using the position of an element in the list)
print(my_list[0])  # What output do you get? Why?
print(my_list[-1]) # What output do you get? Why?

# Access elements by slicing(using a range of indexes to get elements in a list)
# The syntax for for slicing is: my_list[start_index:end_index]
print(my_list[1:4])  # What output do you get? Why?

# Append: add an element to the end of the list.
my_list.append(6)
print(my_list)  # What output do you get? Why?

# Insert: is used to add an element at a specific position in the list.
my_list.insert(2, 10)
print(my_list)  # What output do you get? Why?

# Remove:  remove a specific element from the list.
my_list.remove(3)
print(my_list)  # What output do you get? Why?

# Extend: is used to add multiple elements at the end of the list.
my_list.extend([6, 7, 8])
print(my_list)  # What output do you get? Why?

# Pop: is used to remove and return the last element from the list or the element at a specific position.
popped_element = my_list.pop()
print(popped_element)  # What output do you get? Why?

# Count: is used to count the number of occurrences of a specific element in the list.
count = my_list.count(2)
print(count) # What output do you get? Why?

# Sort: is used to sort the elements in the list in ascending or descending order.
unordered_list = [50, 11, 43, 22, 4]
unordered_list.sort()
print(unordered_list)  # What output do you get? Why?

# Reverse: is used to reverse the order of elements in the list.
my_list.reverse()
print(my_list) # What output do you get? Why?

# Clear: is used to remove all elements from the list.
my_list.clear()  
print(my_list)  # What output do you get? Why?
```

## Tuples


- Tuples are immutable, meaning their elements cannot be changed after creation.
- This is why operations like append, insert, and extend (which modify the data structure) do not work on tuples.
- You can only access and extract elements from a tuple.

### Example:

Let's create a tuple and perform some common operations in Python.

```python
# Create a tuple
my_tuple = (1, 2, 3, 4, 5)

# Access elements by indexing(using the position of an element in the tuple)
print(my_tuple[0])  # What output do you get? Why?
print(my_tuple[-1]) # What output do you get? Why?

# Access elements by slicing(using a range of indexes to get elements in a tuple)
# The syntax for slicing is: my_tuple[start_index:end_index]
print(my_tuple[1:4])  # What output do you get? Why?
```

## Dictionaries

- Dictionaries use key-value pairs, and they are mutable, which allows for dynamic addition, updating, and removal of elements.
- This makes dictionaries suitable for various operations like adding, updating, and accessing values by keys.

### Example:

Let's create a dictionary and perform some common operations in Python.

```python
# Create a dictionary
my_dict = {'name': 'John', 'age': 30, 'city': 'Durban'}

# Access values by keys
print(my_dict['name'])  # What output do you get? Why?

# Add a new key-value pair
my_dict['country'] = 'South Africa'
print(my_dict)  # What output do you get? Why?

# Update the value of an existing key
my_dict['age'] = 31
print(my_dict) # What output do you get? Why?
```

## Sets




- Sets are unordered collections of unique elements, and they support set operations like union, intersection, and difference.
- Sets are suitable for dealing with unique collections and solving problems that involve set operations.

### Example:

Let's create a set and perform some common operations in Python.

```python
# Create sets
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}

# Union of sets
union_set = set1 | set2
print(union_set)  # What output do you get? Why?

# Intersection of sets
intersection_set = set1 & set2
print(intersection_set)  # What output do you get? Why?

# Difference of sets
difference_set = set1 - set2
print(difference_set)  # What output do you get? Why?
```

By following this order, you will gain a strong understanding of data structures in Python.
Make sure to commit your changes and push them to your forked repository after completing each exercise.
Enjoy the learning experience!
