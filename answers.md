# COMP 271 002 F17 Lab 3

# Team project: Daria AND Jamsion

# Objectives


1. *testList list.remove(5)  simply removes the fifth element of the list. 
2. *testList list.remove(Integer.valueOf(5) removes the int from 5 in list.
3. *testList using LinkedList didn't create any change to the code
4. *testIterator linkedlist addition doesn't do anything different to the code
5. *tesIterator list.remove(77) will try the remove the 77th element which doesn't exist so you will get an error
6. run times overall it takes Linked list a lot more time i.e access
- size 10: **all in millisecs
 - addRemoveLinkedList 50
 - addRemoveArrayList  42
 - ListAccessArrayList 52
 - ListAccessLinkedList 30
- Size 100
  - addRemoveLinkedList 55
  - addRemoveArrayList 100
  - ListAccessArrayList 36
  - ListAccessLinkedList 63
- Size 1000
  - addRemoveLinkedList 62
  - addRemoveArrayList 275
  - ListAccessArrayList 29
  - ListAccessLinkedList 422
- Size 10000
  - addRemoveLinkedList 51
  - addRemoveArrayList 286
  - ListAccessArrayList 57
  - ListAccessLinkedList 740
-