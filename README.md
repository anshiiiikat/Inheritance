# 🧬 Inheritance in C++

## 🎯 Aim

To implement and understand different types of inheritance in C++.

---

## ✅ Objectives

- Understand the concept of inheritance in Object-Oriented Programming (OOP).
- Demonstrate **single**, **multilevel**, **hierarchical**, and **multiple inheritance** through real-life inspired C++ programs.
- Model real-world "is-a" relationships using inheritance.

---

## 📚 Theory

### What is Inheritance?

Inheritance is a fundamental concept of Object-Oriented Programming (OOP) that allows a **derived (child) class** to inherit properties and behaviors (methods and attributes) from a **base (parent) class**.

It enables:

- **Code reusability**
- **Reduction in redundancy**
- **Logical class hierarchy**

### Key Concepts

- **Base Class (Parent Class)**  
  Provides common attributes and methods.

- **Derived Class (Child Class)**  
  Inherits from the base class and can add or override methods and attributes.

- **Access Specifiers**  
  - `public`: Accessible from outside the class.  
  - `protected`: Accessible within base and derived classes.  
  - `private`: Not accessible in derived classes.

---

## 🧱 Types of Inheritance in C++

### 1. Single Inheritance
> One base → One derived class  
**Example:** `College → Branch`

### 2. Multilevel Inheritance
> A chain of inheritance  
**Example:** `Mobile → Origin → Brand`

### 3. Hierarchical Inheritance
> One base → Multiple derived classes  
**Example:** `Clothes → Jeans, Tops, Sweater`

### 4. Multiple Inheritance
> One derived class inherits from multiple base classes  
**Example:** `Automobile + Features → Car`

### 5. Hybrid Inheritance
> Combination of two or more types  
Note: May lead to the **Diamond Problem**, which is resolved using **virtual inheritance** in C++.

---

## ✅ Advantages of Inheritance

- Encourages **code reuse** and **reduces redundancy**.
- Helps in making programs **modular** and **organized**.
- Allows **extension** and **specialization** of base classes.
- Supports **polymorphism** and **dynamic binding**.
- Models **real-world relationships** effectively.

---

## ⚠️ Limitations

- Increases **coupling** between base and derived classes.
- **Multiple inheritance** may lead to ambiguity.
- **Multilevel inheritance** can be overly complex if not designed carefully.
- **Misuse** of inheritance can result in **hard-to-maintain code**.

---

## Flowcharts

