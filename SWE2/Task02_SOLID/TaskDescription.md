
Task Description

This task was implemented using the **C++ programming language** to demonstrate
the application of **SOLID principles** in a simple and clear example.

SOLID Principles Applied:

1. **Single Responsibility Principle (SRP)**  
   - The `Car` class is responsible only for car-related data and behavior.
   - The `CarInfoPrinter` class is responsible only for displaying car information,
     separating logic from presentation.

2. **Open/Closed Principle (OCP)**  
   - The system is open for extension but closed for modification.
   - New car types can be added by creating new classes that inherit from `Car`
     without changing existing code.

3. **Liskov Substitution Principle (LSP)**  
   - Objects of derived classes (`ElectricCar`, `GasCar`, `HybridCar`)
     can be used wherever a `Car` object is expected.
   - The `startCarEngine()` function works correctly with any `Car` type.

4. **Interface Segregation Principle (ISP)**  
   - The `IRechargeable` interface is used only by cars that support recharging
     (electric and hybrid cars).
   - Gas cars are not forced to implement unnecessary methods.

5. **Dependency Inversion Principle (DIP)**  
   - High-level functions depend on abstractions rather than concrete implementations.
   - The `startCarEngine()` function depends on the abstract `Car` class, not on specific car types.

Program Flow:
- Different types of cars are created based on their behavior.
- Car information is printed using a separate class.
- Engines are started polymorphically using a base class reference.
- Recharge functionality is applied only to applicable car types.

### Goal of the Task:
The goal of this task is to understand and apply SOLID principles in C++
to build a flexible, maintainable, and extensible software design.
