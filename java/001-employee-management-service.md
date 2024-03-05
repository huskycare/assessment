# Exercise: Employee Management System

## Background:
You are tasked with creating a simplified part of an Employee Management System (EMS) for a company. The system should be able to add new employees, retrieve information about employees, and perform basic operations like updating employee details and calculating bonuses.

## Requirements:

1. **Core Features:**

   Implement an Employee class with attributes such as id, name, department, salary, and any other attributes you deem necessary.
   Create an EmployeeService interface with methods for adding, updating, retrieving, and deleting an employee. Also, include a method for calculating bonuses for employees based on predefined criteria (e.g., performance, department).

1. **Data Storage:**

   Implement a simple storage mechanism (in memory is sufficient) to store employee records. Ensure thread safety when accessing the storage.

1. **Business Logic:**

   Implement logic to calculate bonuses. For simplicity, the bonus calculation can be based on a fixed percentage of the salary that varies by department (See Appendix A) and performance.
   Ensure that the addEmployee method checks for duplicate entries based on some unique attribute (e.g., id or a combination of name and department).    

4. **Testing:**

    Write unit tests for your implementation, covering critical functionalities.

## Deliverables:

- [ ] Source code for the Employee class, EmployeeService interface, and its implementation.
- [ ] Source code for the storage mechanism.
- [ ] Unit tests

## Evaluation Criteria:

- [ ] Correctness and completeness of the implementation.
- [ ] Code quality, including readability, use of best practices, and adherence to Java coding conventions.
- [ ] Design and architecture of the solution, including the use of design patterns where appropriate.
- [ ] Effectiveness and coverage of unit tests.

## Appendix 

**A: Department/Bonus Percentage Table**
   
| Department	| Bonus Percentage|
| --- | --- |
| Engineering |	10% |
| Human Resources| 8% |
| Marketing | 12% |
| Sales |	15% |
| IT | 9% |
