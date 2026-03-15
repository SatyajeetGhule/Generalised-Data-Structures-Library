# 📚 Generic Data Structure Library in C++

A **Generic Data Structure Library** implemented in **C++ using Templates**.
This project provides reusable and type-independent implementations of common data structures such as **Linked Lists, Stack, and Queue**.

The library is designed using **Generic Programming (Templates)** so that the same implementation works with multiple data types like `int`, `float`, `char`, etc.

---

# 🚀 Features

✔ Generic implementation using **C++ Templates**
✔ Clean and modular **Object-Oriented Design**
✔ Supports multiple **Linked List structures**
✔ Dynamic memory management using `new` and `delete`
✔ Fully reusable library for multiple data types

---

# 🧩 Data Structures Implemented

| Data Structure              | Description                               |
| --------------------------- | ----------------------------------------- |
| Singly Linear Linked List   | Nodes connected in one direction          |
| Singly Circular Linked List | Last node points to first node            |
| Doubly Linear Linked List   | Nodes have next and previous pointers     |
| Doubly Circular Linked List | Circular structure with two-way traversal |
| Stack                       | LIFO (Last In First Out) structure        |
| Queue                       | FIFO (First In First Out) structure       |

---

# 📂 Project Structure

```
Generic-Data-Structure-Library
│
├── SinglyLLL
├── SinglyCLL
├── DoublyLLL
├── DoublyCLL
├── Stack
├── Queue
└── main.cpp
```

---

# 🛠 Technologies Used

* **C++**
* **Templates (Generic Programming)**
* **Object-Oriented Programming**
* **Dynamic Memory Allocation**

---

# 📌 Operations Supported

## Linked List

* Insert First
* Insert Last
* Insert At Position
* Delete First
* Delete Last
* Delete At Position
* Display
* Count

---

## Stack

* Push
* Pop
* Peep
* Display
* Count

---

## Queue

* Enqueue
* Dequeue
* Display
* Count

---

# ▶ Example Usage

```cpp
#include<iostream>
using namespace std;

int main()
{
    SinglyLLL<int> obj;

    obj.InsertFirst(10);
    obj.InsertFirst(20);
    obj.InsertLast(30);

    obj.Display();

    cout<<"Total Nodes : "<<obj.Count()<<endl;

    return 0;
}
```

---

# ⚡ Advantages of Generic Implementation

* Code reuse
* Type safety
* Reduced duplication
* Flexible design

Example:

```cpp
SinglyLLL<int> list1;
SinglyLLL<float> list2;
SinglyLLL<char> list3;
```

---

# 📊 Time Complexity

| Operation     | Complexity |
| ------------- | ---------- |
| Insert First  | O(1)       |
| Insert Last   | O(n)       |
| Delete First  | O(1)       |
| Delete Last   | O(n)       |
| Stack Push    | O(1)       |
| Stack Pop     | O(1)       |
| Queue Enqueue | O(1)       |
| Queue Dequeue | O(1)       |

---

# 📖 Learning Outcomes

This project helps in understanding:

* Generic Programming in C++
* Linked List Implementation
* Stack and Queue Implementation
* Dynamic Memory Management
* Object Oriented Design

---

# 👨‍💻 Author

**Satyajeet Manohar Ghule**

---

# 📜 License

This project is for **educational and learning purposes**.
