
# 🐍 Python List — Complete Notes

## 1. List

* A List is a collection used to store multiple items in one variable. `fruits = ["apple", "banana", "mango"]`
* Lists are created using square brackets `[]`. `numbers = [1, 2, 3]`
* Lists are **ordered**, meaning items maintain their order. `["A", "B", "C"]`
* Lists are **mutable**, meaning items can be changed after creation. `numbers[0] = 10`
* Lists allow **duplicate values**. `[10, 20, 10, 30]`
* Lists can contain **different data types**. `[10, "Bharath", 3.5, True]`
* Lists can contain **other lists**. `[[1, 2], [3, 4]]`

## 2. List Indexing

* Indexing is used to access individual items. `fruits[0]`
* List indexing starts from `0`. `["A", "B", "C"] → 0, 1, 2`
* Negative indexing accesses items from the end. `fruits[-1]`
* `-1` represents the last item. `fruits[-1]`

## 3. List Slicing

* Slicing is used to access a range of items. `numbers[1:4]`
* The start index is included and the end index is excluded. `numbers[1:4]`
* Slicing can use negative indexes. `numbers[-3:-1]`
* Slicing returns a new list. `new_list = numbers[1:4]`

## 4. Changing List Items

* Individual items can be changed using their index. `numbers[1] = 50`
* Multiple items can be changed using slicing. `numbers[1:3] = [50, 60]`
* Lists are mutable, so their contents can be changed after creation.

## 5. Adding List Items

* `append()` adds one item to the end. `numbers.append(6)`
* `insert()` adds an item at a specific position. `numbers.insert(1, 10)`
* `extend()` adds multiple items from another iterable. `numbers.extend([7, 8])`

## 6. Removing List Items

* `remove()` removes a specified value. `numbers.remove(10)`
* `pop()` removes an item using its index. `numbers.pop(2)`
* `pop()` without an index removes the last item. `numbers.pop()`
* `del` removes an item or the entire list. `del numbers[1]`
* `clear()` removes all items from the list. `numbers.clear()`

## 7. Looping Through Lists

* A `for` loop can be used to access every item. `for x in numbers:`
* A `while` loop can also be used to traverse a list. `while i < len(numbers):`
* `enumerate()` provides both index and value. `for i, x in enumerate(numbers):`

## 8. Checking List Items

* `in` checks whether an item exists in a list. `"apple" in fruits`
* `not in` checks whether an item does not exist. `"orange" not in fruits`

## 9. List Length

* `len()` returns the number of items in a list. `len(numbers)`

## 10. Searching and Counting

* `index()` returns the position of the first matching value. `numbers.index(20)`
* `count()` returns how many times a value occurs. `numbers.count(20)`

## 11. Sorting Lists

* `sort()` sorts the original list. `numbers.sort()`
* `sort(reverse=True)` sorts the original list in descending order. `numbers.sort(reverse=True)`
* `sorted()` returns a new sorted list without changing the original. `new = sorted(numbers)`

## 12. Reversing Lists

* `reverse()` reverses the original list. `numbers.reverse()`
* `reversed()` returns a reverse iterator. `list(reversed(numbers))`

## 13. Copying Lists

* `copy()` creates a copy of a list. `new_list = numbers.copy()`
* Copying prevents simple assignment from referring to the same list object.

## 14. Joining Lists

* The `+` operator joins two lists. `list3 = list1 + list2`
* `extend()` adds elements of another list to the existing list. `list1.extend(list2)`

## 15. List Comprehension

* List comprehension provides a short way to create a new list. `[x for x in numbers]`
* It can include a condition. `[x for x in numbers if x > 5]`

## 16. Nested Lists

* A nested list is a list containing one or more lists. `matrix = [[1, 2], [3, 4]]`
* Nested lists can be accessed using multiple indexes. `matrix[0][1]`

## 17. List Constructor

* `list()` creates a list or converts an iterable into a list. `list((1, 2, 3))`

## 18. Important List Methods

