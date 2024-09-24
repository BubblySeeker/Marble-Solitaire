# Marble-Solitaire

This project is a Java-based implementation of Marble Solitaire, a classic puzzle game, extended to include multiple variations of the game board. The codebase is organized into different packages that handle specific aspects of the game:

- Model: This includes classes for different board types—European and Triangle—each adhering to a common model interface that defines the core functionalities of the game.


- View: There are view classes that display the game state to the user in text format. A special view class is dedicated to handling the unique layout of the triangular board.


- Controller: The controller interfaces remain unchanged, ensuring compatibility with all game models.


- Main Application: The entry point of the application processes command-line arguments to configure and start the game with user-specified settings like board type and size.


The design uses the Model-View-Controller (MVC) architecture to separate the game logic from user interface concerns, facilitating easy updates and maintenance. Additionally, an optional design using the abstract factory pattern allows for dynamically pairing models with their respective views, enhancing the flexibility and scalability of the application.

This structured approach ensures that the application can be easily extended to include new variations of Marble Solitaire without significant changes to the existing codebase, emphasizing reusability and modular design.
