# DDS-PROJECT-LIST-
Tower of Hanoi Visualizer
Overview
The Tower of Hanoi is a classic algorithmic problem that involves moving a set of disks from one rod to another, following specific rules:

Only one disk can be moved at a time.
A disk can only be placed on top of a larger disk or on an empty rod.
The goal is to move all disks from the source rod to the destination rod using an auxiliary rod.
This implementation uses recursion to solve the Tower of Hanoi problem and provides an ASCII-based visual output to illustrate the movements of the disks.

Features
Recursive Solution: The program uses a recursive algorithm to solve the Tower of Hanoi problem.
Visual Output: The current state of the rods is displayed after each move, allowing users to visualize the process.
Delay for Visualization: A short delay is introduced between moves to enhance the visual effect of the disk movements.
Dynamic Disk Count: Users can specify the number of disks at runtime.


How to Run the Code
Open your terminal or command prompt.
Navigate to the directory where you saved the code.
Run the following command to compile the code:
g++ tower_of_hanoi.cpp -o tower_of_hanoi -pthread

E-Library Book Management System
Overview
The E-Library Book Management System allows users to manage a collection of books by borrowing and returning them. It utilizes a linked list to maintain an inventory of books and a stack to implement undo functionality for recent actions. Users can search for books by title or author and view the current state of the inventory.

Features
Linked List for Inventory: The system uses a linked list to store and manage the collection of books.
Stack for Undo Functionality: A stack is used to keep track of recent actions, allowing users to undo their last action (either borrowing or returning a book).
Search and Filter: Users can search for books by title or author.
Display Available Books: The system can display all currently available books that are not borrowed.
User Interaction: A simple text-based menu allows users to interact with the system.

How to Run the Code
Open your terminal or command prompt.
Navigate to the directory where you saved the code.
Run the following command to compile the code:
g++ e_library.cpp -o e_library

Personal Tracker Application
Overview
The Personal Tracker Application is designed to help users manage and track various personal goals or tasks. It allows users to add, view, and delete tasks, providing a simple text-based interface for interaction. The tasks are stored in a linked list, enabling efficient management of the task list.

Features
Linked List for Task Management: The application uses a linked list to store tasks, allowing for dynamic addition and removal of tasks.
Add Tasks: Users can add new tasks with a description.
View Tasks: Users can view all current tasks in the list.
Delete Tasks: Users can delete tasks by specifying their index in the list.
Simple Text-Based Interface: The application provides an easy-to-use menu for user interaction.


How to Run the Code
Open your terminal or command prompt.
Navigate to the directory where you saved the code.
Run the following command to compile the code:
g++ personal_tracker.cpp -o personal_tracker
