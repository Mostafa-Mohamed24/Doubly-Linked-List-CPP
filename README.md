# Doubly Linked List (C++ Template Class)

A generic (templated) implementation of a Doubly Linked List data structure in C++, supporting any data type via templates.

## Features

- Generic template class clsDblLinkedList<T> — works with any data type
- Insert at the beginning, end, or after a specific node/index
- Delete the first node, last node, or a specific node
- Search for a value using Find()
- Get or update an item by index
- Reverse the entire list
- Print all elements
- Track list size and check if it's empty
- Clear the entire list

## Methods

| Method | Description |
|---|---|
| InsertAtBeginning(T Value) | Insert a new node at the beginning of the list |
| InsertAtEnd(T Value) | Insert a new node at the end of the list |
| InsertAfter(Node* Current, T Value) | Insert a new node after a given node |
| InsertAfter(int Index, T Value) | Insert a new node after a given index |
| Find(T Value) | Search for a node by value |
| DeleteNode(Node*& NodeToDelete) | Delete a specific node |
| DeleteFirstNode() | Delete the first node |
| DeleteLastNode() | Delete the last node |
| GetNode(int Index) | Get a node by its index |
| GetItem(int Index) | Get the value stored at a given index |
| UpdateItem(int Index, T NewValue) | Update the value at a given index |
| Reverse() | Reverse the list in place |
| PrintList() | Print all elements in the list |
| Size() | Return the number of elements |
| IsEmpty() | Check whether the list is empty |
| Clear() | Remove all nodes from the list |
