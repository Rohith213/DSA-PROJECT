# Email Management Console Application
## Data Structures and Algorithms Project

## Overview

This project is a simple console-based email management application that demonstrates the fundamental concepts of data structures. The primary intention behind this project is to explore and implement essential data structure functionalities, such as queues, file handling, and basic operations.

## Features

- **Email Management**: The application allows users to create, delete, and read emails.
- **Queue Implementation**: A queue data structure is employed to manage email files in a first-in-first-out (FIFO) manner.
- **File Handling**: The project involves file handling operations to store and retrieve email data.

## Data Structures Used

### Queue

The queue is used to manage the email files. It provides the following functionalities:

- **Initialization**: Initialize an empty queue.
- **Enqueue**: Add an email file to the end of the queue.
- **Dequeue**: Remove an email file from the front of the queue.
- **isEmpty**: Check if the queue is empty.
- **isFull**: Check if the queue is full.

### Structs

- **Email Struct**: Represents an email with sender, subject, and message fields.
- **Queue Struct**: Manages the email files using a circular queue.

## How to Use

1. **Compile**: Compile the source code using a C compiler.
2. **Run**: Execute the compiled program.
3. **Choose Operation**: Follow the on-screen menu to create, delete, or read emails.

## Project Structure

- `main.c`: Main source code file containing the program logic.
- `emails.txt`: File to store email data.
- `mails.txt`: File to keep track of email file names in the queue.

## Getting Started

To run the project locally, clone the repository and compile the `main.c` file. Ensure that the necessary dependencies are installed.

```bash
git clone https://github.com/Rohith213/Email-Management-Console-Application.git
cd email-management
gcc mail.c -o email_manager
./email_manager