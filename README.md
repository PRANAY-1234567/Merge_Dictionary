🔗 Merge Two Dictionaries in Python

📌 Description

This program merges two dictionaries into a single dictionary using Python’s dictionary unpacking (**) feature.

It is a simple and efficient way to combine key-value pairs.

🧩 Problem Statement

Given two dictionaries:

d1 = {"a": 1, "b": 2}
d2 = {"c": 3, "d": 4}


Merge them into one dictionary.

✅ Code
d1 = {"a": 1, "b": 2}
d2 = {"c": 3, "d": 4}

merged = {**d1, **d2}
print(merged)

🧠 Explanation

d1 contains the first set of key-value pairs

d2 contains the second set of key-value pairs

{**d1, **d2} merges both dictionaries into one

The result is stored in merged and printed

🖨 Example Output
{'a': 1, 'b': 2, 'c': 3, 'd': 4}

🛠 Concepts Used

Dictionaries

Dictionary unpacking (**)

Key-value pairs

🎯 Use Cases

Combining multiple datasets

Interview preparation

Dictionary manipulation practice

Merging configuration settings

🚀 Possible Improvements

Handle duplicate keys

Merge more than two dictionaries

Use update() method as an alternative

👨‍💻 Author
Pranay Jadhao

<img width="593" height="667" alt="image" src="https://github.com/user-attachments/assets/96241c30-ffcb-4225-a552-e95ca3cc4cc2" />
