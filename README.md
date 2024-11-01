# Sleeping-TA-Assignment
Sleeping Teaching Assistant

This project simulates the "Sleeping Teaching Assistant" problem, a classic multithreading and synchronization problem. Using POSIX threads, mutexes, and semaphores, this program models a teaching assistant (TA) helping students in a small office with limited seating. The TA sleeps when no students are waiting and helps each student in turn when they arrive.
Table of Contents

    Problem Description
    Key Concepts
    Features
    Project Structure
    Setup and Compilation
    Usage
    Example Output
    Notes
    License

Problem Description

A university TA helps students with programming assignments during regular office hours. The TA's office can only fit one desk, and there are three chairs outside the office where students can wait. Here’s how the simulation works:

    If no students are waiting, the TA sleeps at the desk.
    When a student arrives and finds the TA sleeping, they wake up the TA for assistance.
    If the TA is busy helping another student and there are available chairs, the student waits.
    If no chairs are available, the student leaves and returns later.

This project uses POSIX threads to simulate multiple students and a TA working concurrently, employing semaphores and mutex locks to manage synchronization and prevent race conditions.
Key Concepts

This project reinforces the following concepts:

    Multithreading with POSIX threads (pthread library)
    Synchronization with mutexes and semaphores
    Classical Synchronization Problems: Modeled after the "Sleeping Barber" problem, a common scenario in operating systems coursework.
    Concurrency Control in resource-limited environments

Features

    Simulates multiple students who periodically seek help from the TA.
    Implements the TA as a thread that alternates between napping and helping students.
    Uses semaphores and mutexes to handle student-TA interactions and manage shared resources safely.
    Randomized sleep times to simulate realistic programming and helping times.

Project Structure

    sleeping_ta.c: Contains the main code for the TA-student simulation.
    README.md: Project documentation.
    Makefile (optional): Can be included to automate compilation.

Setup and Compilation
Prerequisites

    gcc: This project uses gcc for compiling C code. Ensure it is installed on your machine.
    POSIX Threads (pthread): This project relies on pthread, available on most Unix-like systems (Linux, macOS). On Windows, POSIX compatibility libraries like Cygwin or MinGW are required.

Compilation

To compile the code, use the following command in your terminal:

bash
gcc -pthread sleeping_ta.c -o sleeping_ta
Certainly! Here’s a README.md template for your "Sleeping Teaching Assistant" project, outlining the problem, setup, usage, and key features. This template will help others understand your project on GitHub.
Sleeping Teaching Assistant

This project simulates the "Sleeping Teaching Assistant" problem, a classic multithreading and synchronization problem. Using POSIX threads, mutexes, and semaphores, this program models a teaching assistant (TA) helping students in a small office with limited seating. The TA sleeps when no students are waiting and helps each student in turn when they arrive.
Table of Contents

    Problem Description
    Key Concepts
    Features
    Project Structure
    Setup and Compilation
    Usage
    Example Output
    Notes
    License

Problem Description

A university TA helps students with programming assignments during regular office hours. The TA's office can only fit one desk, and there are three chairs outside the office where students can wait. Here’s how the simulation works:

    If no students are waiting, the TA sleeps at the desk.
    When a student arrives and finds the TA sleeping, they wake up the TA for assistance.
    If the TA is busy helping another student and there are available chairs, the student waits.
    If no chairs are available, the student leaves and returns later.

This project uses POSIX threads to simulate multiple students and a TA working concurrently, employing semaphores and mutex locks to manage synchronization and prevent race conditions.
Key Concepts

This project reinforces the following concepts:

    Multithreading with POSIX threads (pthread library)
    Synchronization with mutexes and semaphores
    Classical Synchronization Problems: Modeled after the "Sleeping Barber" problem, a common scenario in operating systems coursework.
    Concurrency Control in resource-limited environments

Features

    Simulates multiple students who periodically seek help from the TA.
    Implements the TA as a thread that alternates between napping and helping students.
    Uses semaphores and mutexes to handle student-TA interactions and manage shared resources safely.
    Randomized sleep times to simulate realistic programming and helping times.

Project Structure

    sleeping_ta.c: Contains the main code for the TA-student simulation.
    README.md: Project documentation.
    Makefile (optional): Can be included to automate compilation.

