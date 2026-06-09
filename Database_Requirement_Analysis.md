here# Database Requirement Analysis

| Table Name | Purpose | Primary Key | Important Fields |
|------------|---------|-------------|------------------|
| Users | Stores user account information | User_ID | Name, Email, Password, Created_Date |
| Income | Stores user income transactions | Income_ID | User_ID, Source, Amount, Date, Description |
| Expenses | Stores user expense transactions | Expense_ID | User_ID, Category_ID, Amount, Date, Description |
| Categories | Stores income and expense categories | Category_ID | Category_Name, Category_Type |
| Budgets | Stores monthly budget details | Budget_ID | User_ID, Category_ID, Budget_Amount, Month, Year |
| Savings_Goals | Stores user savings targets | Goal_ID | User_ID, Goal_Name, Target_Amount, Current_Amount, Deadline |
