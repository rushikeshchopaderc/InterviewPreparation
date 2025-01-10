# InterviewPreparation

Solving the python problems to get ready for interview

PYTHON METHODS FOR DIFFERENT DATATYPES:
1. Dictionaries
- fromkeys(array_to_get_values,def_value): Creates a dictionary from an iterable like list/string with the default value of choice
- clear(): empties the dictionary
- dict.defaultdict(lambda: 0) or defaultdict(int) : makes a empty dictionary with default values 0 when specified the key
- setdefault(key,value) : Similar to the get method below. Grabs a key value pair and if not found, creates a new one with the second argument value passed.
- get(index): used to get the values at the specified index
- pop(index): pops the item at the specified index
- popitems() : Automatically pops the last key value pair from the dictionary
- .values(): gives the values of the dictionary as a list
- .keys() gives all the keys as a list
- .copy() gives a shallow copy of a dictionary( This means changing the copy dictionary also changes the original dictionary.
- .items() gives tuples of the key value pairs of the dictionary as a list/iterables
- dict1.update(dict2): Adds the key- value pairs of dict2 to dict1 and overwrites the key-value pair if it already exists in dict1.

2. Arrays
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
1. Tuples:
2. Strings:
3. Sets:
4. Collections Module:


   
