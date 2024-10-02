# If statement example
x = 5
if x > 10:
    print("x is greater than 10")
else:
    print("x is less than or equal to 10")

# List example
my_list = [1, 2, 3, "four", True, 5.6]
print("List:", my_list)

# Accessing list elements
print("First element:", my_list[0])
print("Last element:", my_list[-1])

# Tuple example
my_tuple = (1, 2, 3, "four", True, 5.6)
print("Tuple:", my_tuple)

# Accessing tuple elements
print("First element:", my_tuple[0])
print("Last element:", my_tuple[-1])

# Set example
my_set = {1, 2, 3, "four", True, 5.6}
print("Set:", my_set)

# Accessing set elements (note: sets are unordered)
for element in my_set:
    print(element)

# Dictionary example
my_dict = {"name": "John", "age": 30, "city": "New York"}
print("Dictionary:", my_dict)

# Accessing dictionary elements
print("Name:", my_dict["name"])
print("Age:", my_dict["age"])

# Using different data types in each collection
my_list = [1, "two", True, 4.5]
my_tuple = (1, "two", True, 4.5)
my_set = {1, "two", True, 4.5}
my_dict = {"int": 1, "str": "two", "bool": True, "float": 4.5}

print("List with different data types:", my_list)
print("Tuple with different data types:", my_tuple)
print("Set with different data types:", my_set)
print("Dictionary with different data types:", my_dict)
