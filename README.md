# todolist

A Flutter program for adding notes and managing tasks, developed by Mohammad Hossein Khan Mohammadi (vishko).

![The main image of the Todolist program](https://github.com/mrvishko/MyTodoList/assets/93584165/33fda999-d7ef-4f4b-a3d6-17e77b7287db)

This program is a Flutter application that manages a Todo list. Below are the features and actions that this program performs:

1. **Display and Management of Todo List**: The application has a main page that displays a Todo list. Each Todo includes a title and an index number.

2. **Adding Todo**: Users can add a new Todo using a text field and an "Add Todo" button. The new Todo is added to the list, and the data is saved in the list.

3. **Deleting Todo**: Each Todo has a delete button that, when pressed, removes the corresponding Todo from the list, and the changes are saved in the list.

4. **Saving and Retrieving from SharedPreferences**: The program uses `SharedPreferences` to save and retrieve the Todo list. When the program runs, the Todo list is retrieved from SharedPreferences, and when a Todo is added or removed, the changes are saved in SharedPreferences.

5. **User Interface (UI) Design**: Various Flutter widgets and designs, including AppBar, Card, TextField, ElevatedButton, and ListView, are used to create the user interface.

6. **Combination of StatefulWidget and StatelessWidget Architecture**: The program uses the StatefulWidget architecture to manage the state and the StatelessWidget for drawing the user interface.

With these explanations, this program allows users to add and manage Todos and uses `SharedPreferences` to store and retrieve data for future use.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
