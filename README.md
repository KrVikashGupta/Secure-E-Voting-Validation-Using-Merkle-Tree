
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


# 🚀 Secure E-Voting Validation System

A **C++ based system** that validates voter identities using **hashing** and **Merkle Tree** to ensure **data integrity** and **tamper-proof verification** in electronic voting environments.

---

✨ **Features**
✅ Verify voter registration numbers securely  
✅ Detect tampering with votes using Merkle Tree  
✅ Efficient hashing using FNV-1a algorithm  
✅ Read voter data from CSV file  
✅ Displays tree structure for visualization  
✅ Modular and clean C++ implementation  

---

🛠️ **Tech Stack**
- **Language:** C++  
- **Hashing Algorithm:** FNV-1a  
- **Data Structure:** Merkle Tree  
- **File Handling:** CSV input for voter records  
- **Development:** Visual Studio Code, g++ Compiler  

---

🚦 **How It Works**
1️⃣ Load voter registration numbers from a CSV file.  
2️⃣ Hash each voter ID using FNV-1a.  
3️⃣ Build a Merkle Tree from the hashed voter IDs.  
4️⃣ User enters a voter registration number.  
5️⃣ The system searches the Merkle Tree to verify identity.  
6️⃣ Displays the result as **VALID** or **INVALID**.  

---

🚀 **Getting Started Locally**

**Prerequisites**  
- C++ compiler (`g++`)  
- CSV file with voter registration numbers  

**Clone the repository**  
```bash
git clone https://github.com/YourUsername/Secure-E-Voting-Validation-Using-Merkle-Tree.git
````

**Compile and run**

```bash
g++ evoting_validation.cpp -o evoting_validation
./evoting_validation
```

**Input**
Enter the voter ID when prompted.

**Output**
Displays the voter name, Merkle Tree structure, and verification status.

---

🎯 **Future Enhancements**

* Build Merkle Tree dynamically from large CSV datasets
* Blockchain integration for immutable vote records
* Graphical User Interface (GUI) for easy interaction
* Multi-user and concurrent validation support

---

🤝 **Contributing**
Contributions are welcome!

* Fork the repository
* Open issues
* Submit pull requests

---

🪪 **License**
This project is licensed under the MIT License.

---

📫 **Contact**
**Vikash Kumar Gupta**
📍 Bokaro Steel City, Jharkhand
✉️ [vikashkumargupta907@gmail.com](mailto:vikashkumargupta907@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/vikash-kumar-gupta) | [GitHub](https://github.com/KrVikashGupta)

