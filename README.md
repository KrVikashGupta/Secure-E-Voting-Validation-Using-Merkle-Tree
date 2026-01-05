
# 🚀 Secure E-Voting Validation System Using Merkle Tree

## Overview

This **C++ project** implements a **Secure E-Voting Validation System** that ensures voter identity verification and data integrity using **FNV-1a hashing** and **Merkle Trees**.
The system detects tampering, providing a **tamper-proof and verifiable voting process**.

---

## ✨ Key Features

* ✅ **Secure Voter Verification:** Validate voter registration numbers efficiently
* ✅ **Tamper Detection:** Merkle Tree ensures data integrity
* ✅ **Efficient Hashing:** FNV-1a hash function for fast and consistent results
* ✅ **CSV Input:** Load voter data from files
* ✅ **Merkle Tree Visualization:** Easy inspection of tree structure
* ✅ **Modular C++ Code:** Clean, maintainable, and extensible

---

## 🛠️ Technologies Used

* **C++** – Core implementation
* **FNV-1a Hash Function** – Consistent hashing of voter IDs
* **Merkle Tree** – Tamper-proof verification structure
* **CSV Parsing & File I/O** – Load and process voter data
* **STL (Vectors, Smart Pointers)** – Efficient memory management
* **Visual Studio Code / g++** – Development environment

---

## ⚙️ How It Works

1. Load voter registration numbers from a CSV file.
2. Hash each voter ID using **FNV-1a**.
3. Construct a **Merkle Tree** from the hashed IDs.
4. User inputs a voter ID for validation.
5. System verifies the ID via the Merkle Tree.
6. Output: **VALID/INVALID** status along with voter name and Merkle Tree structure.

---

## 🧩 Challenges Faced

* Handling large datasets (~7000+ voters) efficiently
* Ensuring consistent FNV-1a hash generation
* Managing invalid or missing CSV data
* Optimizing Merkle Tree construction and search

---

## 📚 Learnings

* Practical **Merkle Tree implementation**
* Understanding **cryptographic hashing** and data integrity
* Efficient **CSV parsing and file handling in C++**
* Writing **modular, maintainable, and scalable code**

---

## 💻 Sample Output

```
=======================================
|--- Secure E-Voting Validation System ---|
Enter Voter ID: 12314515
Verification process initiated...
Name: Vikash Kumar Gupta
Status: VALID
=======================================
```

---

## 🚀 Future Enhancements

* Dynamic Merkle Tree construction for large CSV datasets
* Integrate with **blockchain** for immutable voting records
* Add a **Graphical User Interface (GUI)**
* Support **multi-user and concurrent validations**
* Implement faster searches with **hash maps** for large datasets

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Open issues
* Submit pull requests

---

## 🪪 License

This project is licensed under the **MIT License**.

---

## 📫 Contact

**Vikash Kumar Gupta**
📍 Bokaro Steel City, Jharkhand
✉️ [vikashkumargupta907@gmail.com](mailto:vikashkumargupta907@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/vikash1995) | [GitHub](https://github.com/KrVikashGupta)

---

⭐ **If this project helped you, give it a star!**

---


