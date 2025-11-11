## 🎓 Student Grade Calculator (Python)

This project is a simple **Python program** that calculates a student's grade based on their marks using a function and conditional statements. It’s perfect for **beginners** who are learning Python basics like **functions**, **if-else**, and **user input**.

---

### 🧠 **How It Works**

1. The program defines a function called `calculate_grade(marks)` which:

   * Takes the student's marks as input.
   * Checks the range of marks using `if-elif-else` conditions.
   * Returns the appropriate grade (`A+`, `A`, `B`, `C`, `D`, or `F`).

2. The user is asked to:

   * Enter their **name** and **marks**.
   * The program then calls the function and displays the final report.

---

### 💻 **Code Example**

```python
def calculate_grade(marks):
    if marks >= 90:
        grade = "A+"
    elif marks >= 80:
        grade = "A"
    elif marks >= 70:
        grade = "B"
    elif marks >= 60:
        grade = "C"
    elif marks >= 50:
        grade = "D"
    else:
        grade = "F"
    return grade

name = input("Enter student name: ")
marks = float(input("Enter marks (out of 100): "))
grade = calculate_grade(marks)
print("--- Student Report ---")
print("Name:", name)
print("Marks:", marks)
print("Grade:", grade)
```

---

### 🧾 **Example Output**

```
Enter student name: Ali
Enter marks (out of 100): 85
--- Student Report ---
Name: Ali
Marks: 85.0
Grade: A
```

---

### 🚀 **Features**

* Beginner-friendly and easy to understand
* Uses **functions** for reusability
* Demonstrates **conditional logic** clearly
* Clean and formatted report output

---

### 🛠️ **Requirements**

* Python 3.x installed on your system

---

### ▶️ **How to Run**

1. Copy the code into a file named `student_grade.py`
2. Open your terminal or command prompt
3. Run the file:

   ```
   python student_grade.py
   ```
4. Enter the student’s name and marks when prompted

---

### 👨‍💻 **Author**

**Zain Akram**
Beginner Python Developer | Learning Programming & Logic Building