Setup and Compilation
Prerequisites

    gcc: This project uses gcc for compiling C code. Ensure it is installed on your machine.
    POSIX Threads (pthread): This project relies on pthread, available on most Unix-like systems (Linux, macOS). On Windows, POSIX compatibility libraries like Cygwin or MinGW are required.

Compilation

To compile the code, use the following command in your terminal:

bash

gcc -pthread sleeping_ta.c -o sleeping_ta

This will create an executable named sleeping_ta.
Usage

To run the simulation:
bash
./sleeping_ta

The program will run indefinitely, simulating the TA helping students. To stop it, use Ctrl+C.

Certainly! Here’s a README.md template for your "Sleeping Teaching Assistant" project, outlining the problem, setup, usage, and key features. This template will help others understand your project on GitHub.
Sleeping Teaching Assistant

This project simulates the "Sleeping Teaching Assistant" problem, a classic multithreading and synchronization problem. Using POSIX threads, mutexes, and semaphores, this program models a teaching assistant (TA) helping students in a small office with limited seating. The TA sleeps when no students are waiting and helps each student in turn when they arrive.
Table of Contents

    Problem Description
    Key Concepts
    Features
    Project Structure
    Setup and Compilation
    Usage
    Example Output
    Notes
    License

Problem Description

A university TA helps students with programming assignments during regular office hours. The TA's office can only fit one desk, and there are three chairs outside the office where students can wait. Here’s how the simulation works:

    If no students are waiting, the TA sleeps at the desk.
    When a student arrives and finds the TA sleeping, they wake up the TA for assistance.
    If the TA is busy helping another student and there are available chairs, the student waits.
    If no chairs are available, the student leaves and returns later.

This project uses POSIX threads to simulate multiple students and a TA working concurrently, employing semaphores and mutex locks to manage synchronization and prevent race conditions.
Key Concepts

This project reinforces the following concepts:

    Multithreading with POSIX threads (pthread library)
    Synchronization with mutexes and semaphores
    Classical Synchronization Problems: Modeled after the "Sleeping Barber" problem, a common scenario in operating systems coursework.
    Concurrency Control in resource-limited environments

Features

    Simulates multiple students who periodically seek help from the TA.
    Implements the TA as a thread that alternates between napping and helping students.
    Uses semaphores and mutexes to handle student-TA interactions and manage shared resources safely.
    Randomized sleep times to simulate realistic programming and helping times.

Project Structure

    sleeping_ta.c: Contains the main code for the TA-student simulation.
    README.md: Project documentation.
    Makefile (optional): Can be included to automate compilation.

Setup and Compilation
Prerequisites

    gcc: This project uses gcc for compiling C code. Ensure it is installed on your machine.
    POSIX Threads (pthread): This project relies on pthread, available on most Unix-like systems (Linux, macOS). On Windows, POSIX compatibility libraries like Cygwin or MinGW are required.

Compilation

To compile the code, use the following command in your terminal:

bash

gcc -pthread sleeping_ta.c -o sleeping_ta

This will create an executable named sleeping_ta.
Usage

To run the simulation:

bash

./sleeping_ta

The program will run indefinitely, simulating the TA helping students. 
To stop it, use Ctrl+C.

Example Output

The following is an example of what you might see in the terminal:

Student 1 is programming.
Student 2 is programming.
Student 1 is waiting for the TA. Students waiting: 1
TA is helping a student. Students waiting: 0
Student 3 is programming.
Student 2 is waiting for the TA. Students waiting: 1
Student 4 is programming.
TA is helping a student. Students waiting: 0
...

In this output:

    Student X is programming: The student is working on their assignment.
    Student X is waiting for the TA: The student is waiting in line.
    TA is helping a student: The TA is assisting a student.
Notes

    Infinite Simulation: The simulation runs indefinitely to simulate ongoing office hours. Use Ctrl+C to terminate.
    Adjustable Parameters: You can modify NUM_STUDENTS and NUM_CHAIRS in the code to simulate different scenarios.
    Concurrency Control: Mutexes and semaphores prevent race conditions and ensure only one student is assisted at a time

