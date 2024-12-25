# Mobile Store Management System

## Overview

The **Mobile Store Management System** is a console-based Java application that allows a user to manage the inventory of a mobile store. The system includes functionalities for adding new mobiles and accessories, searching items by name or brand, managing stock levels, and displaying all available products with their details.

The system is built using **Object-Oriented Programming (OOP)** principles such as classes, objects, inheritance, and exception handling.

---

## Features

1. **Add New Products:**
   - Add new mobiles and accessories (like covers, glasses, etc.) to the store's inventory.
   
2. **Search for Products:**
   - Search products based on name or brand to quickly locate them in the storemanagementlogic file.
   
3. **Manage Stock Levels:**
   - Increase or decrease stock quantities for any product.
   
4. **Display All Products:**
   - View a list of all available products, including their details such as name, brand, price, and available quantity.

---

## Technologies Used

- **Java SE**: The project is developed using Java Standard Edition.
- **Object-Oriented Programming (OOP)**: The application uses OOP concepts such as classes, inheritance, and exception handling to manage the store's inventory.

---

## Class Overview

### `Product` (Base Class)
- The base class representing a general product in the store.
- Contains attributes: `name`, `brand`, `price`, and `quantity`.

### `Mobile` (Subclass of `Product`)
- Represents a mobile phone product in the store.
- Inherits from the `Product` class and can include mobile-specific attributes and methods.

### `Accessory` (Subclass of `Product`)
- Represents an accessory (like phone covers or glasses) in the store.
- Inherits from the `Product` class and adds accessory-specific behaviors.

### `StoreManagementLogic`
- Manages the collection of products in the store.
- Provides methods for adding products, searching by name or brand, and manage stock quantities, display all product.

---

## Installation

### Prerequisites

1. **Java**: Make sure you have Java Development Kit (JDK) installed (Java SE 8 or higher).
   - You can download the latest version of JDK from [Oracle's official website](https://www.oracle.com/java/technologies/javase-downloads.html).
   
2. **IDE (optional)**: You can use any Java IDE like IntelliJ IDEA, Eclipse, or even a text editor like VSCode.

---

