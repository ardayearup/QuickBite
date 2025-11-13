# 🥪 QuickBite

## 📖 About
This project implements a **command-line interface (CLI) point-of-sale (POS)** application for a custom sandwich shop.  
The application automates the order process, allowing customers to customize sandwiches, add drinks and chips, and generate receipts.  
It is designed with **Object-Oriented Programming (OOP)** principles, utilizing classes and interfaces to manage different menu items and the overall order flow.

---

## 🚀 Features

### 🏠 Home Screen
- Provides options to start a new order or exit the application.

### 🧾 Order Screen
- Allows customers to add sandwiches, drinks, or chips to their current order.
- Displays a summary of items currently in the order.

### 🥪 Add Sandwich
- **Custom Sandwiches:** Select bread type, sandwich size, and add various meats, cheeses, toppings, and sauces.
- **Signature Sandwiches:** Choose from predefined options (e.g., BLT, Philly Cheese Steak).
- **Customization:** Add or remove additional toppings, sauces, or sides.
- **Toasting Option:** Choose whether to toast the sandwich.
- **Extra Meat/Cheese:** Option to add “extra” portions, with cost adjustments based on sandwich size.

### 🥤 Add Drink
- Select a drink flavor and size.

### 🍟 Add Chips
- Choose a chip type.

### ❌ Remove Item from Order
- Remove specific sandwiches, drinks, or chips by selecting the item type and number.

### 💵 Checkout
- Displays the complete order details and total cost.
- Prompts for confirmation before finalizing the order.

### 🧾 Receipt Generation
- Upon confirmation, generates a detailed receipt file and saves it in a `receipts` folder.

### 🔒 Robust Input Handling
- All menu selections are number-based for a smoother user experience.

---

## ⚙️ Prerequisites
- **Java 17+** installed
- **IDE** (IntelliJ IDEA, VS Code, Eclipse) or a terminal

---

## 🧩 Installation & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ardayearup/QuickBite