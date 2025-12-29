OOP Task Description 

This task was implemented using the **C++ programming language** to demonstrate
basic **Object-Oriented Programming (OOP)** concepts.

Concepts Applied:

1. **Classes and Objects**  
   - Created a base class `Car` that represents a general car.
   - Created objects from derived classes in the `main` function.

2. **Encapsulation**  
   - Used private data members (`brand`, `year`) inside the `Car` class.
   - Provided public setter and getter methods to control access to data.

3. **Inheritance**  
   - Derived three classes from `Car`:
     - `ElectricCar`
     - `GasCar`
     - `HybridCar`

4. **Polymorphism**  
   - Declared the `start()` function as a **pure virtual function** in the base class.
   - Overrode the `start()` function in each derived class to provide
     different behavior based on the car type.

5. **Abstraction**  
   - Used an abstract class (`Car`) to define a common interface for all car types.

Program Flow:
- Objects of different car types are created (`ElectricCar`, `GasCar`, `HybridCar`).
- Car information such as brand and year is displayed using the `showInfo()` method.
- Ea
