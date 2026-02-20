☕️ Coffee Machine Simulator (OOP)
This project is a Python-based Coffee Machine Simulation that demonstrates the core principles of Object-Oriented Programming (OOP), specifically encapsulation, abstraction, and modularity. It mimics the logic of a real-world vending machine, managing everything from ingredient inventory to coin-based financial transactions.

🚀 Features
Modular Architecture: The system is split into four distinct classes to maintain a "Separation of Concerns".

Resource Management: Tracks real-time levels of water, milk, and coffee.

Payment Processing: A built-in money machine that accepts quarters, dimes, nickels, and pennies, calculates change, and tracks total profit.

Inventory Validation: Automatically checks if resources are sufficient before accepting a payment.

Maintenance Commands:

report: Generates a status update on current resources and earnings.

off: Safely shuts down the machine simulation.

📂 Project Structure
The project is organized into the following modules:

main.py: The entry point of the application. It runs the execution loop and coordinates interactions between the classes.

coffee_maker.py: Contains the CoffeeMaker class, which manages the physical ingredients and "brews" the coffee.

menu.py: Houses the Menu and MenuItem classes, responsible for storing drink data and handling menu searches.

money_machine.py: Contains the MoneyMachine class, which processes coin inputs and manages the machine's profit.

🛠 Installation & Usage
Clone the repository:

Bash
git clone https://github.com/yourusername/coffee-machine-python.git
Navigate to the project directory:

Bash
cd coffee-machine-python
Run the application:

Bash
python main.py
🧪 Example Interaction
Plaintext
What would you like? (latte/espresso/cappuccino/): latte
Please insert coins.
How many quarters?: 12
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $0.5 in change.
Here is your latte ☕️. Enjoy!
👨‍💻 Author
Aditya Verma B.Tech in Information Technology | Chhatrapati Shahu Ji Maharaj University
