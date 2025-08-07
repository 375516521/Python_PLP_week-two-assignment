📘 Python List Operations Example

This simple Python script demonstrates basic list operations including appending, inserting, extending, removing, sorting, and finding the index of an element in a list.

🧾 Code Summary

# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend the list with [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort the list in ascending order
my_list.sort()

# Find and print the index of the value 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)

✅ Step-by-Step Explanation

1. Create an Empty List

my_list = [] initializes an empty list.



2. Append Elements

Adds 10, 20, 30, and 40 to the end of the list.



3. Insert Element

my_list.insert(1, 15) inserts the value 15 at index 1.



4. Extend List

Adds multiple elements [50, 60, 70] to the list using extend().



5. Remove Last Element

my_list.pop() removes the last element from the list (70).



6. Sort List

my_list.sort() arranges the list in ascending order.



7. Find Index

my_list.index(30) returns the index of value 30 after sorting.
