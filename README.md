# InterviewPreparation

Solving the python problems to get ready for interview

PYTHON METHODS FOR DIFFERENT DATATYPES:
1. Dictionaries (HashMaps): These are mutable. They are unordered. There can't be duplicate keys. They are written with curly braces. Unlike sets, they have two dimensions key and value as each element.
- fromkeys(array_to_get_values,def_value): Creates a dictionary from an iterable like list/string with the default value of choice
- clear(): empties the dictionary
- dict.defaultdict(lambda: 0) or defaultdict(int) : makes a empty dictionary with default values 0 when specified the key
- setdefault(key,value) : Similar to the get method below. Grabs a key value pair and if not found, creates a new one with the second argument value passed.
- get(index): used to get the values at the specified index
- pop(index): pops the item at the specified index
- popitems() : Automatically pops the last key value pair from the dictionary
- values(): gives the values of the dictionary as a list
- keys() gives all the keys as a list
- copy() gives a shallow copy of a dictionary. This means changing the copy dictionary also changes the original dictionary.
- items() gives tuples of the key value pairs of the dictionary as a list/iterables
- dict1.update(dict2): Adds the key- value pairs of dict2 to dict1 and overwrites the key-value pair if it already exists in dict1.

2. Arrays: Lists in python, These are mutable.
- append(): adds an item to the end of the array
- extend(): adds one list to another list
- clear(): deletes the whole array
- copy(): Creates a shallow copy of the array. This means changing the copy array also changes the original array.
- len(): length of the array
- pop(index): deletes the last element if no index is passed in the argument
- remove(value): deletes the specified element from the array
- reverse(): reverses the array
- sort(): sorts the array in ascending order. If you want to sort it in descending order, pass a reverse=True argument
- index(value): finds the index of the value provided as the argument. Throws an error if the value is not found.
- insert(value, index): inserts the value at a specified index
- del arr[i:j]: deletes the elements from index i to j

3. Tuples: The identifier of a tuple is not the circular braces but the commas: (1,2,3) is a tuple and so is 1,2,3 in python
- index(value): finds the index of the value provided as the argument. returns the first index for the value found. 
- count(value): returns the number of times the value is found in the tuple

4. Sets (HashSets): A set is a collection which is unordered and unindexed. In Python, sets are written with curly brackets. Sets contain unique values. These are mutable. 
- add(value): adds a value to the set, similar to append method in lists
- update(list/iterables): adds multiple values to the set, similar to extend method in lists
- remove(value): removes a value from the set. Similar to remove method in lists. If value is not present in the set, it throws an error
- discard(value) removes a value from the set. It does not throw an error if the value is not present in the set.
- set1.intersetion(set2): gives the elements that are present in both sets
- set1.intersetion(set2,set3): gives the elements that are present in all the sets
- set1.difference(set2): gives the elements that are present in set1 but not in set2
- set1.difference(set2,set3): gives the elements that are present in set1 but not in set2 or set3 (i.e (set2 union set3))
- set1.symmetric_difference(set2): gives the elements that are present in set1 or set2 but not in both. (Similar to A+B-A intersection B)

5. Strings: A string is a sequence of characters. Strings are immutable in python. It is an array of characters.
- upper(): converts the string to uppercase
- lower(): converts the string to lowercase
- count(value): returns the number of times the value is found in the string
- endswith(value): checks if the string ends with the value provided as the argument
- startswith(value): checks if the string starts with the value provided as the argument
- find(substring): returns the index of the first occurrence of the substring
- index(substring): returns the index of the first occurrence of the substring
- isdigit(): checks if the string contains only digits
- isalpha(): checks if the string contains only alphabets
- isalnum(): checks if the string contains only digits and alphabets
- isupper(): checks if the string contains only uppercase characters
- islower(): checks if the string contains only lowercase characters
- isascii(): checks if the string contains only ascii characters
- isnumeric(): checks if the string contains only numeric characters
- isdecimal(): checks if the string contains only decimal characters
- isspace(): checks if the string contains only space characters
- join(list/iterables): joins the elements of the list/iterables into a single string
- lower(): converts the string to lowercase
- upper(): converts the string to uppercase
- lstrip(substring): removes the leading substring from the string
- rstrip(substring): removes the trailing substring from the string
- partition(character): Splits the string into three parts. The first part is the part before the character, the ehird part is the part after the character and the second part is the character itself
- replace(this, with, limit): replacing the text with new text given number of times.
- strip(substring): removes the substring from the string
- zfill(num): adds 0 to the left till the length becomes 20
- text.splitlines(): splits the string into lines

6. Deque: Stacks (LiFo): Last in first out and Queues (FiFo): First in first out are both handled in python using deque dataype
- appendleft(): adds an element to the left of the deque. (Not useful for stacks or queues but useful in general)
- popleft(): deletes the first element of the deque. Used for queues. First in first out
- append(): adds an element to the right of the deque. Useful to add element to queue and stack
- pop(): pops the last element of the deque.(Useful for Stacks)
- extend(list): adds the elements of the list to the right of the deque
- extendleft(list): adds the elements of the list to the left of the deque
- rotate(num): shift the deque by num elements to the right. pass negative integers to shift towards left.

7. Collections Module: This module contains a number of iterables. There are 5 main classes.
- Counter: This Class is used to count the number of times an element occurs in an iterable. it has object methods like most_common(value), elements()
- defaultdict: This Class is used to create a dictionary with default values
- deque: This Class is used to create a deque
- namedtuple: This Class is used to create a named tuple
- OrderedDict: This Class is used to create an ordered dictionary

8. Itertools module: This module contains a number of functions that can be used to with iterators like lists, strings, tuples, etc.
This has 6 main classes.
- product: This class is used to get the cartesian product of the elements of an iterable
- accumulate: This class is used to accumulate the elements of an iterable
- permutations: This class is used to get permutations of the elements of an iterable
- combinations: This class is used to get combinations of elements of an iterable
- groupby: This class is used to group the elements of an iterable
- infinite iterators: This class is used to create infinite iterators