* `append()` — adds an item at the end.
* `clear()` — removes all items.
* `copy()` — returns a copy.
* `count()` — counts occurrences.
* `extend()` — adds elements from another iterable.
* `index()` — finds the position of a value.
* `insert()` — adds an item at a position.
* `pop()` — removes and returns an item.
* `remove()` — removes a specified value.
* `reverse()` — reverses the list.
* `sort()` — sorts the list.

## 19. Common Built-in Functions

* `len()` — returns the number of items. `len(numbers)`
* `max()` — returns the largest value. `max(numbers)`
* `min()` — returns the smallest value. `min(numbers)`
* `sum()` — returns the total of numeric values. `sum(numbers)`
* `sorted()` — returns a sorted list. `sorted(numbers)`
* `reversed()` — returns a reverse iterator. `reversed(numbers)`
* `enumerate()` — returns index and value. `enumerate(numbers)`
* `any()` — checks whether any item is truthy. `any(numbers)`
* `all()` — checks whether all items are truthy. `all(numbers)`
Absolutely bud 🤝 Same exact format as the List notes — **concept + simple explanation + example on the same line**, covering the important W3Schools-level concepts for **Tuple, Set, and Dictionary**.

# 🐍 Python Tuple — Complete Notes

## 1. Tuple

* A Tuple is a collection used to store multiple items in one variable. `fruits = ("apple", "banana", "mango")`
* Tuples are **ordered**, meaning items maintain their order. `("A", "B", "C")`
* Tuples are **unchangeable (immutable)**, meaning items cannot be changed after creation. `numbers = (1, 2, 3)`
* Tuples allow **duplicate values**. `(10, 20, 10, 30)`
* Tuples can contain **different data types**. `(10, "Bharath", 3.5, True)`
* Tuples are written using round brackets `()`. `numbers = (1, 2, 3)`
* A tuple can contain other tuples or collections. `((1, 2), (3, 4))`

## 2. Creating a Tuple

* An empty tuple can be created using empty parentheses. `empty = ()`
* A single-item tuple requires a comma. `single = (10,)`
* Multiple values can be stored in a tuple. `numbers = (1, 2, 3)`

## 3. Tuple Indexing

* Indexing is used to access individual items. `fruits[0]`
* Tuple indexing starts from `0`. `("A", "B", "C") → 0, 1, 2`
* Negative indexing accesses items from the end. `fruits[-1]`

## 4. Tuple Slicing

* Slicing is used to access a range of items. `numbers[1:4]`
* The start index is included and the end index is excluded. `numbers[1:4]`
* Slicing returns a new tuple. `new_tuple = numbers[1:4]`

## 5. Tuple Immutability

* Tuple items cannot be changed directly after creation. `numbers = (1, 2, 3)`
* Items cannot be added or removed directly.
* A tuple can be converted to a list for modification and converted back to a tuple. `tuple(list(numbers))`

## 6. Looping Through Tuples

* A `for` loop can be used to access every item. `for x in numbers:`
* `enumerate()` can provide index and value. `for i, x in enumerate(numbers):`

## 7. Checking Tuple Items

* `in` checks whether an item exists. `20 in numbers`
* `not in` checks whether an item does not exist. `50 not in numbers`

## 8. Tuple Methods

* `count()` returns the number of occurrences of a value. `numbers.count(10)`
* `index()` returns the position of the first matching value. `numbers.index(20)`

## 9. Tuple Unpacking

* Tuple unpacking assigns tuple items to separate variables. `a, b, c = numbers`
* Extended unpacking can collect multiple values using `*`. `a, *b = numbers`

## 10. Joining Tuples

* The `+` operator joins tuples. `tuple3 = tuple1 + tuple2`
* The `*` operator repeats tuple items. `tuple2 = tuple1 * 2`

## 11. Tuple Functions

* `len()` returns the number of items. `len(numbers)`
* `max()` returns the largest value. `max(numbers)`
* `min()` returns the smallest value. `min(numbers)`
* `sum()` returns the total of numeric values. `sum(numbers)`
* `sorted()` returns a new sorted list. `sorted(numbers)`

