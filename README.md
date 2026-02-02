# Day 6 Assignment – Expense Tracker

## Objective 🎯
Build a console-based Expense Tracker that lets you log, view, and manage expenses using **files** in Python. Include proper **error handling**.

---

## Requirements

1. **Add Expenses**
   - Ask for:
     - Date (YYYY-MM-DD)
     - Category (e.g., Food, Transport, Bills)
     - Amount (must be a number)
   - Save each expense to a file `expenses.txt`

2. **View Expenses**
   - Read and display all expenses from the file
   - Handle empty or missing file gracefully
   - Optional: calculate total expenses

3. **Error Handling**
   - Prevent crashes from invalid input
   - Handle missing file

4. **Optional / Bonus Features**
   - Filter by category
   - Delete an expense entry
   - Save data in JSON format instead of plain text
   - Summarize monthly expenses

---

## Sample Program Flow

--- Expense Tracker ---

Add Expense

View Expenses

Exit

Choose option: 1
Enter date (YYYY-MM-DD): 2026-02-02
Enter category: Food
Enter amount: 450
Expense added successfully!

Choose option: 2
Date: 2026-02-02, Category: Food, Amount: 450
Total Expenses: 450

yaml
Copy code

---

## Submission Instructions

- Push your code to your private repository created by GitHub Classroom
- Include at least 5 expense entries
- Test all features before submission
- Optional: implement bonus features for extra credit

---

## Learning Outcomes

- Practice reading/writing files
- Implement error handling (`try/except`)
- Apply simple CRUD logic
- Simulate a real-world backend system
