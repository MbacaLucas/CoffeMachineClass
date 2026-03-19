# Simple Coffee Machine (C++ Learning Project)

A simple console-based coffee machine simulator built to practice **Object-Oriented Programming (OOP)** fundamentals in C++.

## 🚀 Features
- **Encapsulation**: Private resource management (`waterLevel`, `coffeeBeans`).
- **Data Validation**: Prevention of negative resource inputs via constructor and methods.
- **Resource Monitoring**: Status reporting and precise error diagnostics.
- **Const Correctness**: Proper use of `const` for read-only methods.

## 📖 How it Works
The machine requires at least **200ml of water** and **15g of coffee beans** to brew a single cup.
1. Create an instance of `CoffeMachine`.
2. Use `makeCoffe()` to attempt brewing.
3. If resources are low, use `addIngredients()` to refill.
4. Use `showStatus()` to monitor levels at any time.

## 🎓 Learning Objectives
- Understanding `private` vs `public` access modifiers.
- Implementing constructors with logic.
- Using method delegation (calling private methods from public ones).
- Managing internal state consistency.
