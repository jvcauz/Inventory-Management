# Inventory Management System

A simple inventory management system developed in Java to practice fundamental programming concepts, including:

- Arrays
- Loops (for and do-while)
- Conditional statements (if/else)
- User input handling with Scanner
- Basic inventory management logic

## Language

The application interface is currently available in Portuguese (Brazil).

## Features

The system allows the user to:

- Register up to 4 products
- View the current inventory
- Add units to a product
- Remove units from a product
- Prevent removal when there is insufficient stock
- Navigate through an interactive console menu

## Requirements

- JDK 21 (or newer)

## Running the Project

Compile the source file:

```bash
javac Gerenciador.java
```

Run the application:

```bash
java Gerenciador
```

## Example Menu

```text
------ MENU ------
1. Exibir Estoque
2. Adicionar Itens
3. Remover Itens
4. Sair
>
```

## Example Output

```text
Nome: Mouse | Quantidade: 15
Nome: Teclado | Quantidade: 8
Nome: Monitor | Quantidade: 5
Nome: Headset | Quantidade: 12
```

## Learning Objectives

This project was created as a learning exercise to strengthen skills in:

- Programming logic
- Data structures using arrays
- User interaction through the console
- Inventory control algorithms
- Java fundamentals

## Future Improvements

- Support an unlimited number of products
- Product search functionality
- Product categories
- Input validation and exception handling
- Refactor the project using Object-Oriented Programming with a Product class
- Data persistence using MySQL
- Integration with MySQL through JDBC for inventory storage and management
- Development of a REST API to expose inventory operations (create, read, update, and delete products)
- Migration from an array-based structure to a database-driven architecture
