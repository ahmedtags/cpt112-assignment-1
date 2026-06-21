# CPT111 - Principles of Programming (Assignment 2)

<p align="center">
  <img src="https://img.shields.io/badge/Language-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="Language" />
  <img src="https://img.shields.io/badge/Course-CPT111-24292e?style=for-the-badge" alt="Course" />
  <a href="https://github.com/ahmedtags">
    <img src="https://img.shields.io/badge/Profile-ahmedtags-D9A34A?style=for-the-badge&logo=github&logoColor=white" alt="Profile" />
  </a>
  <a href="https://blxman-37fy.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-blxman--37fy-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

This repository contains the C++ implementation for **CPT111: Principles of Programming - Assignment 2** (Academic Session 2023/2024) at Universiti Sains Malaysia (USM).

## Course Details
- **Course Code:** CPT111
- **Course Name:** Principles of Programming
- **Semester:** Year 1, Semester 1 (2023/2024)

---

## Assignment Overview

The assignment is an interactive C++ console application that demonstrates OOP principles:
1. **Object-Oriented Programming (OOP):**
   - Classes, private member encapsulation, and constructors.
   - Inheriting `Pension_Info` from `Service_Info` and composing the `Employee` object.
   - Declaring `friend` functions for input handling.
2. **Pension Eligibility Rules:**
   - Age must be $\ge 40$ years old.
   - Years of service must be $\ge 10$ years.
3. **Financial Estimation Formulas:**
   - Monthly Pension = $0.00167 \times \text{Service Months} \times \text{Last Salary}$.
   - Gratuity = $0.075 \times \text{Service Months} \times \text{Last Salary}$.

---

## What I Did
- Developed the complete OOP-structured pension calculation console program in [`Asgn1_22304588_AHMED_H_M_.cpp`](Asgn1_22304588_AHMED_H_M_.cpp).
- Referenced the coursework submission report: [`CW1_22304588.pdf`](CW1_22304588.pdf).

---

## Tools & Tech Stack
- **Language:** C++ (Standard library, inheritance, friend functions, encapsulation)
- **IDE/Compiler:** GCC / MinGW

---

## How to Run

1. Compile the program:
   ```bash
   g++ Asgn1_22304588_AHMED_H_M_.cpp -o pension_app
   ```
2. Run the executable:
   ```bash
   ./pension_app
   ```
3. Input employee information, appointment details, salary/allowances, and pension dates to view the computed eligibility status and estimates.

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
