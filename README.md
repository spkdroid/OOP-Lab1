# Object Oriented Programming Lab

### Problem 1: Class Inheritance

1. Create a base class `Person` with attributes `name` and `age`.
2. Derive two classes, `Student` and `Teacher`, from `Person`.
3. Include appropriate constructors and methods in each class.
4. Demonstrate polymorphism by creating an array of `Person` objects and displaying information for each.

### Problem 2: Encapsulation and Abstraction

1. Design a class `BankAccount` with private attributes `accountNumber`, `balance`, and `accountHolderName`.
2. Encapsulate these attributes using getter and setter methods.
3. Implement a method `withdraw(double amount)` to deduct money from the account balance.
4. Create instances of the `BankAccount` class and demonstrate encapsulation and abstraction.

### Problem 3: Interface and Polymorphism

1. Define an interface `Drawable` with a method `draw()`.
2. Create classes `Circle` and `Square` that implement the `Drawable` interface.
3. Add unique methods to each class (e.g., `calculateArea()` for `Circle` and `calculatePerimeter()` for `Square`).
4. Demonstrate polymorphism by creating an array of `Drawable` objects and calling the `draw()` method on each.

### Problem 4: Composition

1. Create a class `Library` with attributes `name` and a list of `Book` objects.
2. Implement a method in the `Library` class to add a book to its collection.
3. Create instances of the `Library` and `Book` classes and showcase composition.

### Problem 5: Exception Handling

1. Create a class `TemperatureConverter` with a method `convertToFahrenheit(double celsius)` that converts Celsius to Fahrenheit.
2. Implement exception handling to handle invalid temperature values.
3. Demonstrate the usage of the `TemperatureConverter` class with different scenarios.

### Problem 6: Static Members

1. Create a class `Car` with a static variable `totalCars` to keep track of the number of cars created.
2. Implement a non-static method `startEngine()` that prints a message indicating the engine has started.
3. Demonstrate the usage of both static and non-static members.
