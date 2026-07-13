# Merge Two Dictionaries in Python

## 📌 Overview

This project demonstrates how to **merge two dictionaries** into a single dictionary using Python's **dictionary unpacking (`**`)** feature.

The program combines key-value pairs from two dictionaries into one new dictionary. Dictionary unpacking is a clean, efficient, and modern approach introduced in **Python 3.5+**.

This project is ideal for beginners learning Python dictionaries and data manipulation.

---

## 🚀 Features

* Merges two dictionaries into one
* Uses Python's dictionary unpacking (`**`)
* Preserves all key-value pairs
* Simple and beginner-friendly implementation

---

## 🛠️ Technologies Used

* Python 3.5+

---

## 📂 Project Structure

```text
├── merge_dictionaries.py
└── README.md
```

---

## 💻 Source Code

```python
d1 = {"a": 1, "b": 2}
d2 = {"c": 3, "d": 4}

merged = {**d1, **d2}
print(merged)
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/merge-two-dictionaries.git
cd merge-two-dictionaries
```

### Run the Program

```bash
python merge_dictionaries.py
```

---

## 📋 Sample Output

```text
{'a': 1, 'b': 2, 'c': 3, 'd': 4}
```

---

## 🧠 Concepts Covered

* Python Dictionaries
* Dictionary Unpacking (`**`)
* Key-Value Pairs
* Dictionary Operations
* Data Manipulation

---

## 🔍 How It Works

1. Create two dictionaries containing key-value pairs.
2. Use the `**` unpacking operator to expand both dictionaries.
3. Store the combined result in a new dictionary.
4. Print the merged dictionary.

---

## ⚠️ Duplicate Keys

If both dictionaries contain the **same key**, the value from the **second dictionary** overwrites the value from the first.

Example:

```python
d1 = {"a": 1, "b": 2}
d2 = {"b": 20, "c": 3}

merged = {**d1, **d2}
print(merged)
```

Output:

```text
{'a': 1, 'b': 20, 'c': 3}
```

---

## ⏱️ Complexity Analysis

| Operation        | Complexity   |
| ---------------- | ------------ |
| Time Complexity  | **O(n + m)** |
| Space Complexity | **O(n + m)** |

Where:

* **n** = number of items in the first dictionary
* **m** = number of items in the second dictionary

---

## 🔮 Future Improvements

* Accept dictionaries from user input
* Merge multiple dictionaries
* Detect duplicate keys before merging
* Merge nested dictionaries recursively
* Compare dictionary merging techniques (`update()`, `|`, and `**`)

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How dictionaries store data in Python
* How dictionary unpacking (`**`) works
* How to merge multiple dictionaries efficiently
* How Python handles duplicate keys during merging

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | Python | Java | SQL | Data Analytics

---

## 📄 License

This project is open-source and available for educational and learning purposes.
