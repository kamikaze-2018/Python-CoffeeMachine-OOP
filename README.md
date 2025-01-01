# Coffee Machine

This Python project simulates a coffee machine. Users can select drinks from the menu, and the program manages resources (like water, milk, and coffee), processes payments, and provides a report of the machine's status.

## Features

- Menu with three drink options: **Latte**, **Espresso**, and **Cappuccino**.
- Resource management to ensure sufficient ingredients for drinks.
- Coin-based payment processing.
- Reports on current resources and profit.
- User-friendly interface for interaction.

## Project Structure

The project contains the following classes:

### `CoffeeMaker`
- Manages resources (water, milk, coffee).
- Provides a resource report.
- Checks if resources are sufficient for a selected drink.
- Deducts resources when a drink is made.

### `Menu` and `MenuItem`
- `Menu`: Stores available drinks and their ingredients.
- `MenuItem`: Represents a drink on the menu, including its ingredients and cost.

### `MoneyMachine`
- Handles payment transactions.
- Processes coins inserted by the user.
- Ensures sufficient payment for the drink and provides change if applicable.
- Tracks total profit.

## How to Use

1. Clone the repository to your local machine.
   ```bash
   git clone <repository_url>
   ```
2. Run the program using Python:
   ```bash
   python main.py
   ```
3. Follow the prompts to:
   - Select a drink from the menu.
   - Insert coins to make the payment.
   - View a report of the machine's resources and profits.
   - Turn off the machine by typing `off`.

## Example Interaction

```
What would you like? (latte/espresso/cappuccino): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $0.5 in change.
Here is your latte ☕️. Enjoy!
```

## Dependencies

This project requires Python 3.x. No additional libraries are needed.

## Project Files

- `coffee_maker.py`: Defines the `CoffeeMaker` class.
- `menu.py`: Defines the `Menu` and `MenuItem` classes.
- `money_machine.py`: Defines the `MoneyMachine` class.
- `main.py`: Contains the main logic for the program.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Acknowledgments

This project is inspired by educational programming exercises to simulate real-world systems in Python.
