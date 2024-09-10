**
ETH Deposit Tracker**
The ETH Deposit Tracker is a TypeScript-based application that monitors Ethereum deposits on the blockchain. It tracks deposit transactions, stores them in a MongoDB database, and sends notifications via Telegram when new deposits are detected.

**Prerequisites**
Before you start, ensure you have the following installed:


**Entities:**
Core business logic and domain models.
Use Cases: Application-specific business rules.
Interface Adapters: Presenters, controllers, and gateways.
Frameworks and Drivers: External frameworks and tools (database, web framework, etc.).
SOLID principles were applied throughout the development:

Single Responsibility Principle: Each class and module has a single, well-defined responsibility.
Open-Closed Principle: The system is open for extension but closed for modification.
Liskov Substitution Principle: Objects of a superclass are replaceable with objects of its subclasses without affecting the correctness of the program.
Interface Segregation Principle: Clients are not forced to depend on interfaces they do not use.
Dependency Inversion Principle: High-level modules do not depend on low-level modules. Both depend on abstractions.
Flexibility
The ETH Deposit Tracker was designed with flexibility in mind. It can be easily configured to listen for any token from any blockchain by simply configuring a context for each one. This modular approach allows for easy expansion to support multiple cryptocurrencies and blockchains without significant changes to the core architecture.
