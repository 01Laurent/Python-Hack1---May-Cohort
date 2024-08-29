    *SOLUTIONS TO THE ALGORITHMS
    * Reversing a string using a stack
- A stack is a data structure that follows the Last in, First OUT(LIFO) principle, meaning that the last item you put in the stack is the first one you get out. i.e when you place a chair on top of a stack, and you want a chair you take the top one first.
  *Steps to reverse a string using a stack.
  1. You initialize the stack, like creating an empty stack.
  2. Then one can push the characters on to the stack, as each character is added it goes to the top.
  3. Pop characters from the stack- the characters will be removed one by one(pop), this will give the characters in reverse order.
  4. Building the reversed string - as we pop each character from the stack, we append it to a new string, This new string will be the reversed version of the original string.











































# Data Structures and Algorithms Practice

This repository contains your solutions to three simple data structures and algorithms problems. Please follow the instructions below to complete the tasks and submit your work.

## Questions

### 1. Reverse a String Using a Stack
- **Task:** Implement a stack data structure to reverse a string.
- **Function:** `reverse_string(s: str) -> str`
- **Example:**
  - Input: `"hello"`
  - Output: `"olleh"`

### 2. Implement a Queue Using Two Stacks
- **Task:** Implement a queue using two stacks.
- **Class:** `QueueWithStacks`
- **Methods:**
  - `enqueue(x: int)`: Adds an element to the queue.
  - `dequeue() -> int`: Removes and returns the front element of the queue.
- **Example:**
  ```python
  q = QueueWithStacks()
  q.enqueue(1)
  q.enqueue(2)
  print(q.dequeue())  # Output: 1
  print(q.dequeue())  # Output: 2


### 3. Find the Maximum Element in a List Using a Linked List
- **Task:** Implement a singly linked list and find the maximum element in the list.
- **Class:** LinkedList
- **Method:** find_max() -> int
- **Example**
  ```python
  ll = LinkedList()
  ll.append(3)
  ll.append(1)
  ll.append(4)
  ll.append(2)
  print(ll.find_max())  # Output: 4


### Submission Instructions
- Fork this repository.
- Clone the forked repository to your local machine.
- Create a separate branch for your solutions.
- Implement the solutions to the above questions in Python.
- Commit your changes with clear and descriptive messages.
- Push your changes to your forked repository.
- Create a pull request (PR) to the original repository with your solutions.
- Submit the URL of your GitHub repository as your final submission.

### Submission form 
https://forms.gle/VUTFyWTXKUPq4CMQA
