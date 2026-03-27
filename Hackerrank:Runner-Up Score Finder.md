# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:

ADD CODE HERE
n = int(input())
scores = list(map(int, input().split()))
unique_scores = list(set(scores))
unique_scores.sort()
print(unique_scores[-2])
## OUTPUT
<img width="170" height="154" alt="image" src="https://github.com/user-attachments/assets/a341f0a0-3c87-4443-a39b-6d8fd4e5835b" />

## RESULT
Thus,the program is executed successfully