## 12. Tuple Constructor

* `tuple()` creates a tuple or converts an iterable into a tuple. `tuple([1, 2, 3])`

### 🧠 Tuple Memory

**Tuple → Ordered → Immutable → Duplicates → Indexing → Slicing → Unpacking**

---

# 🐍 Python Set — Complete Notes

## 1. Set

* A Set is a collection used to store multiple unique items. `fruits = {"apple", "banana", "mango"}`
* Sets are **unordered**, so items do not have a fixed position. `{"A", "B", "C"}`
* Sets are **changeable (mutable)**. `numbers.add(10)`
* Sets **do not allow duplicate values**. `{1, 2, 2, 3}`
* Sets are written using curly brackets `{}`. `{1, 2, 3}`
* Sets can contain different data types. `{10, "Bharath", 3.5}`
* Sets do not support indexing or slicing. `numbers[0]` ❌
* Sets are useful for removing duplicate values. `set(numbers)`

## 2. Creating a Set

* An empty set is created using `set()`. `empty = set()`
* Curly brackets can be used to create a set with items. `numbers = {1, 2, 3}`

## 3. Adding Set Items

* `add()` adds one item to a set. `numbers.add(4)`
* `update()` adds multiple items from an iterable. `numbers.update([5, 6])`

## 4. Removing Set Items

* `remove()` removes a specified item and raises an error if it does not exist. `numbers.remove(2)`
* `discard()` removes a specified item without raising an error if it does not exist. `numbers.discard(2)`
* `pop()` removes and returns an arbitrary item. `numbers.pop()`
* `clear()` removes all items. `numbers.clear()`
* `del` deletes the entire set. `del numbers`

## 5. Set Union

* Union combines all unique items from two sets. `A | B`
* `union()` performs the same operation. `A.union(B)`

## 6. Set Intersection

* Intersection returns only common items. `A & B`
* `intersection()` performs the same operation. `A.intersection(B)`

## 7. Set Difference

* Difference returns items present in the first set but not the second. `A - B`
* `difference()` performs the same operation. `A.difference(B)`

## 8. Symmetric Difference

* Symmetric difference returns items that are in either set but not in both. `A ^ B`
* `symmetric_difference()` performs the same operation. `A.symmetric_difference(B)`

## 9. Set Relationships

* `issubset()` checks whether one set is contained within another. `A.issubset(B)`
* `issuperset()` checks whether a set contains another set. `A.issuperset(B)`
* `isdisjoint()` checks whether two sets have no common items. `A.isdisjoint(B)`

## 10. Checking Set Items

* `in` checks whether an item exists. `10 in numbers`
* `not in` checks whether an item does not exist. `10 not in numbers`

## 11. Looping Through Sets

* A `for` loop can be used to access set items. `for x in numbers:`
* Sets do not guarantee a particular iteration order.

## 12. Copying Sets

* `copy()` creates a copy of a set. `new_set = numbers.copy()`

## 13. Set Functions

* `len()` returns the number of items. `len(numbers)`
* `max()` returns the largest value. `max(numbers)`
* `min()` returns the smallest value. `min(numbers)`
* `sum()` returns the total of numeric values. `sum(numbers)`
* `sorted()` returns a sorted list. `sorted(numbers)`

## 14. Set Constructor

* `set()` creates a set or converts an iterable into a set. `set([1, 2, 2, 3])`

### 🧠 Set Memory

**Set → Unique → Unordered → Mutable → No Indexing → Add → Remove → Union → Intersection → Difference**

---

# 🐍 Python Dictionary — Complete Notes

## 1. Dictionary

* A Dictionary is a collection used to store data in **key-value pairs**. `student = {"name": "Bharath", "age": 22}`
* Dictionaries are **ordered** in modern Python. `{"name": "Bharath", "age": 22}`
* Dictionaries are **changeable (mutable)**. `student["age"] = 23`
* Dictionary keys must be **unique**. `{"name": "Bharath", "name": "Raj"}`
* Values can be duplicated. `{"a": 10, "b": 10}`
* Keys must be of immutable/hashable types. `"name"`, `1`, `(1, 2)`
* Values can contain different data types. `{"name": "Bharath", "age": 22, "marks": 85}`
* Dictionaries are written using curly brackets `{}`.
* Dictionaries use keys instead of numerical indexes.

