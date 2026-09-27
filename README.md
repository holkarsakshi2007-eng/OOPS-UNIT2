Sakshi Dadaso Holkar

126UAD2007

SY-F

## Object-Oriented programing

Unit-2

Programs:

1 Basic single inheritance

2 Protected member access 

3 Public versus private inheritance

4 Multilevel inheritance 

5 Hierarchical inheritance 

6 Multiple inheritance 

7 Multiple-inheritance ambiguity 

8 Constructor and destructor order

9 Parameterized base constructor

10 Function overriding 

11 Abstract class

12 Virtual base class 

13 Friend class 

14 Nested class 

15 Mini-project: Vehicle rental 



#  Inheritance 
 
Welcome to the Inheritance module of my C++ Object-Oriented Programming collection! This branch of code focuses entirely on how classes inherit attributes, methods, and behaviors from parent classes—a fundamental mechanism for building scalable and reusable C++ software architectures.
This repository section dives deep into **code reusability, hierarchical class relationships, polymorphism, and advanced architectural concepts** like virtual base classes and abstract interfaces.





| S.No. | Topic / Concept | Description |
| :---: | :--- | :--- |
| **1** | **Basic Single Inheritance** | Deriving a new class from a single base class to inherit properties and methods. |
| **2** | **Protected Member Access** | Utilizing `protected` visibility to allow derived class access while keeping data hidden from the outside world. |
| **3** | **Public vs. Private Inheritance** | Exploring how inheritance modes alter the accessibility of base class members in derived classes. |
| **4** | **Multilevel Inheritance** | Building a chain of inheritance where a class is derived from another derived class (A -> B -> C). |
| **5** | **Hierarchical Inheritance** | Multiple derived classes inheriting from a single common base class. |
| **6** | **Multiple Inheritance** | Deriving a single class from two or more base classes simultaneously. |
| **7** | **Multiple-Inheritance Ambiguity** | Resolving naming conflicts (the Diamond Problem / scope resolution) when inheriting from multiple classes. |
| **8** | **Constructor & Destructor Order** | Tracking the precise execution sequence of base and derived constructors/destructors during object lifecycle. |
| **9** | **Parameterized Base Constructor** | Passing arguments from a derived class constructor up to the base class constructor. |
| **10** | **Function Overriding** | Redefining base class member functions in a derived class for dynamic behavior. |
| **11** | **Abstract Class** | Creating interfaces using pure virtual functions (`= 0`) that must be implemented by derived classes. |
| **12** | **Virtual Base Class** | Eliminating duplicate copies of a shared base class in complex inheritance networks. |
| **13** | **Friend Class** | Granting a separate external class full access to private and protected members of another class. |
| **14** | **Nested Class** | Declaring a class inside another class to logically group tightly coupled components. |
| **15** | **Mini-Project: Vehicle Rental** | A capstone application implementing inheritance, polymorphism, and class hierarchies to manage vehicle bookings. |

---

## Capstone Mini-Project: Vehicle Rental System

The **Vehicle Rental System** brings together the core concepts of this unit. It showcases:
* **Base & Derived Classes:** General `Vehicle` class extended into specialized types (e.g., `Car`, `Bike`, `Truck`).
* **Polymorphism & Overriding:** Dynamic calculation of rental costs and feature display.
* **Encapsulation:** Managing customer records, rental status, and inventory safely.

---

## 🛠️ Compilation & Execution

To compile and test any of the programs in this unit, use your standard C++ terminal compiler:

```bash
# Navigate to the specific program directory
cd "Folder-Name"

# Compile the source file
g++ program_name.cpp -o output

# Run the executable
./output
