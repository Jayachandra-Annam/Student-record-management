# Student Record Management System

A simple **Student Record Management System in C** using a **Singly Linked List (SLL)**.

This project allows the user to add, display, modify, delete, save, sort, reverse, and delete all student records.

## Features

- Add a new student record
- Automatically generate a unique roll number
- Display all student records
- Modify a student record
- Delete a particular student record
- Delete all student records
- Sort students by name
- Reverse the linked list
- Save student records into a file
- Exit the program

## Student Information

Each student record contains:

- Roll Number
- Name
- Percentage
- Pointer to the next student record

The structure used is:

```c
typedef struct student
{
    int rollno;
    char name[20];
    float percentage;
    struct student *next;
} SLL;
