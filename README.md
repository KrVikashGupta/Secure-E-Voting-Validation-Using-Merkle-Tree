
# Secure E-Voting Validation System Using Merkle Tree

## Overview
This C++ project implements a **Secure E-Voting Validation System**.  
It verifies voter identities and ensures data integrity using **FNV-1a hashing** and **Merkle Tree structures**.  
The system can detect any tampering with voter data and provide a tamper-proof verification process.

---

## Features
- Secure verification of voter registration numbers  
- Tamper detection using Merkle Tree  
- Efficient hashing with FNV-1a  
- CSV-based voter data input  
- Clear visualization of Merkle Tree structure  
- Modular and maintainable C++ implementation  

---

## Tools & Technologies
- **C++** – Core programming language  
- **FNV-1a Hash Function** – For hashing voter IDs  
- **Merkle Tree** – Tamper-proof tree structure  
- **CSV File Handling** – Input of voter data  
- **STL (Vectors, Smart Pointers)** – Efficient data handling  
- **Visual Studio Code & g++ Compiler** – Development environment  

---

## How It Works
1. Load voter registration numbers from a CSV file.  
2. Each voter ID is hashed using FNV-1a.  
3. Build a Merkle Tree from the hashed voter IDs.  
4. User inputs a voter ID for verification.  
5. System searches the Merkle Tree to validate the voter.  
6. Displays result: **VALID** or **INVALID**, along with voter name and Merkle Tree structure.

---

## Challenges Faced
- Handling large voter datasets (~7000+ entries)  
- Ensuring consistent FNV-1a hash generation  
- Handling invalid or missing CSV data  
- Optimizing Merkle Tree construction for efficiency  

---

## Learnings
- Practical implementation of **Merkle Trees**  
- Understanding **cryptographic hashing** for data integrity  
- File I/O operations and **CSV parsing in C++**  
- Writing **modular, maintainable code**  

---

## Sample Output
```

=======================================
|---Secure E-Voting Validation System---|
Enter Voter ID: 12314515
Verification process initiated...
Name: Vikash Kumar Gupta
Status: VALID
=============

```

---

## Future Enhancements
- Build Merkle Tree dynamically from large CSV datasets  
- Integrate **blockchain** for immutable voting records  
- Add **graphical user interface (GUI)**  
- Support **multi-user and concurrent validation**  
- Implement faster search using hash maps for large datasets  

---

## Author
**Vikash Kumar Gupta**  
📧 vikashkumargupta907@gmail.com  
📍 Bokaro Steel City, Jharkhand  

---

## License
This project is licensed under the **MIT License**.
```
