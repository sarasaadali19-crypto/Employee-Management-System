# Employee-Management-System
Employee Management System using C++ and OOP.




Employee Management System

1. Project Description

The Employee Management System is a C++ console application designed to manage employee information. It allows users to enter employee details, calculate salaries, and display employee records.

2. Project Objectives

* Enter employee ID and name.
* Store employee salary information.
* Calculate the total salary, including monthly allowance.
* Calculate salary with an additional bonus.
* Display employee information clearly.
* Apply Object-Oriented Programming (OOP) concepts.

3. OOP Concepts Applied

Classes and Objects

The program contains two classes: Employee and FullTimeEmployee. The employee object is created from the FullTimeEmployee class.

Encapsulation

Employee data members are declared private. Public member functions provide controlled access to selected data.

Constructors

Constructors initialize employee information when an object is created.

Destructors

Destructors are defined in the base and derived classes to support proper object destruction.

Inheritance

The FullTimeEmployee class inherits from the Employee class.

Polymorphism

The program demonstrates polymorphism by calling an overridden function through a base-class pointer.

Function Overloading

The calculateSalary() function has two versions: one calculates the regular salary, and the other calculates the salary with an additional bonus.

Access Modifiers

The program uses private, protected, and public to control access to class members.

Virtual Functions

The display() and calculateSalary() functions are virtual in the base class and overridden in the derived class.

4. How the Program Works

1. The user enters the employee ID.
2. The user enters the employee name.
3. The user enters the basic salary.
4. The user enters the monthly allowance.
5. The program displays the employee information and total salary.
6. The user enters a bonus.
7. The program displays the salary including the bonus.

5. How to Compile and Run

Save the source code as main.cpp.

Compile the program using a C++ compiler:

g++ -std=c++11 main.cpp -o employee_management

Run the program on Linux or macOS:

./employee_management

6. Programming Language

C++

7. Author


Sara Saad Ali 
