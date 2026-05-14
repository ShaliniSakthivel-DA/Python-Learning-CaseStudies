# Student Course Fee Calculator Using Python

## 📌 Project Overview
This beginner-friendly Python case study collects student details using the `input()` function and calculates GST and total course fee using basic arithmetic operations.

The project demonstrates:
- Variables
- User Input
- Type Casting
- Arithmetic Operations
- f-Strings
- Data Types using `type()`

---

## 🛠 Technologies Used
- Python

---

## 📚 Concepts Covered
- Variables
- `input()` function
- `int()` type casting
- `float()` type casting
- GST calculation
- f-strings
- `type()` function

---

## 📋 Program Features
The program:
1. Gets student details from the user
2. Converts age into integer
3. Converts course fee into float
4. Calculates:
   - GST (18%)
   - Total Fee
5. Displays all details clearly
6. Shows datatype of important variables

---

## 💻 Sample Output

```python
Enter Student Name: Shalini Sakthivel
Enter Student Age: 27
Enter Course Name: Data Analysis
Enter Course Fee: 45000

----- Student Details -----

Student Name : Shalini Sakthivel
Student Age  : 27
Course Name  : Data Analysis
Course Fee   : 45000.0
GST (18%)    : 8100.0
Total Fee    : 53100.0

----- Datatypes -----

Type of student_age : <class 'int'>
Type of course_fee  : <class 'float'>
Type of total_fee   : <class 'float'>
```

---

## 🧮 GST Calculation Logic

```python
gst = course_fee * 0.18
total_fee = course_fee + gst

print("Total Course Fee:", total_fee)
```

---

## 🎯 Learning Outcome
By completing this project, learners can understand how to:
- Accept user input
- Perform type conversion
- Calculate percentages
- Display formatted output
- Identify Python data types

---

## 👩‍💻 Author
Shalini
