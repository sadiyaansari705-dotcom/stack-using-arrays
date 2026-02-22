Stack Implementation in C (Using Array)

This project demonstrates how to implement a Stack Data Structure in C using an array.

The program includes the following stack operations:

✅ Initialize Stack

✅ Push

✅ Pop

✅ Peek

✅ Check if Stack is Full

✅ Check if Stack is Empty

🧾 Program Description

The stack is implemented using:

A fixed-size array (MAX = 5)

A top variable to track the topmost element

The stack follows the LIFO (Last In, First Out) principle.

🧠 Concepts Used

Structures in C

Arrays

Stack Data Structure

LIFO Principle

Functions

Conditional Statements

Basic Error Handling

📚 Stack Operations Explained
🔹 Initialize

Sets top = -1 to indicate the stack is empty.

🔹 Push

Checks if the stack is full.

Increments top.

Inserts the new element.

🔹 Pop

Checks if the stack is empty.

Returns and removes the top element.

Decrements top.

🔹 Peek

Returns the top element without removing it.

📤 Sample Output
10 pushed to stack
20 pushed to stack
30 pushed to stack
Top element is 30
30 popped from stack
20 popped from stack
Top element is 10
🚀 How to Run
🔹 Compile the Program
gcc main.c -o output
🔹 Run the Program
./output

(For Windows)

output.exe
📂 Project Structure
📁 stack-using-array
 ├── main.c
 └── README.md
⚠️ Limitations

Stack size is fixed (MAX = 5).

No dynamic resizing.

Returns -1 when stack is empty (can be improved).

🔧 Possible Improvements

Make stack size dynamic.

Implement menu-driven version.

Add better error handling.

Implement stack using linked list.

👨‍💻 Author

sadiya ansari 
B.Tech Student

If you want, I can also give:

⭐ Short lab submission version

⭐ Stack using linked list version

⭐ Menu-driven stack implementation