## 2. Creating a Dictionary

* An empty dictionary can be created using `{}`. `student = {}`
* A dictionary can contain multiple key-value pairs. `student = {"name": "Bharath", "age": 22}`

## 3. Accessing Dictionary Items

* A value can be accessed using its key. `student["name"]`
* `get()` can be used to access a value by key. `student.get("name")`
* `keys()` returns all keys. `student.keys()`
* `values()` returns all values. `student.values()`
* `items()` returns all key-value pairs. `student.items()`

## 4. Changing Dictionary Items

* An existing value can be changed using its key. `student["age"] = 23`
* `update()` can add or change key-value pairs. `student.update({"age": 23})`

## 5. Adding Dictionary Items

* A new key-value pair can be added using a key. `student["city"] = "Salem"`
* `update()` can add multiple key-value pairs. `student.update({"city": "Salem"})`

## 6. Removing Dictionary Items

* `pop()` removes an item using its key. `student.pop("age")`
* `popitem()` removes the last inserted key-value pair. `student.popitem()`
* `del` removes a specified item or the entire dictionary. `del student["age"]`
* `clear()` removes all items. `student.clear()`

## 7. Checking Dictionary Items

* `in` checks whether a key exists. `"name" in student`
* `not in` checks whether a key does not exist. `"city" not in student`
* `in` checks keys by default, not values.

## 8. Looping Through Dictionary

* A `for` loop can iterate through dictionary keys. `for key in student:`
* `values()` can be used to iterate through values. `for value in student.values():`
* `items()` can be used to iterate through keys and values. `for key, value in student.items():`

## 9. Dictionary Length

* `len()` returns the number of key-value pairs. `len(student)`

## 10. Copying Dictionary

* `copy()` creates a copy of a dictionary. `new_student = student.copy()`

## 11. Nested Dictionary

* A dictionary can contain another dictionary. `students = {"student1": {"name": "Bharath"}}`
* Nested dictionaries are useful for storing structured data.

## 12. Dictionary Comprehension

* Dictionary comprehension provides a short way to create dictionaries. `{x: x*x for x in numbers}`

## 13. Dictionary Methods

* `clear()` — removes all items.
* `copy()` — returns a copy.
* `fromkeys()` — creates a dictionary from specified keys.
* `get()` — returns the value of a specified key.
* `items()` — returns key-value pairs.
* `keys()` — returns all keys.
* `pop()` — removes a specified key-value pair.
* `popitem()` — removes the last inserted pair.
* `setdefault()` — returns a value and inserts the key if it does not exist.
* `update()` — updates or adds key-value pairs.
* `values()` — returns all values.

## 14. Dictionary Functions

* `len()` — returns the number of key-value pairs. `len(student)`
* `sorted()` — returns sorted keys as a list. `sorted(student)`
* `max()` — returns the largest key. `max(student)`
* `min()` — returns the smallest key. `min(student)`

### 🧠 Dictionary Memory

**Dictionary → Key-Value → Ordered → Mutable → Unique Keys → Access by Key → Add → Change → Remove → Loop**

---

# 🔥 Final Collection Memory

| Collection     | Main Property                               |
| -------------- | ------------------------------------------- |
| **List**       | Ordered + Mutable + Duplicates              |
| **Tuple**      | Ordered + Immutable + Duplicates            |
| **Set**        | Unordered + Mutable + Unique                |
| **Dictionary** | Key-Value + Ordered + Mutable + Unique Keys |




**List**

