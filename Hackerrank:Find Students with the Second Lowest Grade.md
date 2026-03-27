# 🎓 Hackerrank:Python Program to Find Students with the Second Lowest Grade

This program reads student names and their corresponding grades, identifies the **second lowest grade**, and prints the names of all students who have that grade in **alphabetical order**.

---

## 🎯 Aim

To write a Python program to:
- Read a list of students and their grades.
- Identify the second lowest grade.
- Print the names of students who have that grade, sorted alphabetically.

---

## 🧠 Algorithm

1. **Read** an integer `n` representing the number of students.
2. **Read** each student’s name and grade, and store them as a sublist inside a list.
3. **Extract** all the grades and sort them.
4. **Identify** the second lowest grade from the sorted grade list.
5. **Collect** names of all students whose grade matches the second lowest grade.
6. **Sort** the names alphabetically.
7. **Print** each name on a new line.

---

## 💻  Program

Add Code Here
n = int(input("Enter the number of students: "))
students = []

# Read student names and grades
for _ in range(n):
    name = input("Enter student's name: ")
    grade = float(input("Enter student's grade: "))
    students.append([name, grade])

# Extract and sort the grades
grades = sorted(set([student[1] for student in students]))

# Identify the second lowest grade
second_lowest_grade = grades[1]

# Collect names of students with the second lowest grade
second_lowest_students = sorted([student[0] for student in students if student[1] == second_lowest_grade])

# Print the sorted names
for name in second_lowest_students:
    print(name)
## Output
<img width="346" height="411" alt="image" src="https://github.com/user-attachments/assets/1731b337-3b8d-4ab5-8172-662650db64db" />

## Result

Thus,the program is executed successfully


