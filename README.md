**Technical Task: Vending Machine Application**

### Objective
Develop a console-based vending machine application to assess Java and Object-Oriented Programming (OOP) knowledge.

### Requirements
1. **Product Management:**
   - Implement an abstract class `Item` with the following properties:
     - `name` (String): Product name
     - `price` (double): Product price
     - `quantity` (int): Available stock
   - Create the following subclasses extending `Item`:
     - `Coke`
     - `Fanta`
     - `Sprite`
     - `Water`
     - `Juice`

2. **Vending Machine Functionality:**
   - Display a list of available items with their prices and quantities.
   - Allow the user to select a product by entering its name.
   - If the selected product is out of stock, display an appropriate message.
   - Prompt the user to enter money.
   - If the entered amount is less than the product price, prompt the user to add more money.
   - Once the required amount is entered:
     - Dispense the selected product.
     - Deduct the purchased quantity from the stock.
     - Display a message if the selected product is `Coke`: **"Better to drink it cold!"**
     - Return any change if applicable.
   - After the transaction, return to the menu with the updated product list.

3. **Constraints:**
   - Store items in memory (no database required).
   - Use OOP principles, including abstraction, encapsulation, and polymorphism.

4. **Evaluation Criteria:**
   - Correct use of classes and inheritance.
   - Proper implementation of encapsulation.
   - Handling of user input and exceptions.
   - Code readability and maintainability.

### Deliverables
- Java source code implementing the vending machine logic.
- A short description of the design approach if necessary.

This task will help evaluate the student's ability to design an OOP-based application while managing user interactions and handling transactions in a vending machine scenario.
