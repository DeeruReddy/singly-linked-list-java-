# Singly Linked List Implementations in Java

This repository contains various implementations of singly linked lists in Java, each demonstrating different operations such as insertion, deletion, searching, and more.

## Files Overview

1. **EndInsertDeleteBeginning.java**
   - Implements a singly linked list with insertion at the end and deletion at the beginning.

2. **EndInsertEndDelete.java**
   - Implements a singly linked list with insertion and deletion operations at the end.

3. **Insert.java**
   - Basic implementation of a singly linked list with insertion at the end.

4. **InsertatEnd.java**
   - Similar to `Insert.java`, provides end insertion functionality for a singly linked list.

5. **InsertatEndDeletebyValue.java**
   - Implements a singly linked list with insertion at the end and deletion based on a given value.

6. **InsertatStart.java**
   - Demonstrates insertion at the beginning of a singly linked list.

7. **InsertEndReverseList.java**
   - Implements a singly linked list with insertion at the end and functionality to reverse the list.

8. **SearchOperation.java**
   - Provides search functionality within a singly linked list.

9. **SortedInsertion.java**
   - Implements a singly linked list with sorted insertion, maintaining the list in ascending order.

## Usage

Each file is a standalone Java program. To run any of them:
1. Compile the file using `javac <filename>.java`.
2. Run the compiled program using `java <filename>`.
3. Follow the on-screen instructions (if any) to input data or perform operations.

## Features

- **Insertion**: At beginning, end, or in a sorted manner.
- **Deletion**: At beginning, end, or by value.
- **Searching**: Check if an element exists in the list.
- **Reversal**: Reverse the entire linked list.

## Example

For example, to use `InsertatEndDeletebyValue.java`:
1. Input numbers one by one (enter `-1` to stop).
2. Enter the value to delete.
3. The program will display the updated list after deletion.

## Notes

- All programs use a `Scanner` for input and close it after use.
- The linked list nodes are defined using a nested static class `SLLNode`.
- Each program includes a display function to print the list contents.

Feel free to explore and modify the code as needed!
