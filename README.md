# CPT112 - Discrete Structures (Assignment 1)

This repository contains the C++ implementation for **CPT112: Discrete Structures - Assignment 1** (Academic Session 2024/2025) at Universiti Sains Malaysia (USM).

## Course Details
- **Course Code:** CPT112
- **Course Name:** Discrete Structures
- **Semester:** Year 1, Semester 2 (2024/2025)

---

## Assignment Overview

The assignment applies discrete mathematics concepts computationally in C++:
1. **Set Theory Operations:**
   - Union, Intersection, Difference, and Complement of sets.
   - Checking subset relationships.
2. **Relations and Logic:**
   - Representing relations between sets using C++ data structures.
   - Checking reflexive, symmetric, and transitive properties.
3. **Program Output:** Displaying set membership, operation results, and relation properties in a formatted console output.

---

## What I Did
- Implemented all set operations and relation checks in [`Asgn1_22304588_AHMED_H_M_.cpp`](Asgn1_22304588_AHMED_H_M_.cpp).
- Referenced the coursework submission report: [`CW1_22304588.pdf`](CW1_22304588.pdf).

---

## Tools & Tech Stack
- **Language:** C++ (standard library, arrays, STL sets)
- **IDE/Compiler:** GCC / MinGW

---

## How to Run

1. Compile the program:
   ```bash
   g++ Asgn1_22304588_AHMED_H_M_.cpp -o sets_relations
   ```
2. Run the executable:
   ```bash
   ./sets_relations
   ```
3. The program will demonstrate set operations and print the relation properties to console output.

---

## 📸 Sample Output

```
===== Pension Eligibility and Calculation App (PECA) =====
1. Input Personal Information
2. Input Service and Wages Information
3. Display Service and Wages Information
4. Set Pension Date and Calculate Pension Estimation
5. Exit
Select an option: 1

Enter Employee ID: EMP001
Enter Employee Name: Ahmed Taha
Your Date of Birth Information:
Day: 15   Month: 3   Year: 1980

Select an option: 2
Service Information:
Set Appointment Date:
Day: 1   Month: 6   Year: 2005
Enter Last Salary: RM5000
Enter Total Allowance: RM800

Select an option: 4
Set Pension Date:
Day: 1   Month: 6   Year: 2026

Pension Eligibility Calculation:
Pension Eligibility Confirmed!
Estimated Monthly Pension: RM2104.2
Gratuity: RM94500

Select an option: 3
Service Information:
Name: Ahmed Taha
ID: EMP001
Date of Birth: 15/3/1980
Date of Appointment: 1/6/2005
Last Salary: RM5000
Total Allowance: RM800

Select an option: 5
Exiting the application. Goodbye!
```