| Method / Function | Purpose                                          |
| ----------------- | ------------------------------------------------ |
| `append()`        | Adds one element to the end                      |
| `extend()`        | Adds multiple elements                           |
| `insert()`        | Adds an element at a specific position           |
| `remove()`        | Removes the first matching value                 |
| `pop()`           | Removes and returns an element by index          |
| `clear()`         | Removes all elements                             |
| `index()`         | Returns the index of a value                     |
| `count()`         | Counts occurrences of a value                    |
| `sort()`          | Sorts the list                                   |
| `reverse()`       | Reverses the list                                |
| `copy()`          | Creates a copy                                   |
| `len()`           | Returns number of elements                       |
| `max()`           | Returns largest element                          |
| `min()`           | Returns smallest element                         |
| `sum()`           | Returns sum of numeric elements                  |
| `sorted()`        | Returns a new sorted list                        |
| `reversed()`      | Returns a reverse iterator                       |
| `any()`           | Returns `True` if at least one element is truthy |
| `all()`           | Returns `True` if all elements are truthy        |
| `enumerate()`     | Gives index and value while looping              |

**Tuples
**
| Method / Function | Purpose                                       |
| ----------------- | --------------------------------------------- |
| `count()`         | Counts occurrences of a value                 |
| `index()`         | Returns the index of a value                  
| `len()`           | Returns number of elements                    |
| `max()`           | Returns largest element                       |
| `min()`           | Returns smallest element                      |
| `sum()`           | Returns sum of numeric elements               |
| `sorted()`        | Returns a new sorted list                     |
| `reversed()`      | Returns a reverse iterator                    |
| `any()`           | Checks whether at least one element is truthy |
| `all()`           | Checks whether all elements are truthy        |
| `enumerate()`     | Gives index and value while looping           |

**Set
**
| Method / Function        | Purpose                                       |
| ------------------------ | --------------------------------------------- |
| `add()`                  | Adds one element                              |
| `update()`               | Adds multiple elements                        |
| `remove()`               | Removes an element; error if absent           |
| `discard()`              | Removes an element; no error if absent        |
| `pop()`                  | Removes and returns an arbitrary element      |
| `clear()`                | Removes all elements                          |
| `union()`                | Combines two or more sets                     |
| `intersection()`         | Returns common elements                       |
| `difference()`           | Returns elements only in the first set        |
| `symmetric_difference()` | Returns non-common elements                   |
| `issubset()`             | Checks whether set is a subset                |
| `issuperset()`           | Checks whether set is a superset              |
| `isdisjoint()`           | Checks whether sets have no common elements   |
| `copy()`                 | Creates a copy                                |
| `len()`                  | Returns number of elements                    |
| `max()`                  | Returns largest element                       |
| `min()`                  | Returns smallest element                      |
| `sum()`                  | Returns sum of numeric elements               |
| `sorted()`               | Returns a sorted list                         |
| `any()`                  | Checks whether at least one element is truthy |
| `all()`                  | Checks whether all elements are truthy        |

| Operator | Purpose              |
| -------- | -------------------- |
| `A \| B` | Union                |
| `A & B`  | Intersection         |
| `A - B`  | Difference           |
| `A ^ B`  | Symmetric difference |
| `A <= B` | Subset check         |
| `A >= B` | Superset check       |

**Dictionary**

| Method / Function | Purpose                                       |
| ----------------- | --------------------------------------------- |
| `get()`           | Returns value for a key                       |
| `keys()`          | Returns all keys                              |
| `values()`        | Returns all values                            |
| `items()`         | Returns key-value pairs                       |
| `update()`        | Adds or updates key-value pairs               |
| `pop()`           | Removes specified key and returns its value   |
| `popitem()`       | Removes and returns the last key-value pair   |
| `clear()`         | Removes all pairs                             |
| `copy()`          | Creates a copy                                |
| `setdefault()`    | Gets value or inserts a default value         |
| `len()`           | Returns number of key-value pairs             |
| `max()`           | Returns largest key                           |
| `min()`           | Returns smallest key                          |
| `sorted()`        | Returns sorted keys as a list                 |
| `any()`           | Checks dictionary keys for truthiness         |
| `all()`           | Checks whether all dictionary keys are truthy |
| `enumerate()`     | Gives index and key while looping             |

