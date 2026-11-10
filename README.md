# Expense Tracker App (v1.0)

A simple command-line Expense Tracker application developed using Python in Google Colab. The application allows users to record monthly expenses, calculate category-wise spending, identify the highest spending category, and generate a summary report in Bangladeshi Taka (Tk).

## 1. Project Overview

The Expense Tracker helps individuals understand their monthly spending habits by organizing expenses into categories. Users can enter expenses one by one, and the application automatically calculates category totals, overall expenditure, and percentage distribution.

## 2. Project Objectives

- Record individual monthly expenses.
- Calculate total spending for each category.
- Calculate overall monthly expenditure.
- Identify the category with the highest spending.
- Generate a report showing category-wise expenses and percentage shares.

## 3. Technologies Used

- **Programming Language:** Python 3
- **Development Environment:** Google Colab
- **Libraries:** Python Standard Library only

## 4. Features

- **Expense Entry:** Collects item name, amount, and category from users.
- **Default Category:** Assigns "other" when the category is left blank.
- **Category-wise Calculation:** Groups expenses by category and calculates individual totals.
- **Overall Total:** Calculates total monthly expenditure.
- **Top Spending Category:** Identifies the category with the highest spending.
- **Percentage Calculation:** Calculates each category's share of total expenditure.
- **Monthly Report:** Displays a formatted summary of monthly expenses.
- **Empty Input Handling:** Displays "No expenses entered." when no expenses are recorded.
<img width="345" height="61" alt="image" src="https://github.com/user-attachments/assets/9b9f5560-e822-4663-9d13-5124ddf05ba5" />

## 5. Repository Structure

```text
Expense-Tracker-App/
│
├── Expense_Tracker_App_V1_0.ipynb
└── README.md
```

## 6. How to Run the Project

### Using Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Upload notebook**.
3. Upload `Expense_Tracker_App_V1_0.ipynb`.
4. Run the notebook cells sequentially.
5. Enter expense details when prompted.
6. Type `done` to finish entering expenses and generate the monthly report.

## 7. Sample Input

```text
Item (or 'done' to finish): rice
Amount (Tk): 120
Category: food

Item (or 'done' to finish): meat
Amount (Tk): 130
Category: food

Item (or 'done' to finish): fish
Amount (Tk): 150
Category: food

Item (or 'done' to finish): vegetables
Amount (Tk): 200
Category: food

Item (or 'done' to finish): bus ticket
Amount (Tk): 25
Category: transport

Item (or 'done' to finish): washing powder
Amount (Tk): 150
Category: cleaner

Item (or 'done' to finish): electricity
Amount (Tk): 800
Category: bills

Item (or 'done' to finish): gift
Amount (Tk): 200
Category:

Item (or 'done' to finish): done
```

## 8. Sample Output

```text
-------Monthly Report--------
food: 600 Tk (34%)
transport: 25 Tk (1%)
cleaner: 150 Tk (8%)
bills: 800 Tk (45%)
other: 200 Tk (11%)
--------------------------
Total: 1775 Tk
You spent the most on bills: 800 Tk
```
<img width="412" height="611" alt="image" src="https://github.com/user-attachments/assets/8a3d9f1a-e14a-4e6a-8f3c-7879554fb359" />

## 9. Key Python Concepts Applied

- **Lists and Dictionaries:** Store and organize expense records.
- **Loops:** Use `while` and `for` loops for data collection and processing.
- **Conditional Statements:** Handle default categories and control program execution.
- **Functions:** Organize the application into reusable, modular functions.
- **Dictionary Operations:** Group expenses and calculate category-wise totals.
- **Data Aggregation:** Calculate overall spending and category totals.
- **Percentage Calculation:** Determine each category's contribution to total expenditure.
- **Return Values:** Pass calculated results between functions.

## 10. Testing

The application was tested with eight expense records from a single month.

Test scenarios include:

- Entering multiple expenses across different categories.
- Entering multiple expenses under the same category.
- Leaving the category blank to apply the default "other" category.
- Typing `done` to finish expense entry.
- Verifying category-wise totals and overall expenditure.
- Identifying the highest spending category.

## 11. Project Limitations (v1.0)

- Expenses cannot be added or deleted after the report is generated.
- Expense records are not saved to a file or database.
- Amount validation is not implemented.
- Budget management is not included.
- The application uses a command-line interface only.

## 12. Future Improvements

- Store expense records in a database.
- Add, edit, and delete expense records.
- Introduce monthly and yearly expense tracking.
- Implement budget management.
- Develop a web-based application using Django.
- Add interactive dashboards and visualizations.

## 13. Author

**Jahura Begum**

- GitHub: [Jahura7](https://github.com/Jahura7)
- LinkedIn: [Jahura Begum](https://www.linkedin.com/in/jahura-begum-64008858/)

---

*This project was developed as part of my Python learning journey to strengthen my understanding of programming fundamentals, modular programming, and practical problem-solving.*
