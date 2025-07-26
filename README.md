# 📒 Contact Book Application with Trie + BST

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![GUI](https://img.shields.io/badge/GUI-Tkinter-orange)

A high-performance contact book application that combines the efficiency of Trie data structure for prefix searches with Binary Search Tree (BST) for sorted storage. Features a modern Tkinter GUI with all CRUD operations.

## 🌟 Features

- **Lightning Fast Search**: Trie implementation for O(k) time prefix searches
- **Sorted Contacts**: BST maintains contacts in alphabetical order
- **Full CRUD Operations**:
  - Create: Add new contacts
  - Read: View all contacts or search by prefix
  - Update: Modify existing contacts
  - Delete: Remove contacts
- **Persistent Storage**: Automatically saves to JSON file
- **Responsive GUI**: Intuitive Tkinter interface

## 🛠️ Tech Stack

- **Language**: Python 3.6+
- **Data Structures**:
  - Trie (Prefix tree) for efficient searching
  - Binary Search Tree for sorted storage
- **GUI**: Tkinter
- **Persistence**: JSON file storage


## 🖥️ Usage

### ➕ Add Contact:
- Fill in **Name**, **Phone**, and (optional) **Email**
- Click the **"Add"** button

### 🔍 Search Contacts:
- Type in the **search box** to filter contacts by name prefix

### ✏️ Update Contact:
- Select a contact from the list
- Modify fields and click **"Update"**

### 🗑️ Delete Contact:
- Select a contact and click **"Delete"**

### 📋 View All Contacts:
- Contacts auto-display in **alphabetical order**
- **Clear** the search box to see all contacts

---

## 🧠 Data Structures Explained

### 🔡 Trie Implementation
- Used for **efficient prefix search** (`O(k)` time complexity)
- Each node = 1 character in contact names
- Enables **instant search-as-you-type**

### 🌳 Binary Search Tree
- Stores contacts in **sorted order by name**
- Enables `O(log n)` operations when balanced
- **In-order traversal** provides a sorted contact list

---

## 📂 Project Structure

contact-book-trie-bst/
├── contact_book.py # Core logic with Trie + BST implementation
├── contact_book_gui.py # Tkinter GUI application
├── contacts.json # Auto-generated contacts database
├── README.md # This file
└── requirements.txt # Python dependencies


---

## 🚀 Performance

| Operation       | Time Complexity      | Description                           |
|----------------|----------------------|---------------------------------------|
| Add Contact     | `O(k) + O(log n)`     | `k = name length`, `n = total contacts` |
| Prefix Search   | `O(k)`                | Extremely fast search-as-you-type     |
| Delete Contact  | `O(k) + O(log n)`     | Efficient contact removal             |
| View All        | `O(n)`                | In-order BST traversal                |

---




