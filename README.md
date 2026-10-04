Municipal Financial Management System (MFMS)

PAP521S – Programming in Practice

Project A: Municipal Financial Management System

Programming Language: ANSI C (C99)  
Development Environment: Visual Studio Code and GCC  
Version Control: Git and GitHub  
Project Type: Group Project  
Group Number: 0  
Submission: Moodle and GitHub Repository  




1. Project Description

The Municipal Financial Management System (MFMS) is a basic C program developed for the PAP521S Programming in Practice course.

The system is designed to help manage some basic municipal information such as employees, budgets, suppliers and assets. It is a menu-driven program where the user can select different sections of the system.

The project also gives the group an opportunity to apply the C programming concepts covered in class, including variables, arrays, strings, functions, loops, conditions and calculations.

Git and GitHub were used by the group to work on and keep track of the project.

---

2. System Modules

The system contains the following modules:

1. Employee Management
2. Budget Management
3. Supplier Management
4. Asset Management
5. Reports

The main menu is used to access the different modules.



3. Project Files


MFMS
├── .gitignore
├── main.c
├── employee.c
├── employee.h
├── budget.c
├── budget.h
├── supplier.c
├── supplier.h
├── assets.c
├── assets.h
├── reports.c
├── reports.h
└── README.md
```



4. Group Members

| No. | Name | Student Number | Responsibility |
|---|---|---|---|
| 1 | Naftal Fotolela | 213071916 | Testing & Documentation |
| 2 | Corneluis D Frans | 216073529 | Functions, Integration & Validation |
| 3 | Dave K Angulah | 201030586 | Budget Module |
| 4 | Kaluwa Martha | 222051078 | Supplier Management |
| 5 | Tjiharuka Utjiwee | 219110972 | Assets Management |
| 6 | Nalilongwe Lawrence | 225081903 | Employee Management |
| 7 | I. Gustav | 224095080 | Reports |

---

## 5. Main Features

### Employee Management

The employee section allows the user to:

- Add employees
- Display employees
- Search for an employee
- Calculate salary information
- Display employee information

Employee information is stored using structures and arrays.

### Budget Management

The budget section allows the user to:

- Add departmental budgets
- Enter expenditure
- Calculate the remaining budget
- Check whether expenditure is within the budget
- Display departments that have exceeded their budgets

### Supplier Management

The supplier section allows the user to:

- Add suppliers
- Display suppliers
- Search suppliers by ID
- Search suppliers by name

Supplier information includes the supplier ID, name, email, telephone number and location.

### Asset Management

The asset section allows the user to:

- Add assets
- Display assets
- Search for assets

The system stores information such as asset ID, name, type, value, department and condition.

### Reports

The reports section contains:

- Employee Report
- Budget Report
- Supplier Report
- Asset Report

The Employee Report gives a summary of employee salary information. The Budget Report shows the total allocated budget, expenditure and remaining budget. The Supplier and Asset Reports display the records stored in the system.

---

## 6. Compilation

Open the MFMS folder in Visual Studio Code and compile the program using:

```bash
gcc *.c -o mfms
```

On Windows, this will create `mfms.exe`.



7. Running the Program

Run the program from the VS Code terminal using:

```powershell
.\mfms.exe
```

The main menu will then be displayed.



8. Main Menu

The main menu contains:

```text
==================================================
        Municipal Financial Management
==================================================
1. Employee Management
2. Budget Management
3. Supplier Management
4. Asset Management
5. Reports
6. Exit
==================================================
```



9. Testing

The system was tested during development after the different modules were added and integrated.

Testing included:

- Main menu
- Employee Management
- Budget Management
- Supplier Management
- Asset Management
- Reports
- Searching
- Salary calculations
- Compilation
- Integration of the different modules

The system was also tested using sample employee, supplier, budget and asset records.



10. Git and GitHub

Git and GitHub were used to manage the project and keep track of changes made by the group members.

The group used GitHub to commit and push changes, fix problems and combine the different modules into the final system.

**GitHub Repository:**

https://github.com/216073529/MFMS.git



11. Development Process

The project was developed by first creating the different modules and then connecting them through the main program.

The general process used was:

```text
Input
  ↓
Processing
  ↓
Storage
  ↓
Search
  ↓
Calculation
  ↓
Output
```

The program was compiled and tested while the modules were being integrated.



12. Current Project Status

The Project A foundation system has been completed and the different modules have been integrated into the main program.

The system currently includes Employee Management, Budget Management, Supplier Management, Asset Management and Reports.

The project is ready for submission and demonstration.



13. Future Development

The system can be expanded in Project B by adding features such as:

- File or database storage
- More detailed reports
- Better input validation
- More financial calculations
- Improved user interface
- Additional employee, supplier and asset functions



14. Academic Project

Course: PAP521S – Programming in Practice  
Project: Project A – Municipal Financial Management System

This project demonstrates the use of the C programming concepts covered during the course.