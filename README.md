# 📘 Day 26: Nested Logic | HackerRank 30 Days of Code

This repository contains the Python solution for Day 26 of the HackerRank 30 Days of Code challenge, focusing on **nested conditional logic** through a real-life scenario involving library fines based on return dates.

## 🚀 Challenge Summary

You're given two dates: 

- The **actual return date** of a library book
  
- The **expected due date** for returning the book  

Your task is to write a program that calculates the **fine** based on the following rules.

## 📝 Problem Statement

Complete a program that:

- Takes the actual and expected return dates
  
- Calculates the fine as follows:

          -If the book is returned on or before the due date → Fine: 0
          
          -If returned late but within the same month and year → Fine: 15 × (days late)
          
          -If returned late but within the same year → Fine: 500 × (months late)
          
          -If returned in a different year → Fine: 10000 (fixed)

## ✅ Constraints

          - 1 ≤ D ≤ 31
            
          - 1 ≤ M ≤ 12
            
          - 1 ≤ Y ≤ 3000
            
          - Dates will be valid Gregorian calendar dates.

## 🔢 Sample Input

          9 6 2015
          
          6 6 2015

## ✅ Sample Output

          45

## 💡 Explanation

- Returned Date: 9 June 2015
   
- Due Date: 6 June 2015
  
→ Same month and year, 3 days late  

→ Fine = 15 × 3 = 45

## 🧠 Concepts Practiced

- Nested `if-elif-else` conditions
    
- Date comparison logic
  
- Clean conditional structure
   
- Real-world logic implementation
    
- Efficient input parsing with `map()` and `split()`

## 🛠 How to Run

Option 1: Manual input

        python3 nested_logic.py

Option 2: Input file

Create a file named input.txt with the input data and run:

        python3 nested_logic.py < input.txt

## 🔗 HackerRank Challenge Link

        HackerRank – Day 26: Nested Logic

🏆 Challenge Completed

✅ Problem Solved

🎯 Points Earned: 30

## 📅 Completed On

        07th June 2025

## 🔖 Tags

#Python #HackerRank #NestedLogic #Conditionals #30DaysOfCode #ProblemSolving #Day26Challenge #LibraryFine #CleanCode

## ✍ Author

        Harsha M
        
        GitHub: @Harshaharika7
        
        LinkedIn: Harsha M
