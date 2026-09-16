# Python-notes
Python notes
Perfect bud 🤝 Now I understand the format you want: **concept → simple explanation → example on the same line**, without creating a separate example section.

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

