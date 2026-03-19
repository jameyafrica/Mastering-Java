# Mastering Java
A transparent, high-accountability roadmap of my Java engineering journey.


# ☕ Mastering Java: The Learning Journey

> "Focusing on robust code, JVM internals, and scalable architecture."

## 📊 Knowledge Checklist
- [x] **Java Basics:** (Variables, Data Types, Control Flow)
- [ ] **Object-Oriented Programming:** (Inheritance, Interfaces, Polymorphism)
- [ ] **Collections Framework:** (Lists, Sets, Maps, Streams API)
- [ ] **Exception Handling:** (Try-Catch-Finally, Custom Exceptions)
- [ ] **Concurrency:** (Threads, ExecutorService, Virtual Threads)
- [ ] **JVM Deep Dive:** (Garbage Collection, Heap vs Stack)

---

## 🏗️ Project Catalog
| Project Name | Category | Difficulty | Status | Key Takeaway |
| :--- | :--- | :--- | :--- | :--- |
| **Simple Calculator** | 🛠️ Independent | ⭐ | Polished | Basic logic & Scanner class |
| **Banking System** | 🎓 Tutorial | ⭐⭐⭐ | In-Progress | Encapsulation & Data Security |
| **Two Sum** | 🧩 LeetCode | ⭐⭐ | Polished | HashMaps for $O(n)$ time |

---

## 💡 The "Aha!" Log
### **Hurdle: Primitive vs. Reference Types**
* **The Problem:** I couldn't understand why changing a variable inside a method sometimes changed the original and sometimes didn't.
* **The Breakthrough:** I realized Java is always **pass-by-value**, but for objects, that value is the **memory address**. Changing the address doesn't change the original, but modifying the object *at* that address does.