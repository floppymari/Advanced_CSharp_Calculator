# Multi-Purpose Utility Suite & Advanced Calculator 🇮🇹

A comprehensive Windows Forms desktop application developed in C# that integrates advanced mathematical logic, geometric calculations, and system utility modules. This project demonstrates modular software design and a dynamic user interface.

### 🌟 Key Features

‼️ **Dynamic UI Architecture:** Features an interface that switches in real-time between **Base**, **Scientific**, and **Geometric** modes by managing control visibility and group box states.
‼️ **Scientific Computing:** Includes trigonometric functions (Sin, Cos, Tan), square roots, and powers using the `Math` library.
‼️ **Recursive Algorithms:** Implements a custom recursive function to calculate factorials.
‼️ **Geometry Engine:** A dedicated module for calculating **Area and Perimeter** of multiple shapes (Rectangle, Square, Rhombus, Circle, Parallelogram) with intelligent input fields that adapt to the selected figure.
‼️ **Modular Integration:** Acts as a central hub to launch external specialized modules for **File Management**, **String Manipulation**, and **Date Handling**.

### 🛠 Technical Deep Dive

🫆 **Event-Driven Programming:** Managed complex user interactions through synchronized event handlers for buttons, checkboxes, and radio buttons.
🫆 **Error Handling & Validation:** Built-in safeguards to prevent common application crashes, such as:
    🧠 **Division by Zero:** Includes custom alerts and state resets.
    🧠 **Selection Logic:** A validation method (`VerificaChecked`) ensures only one scientific operation is active at a time to prevent logic conflicts.
    🧠 **Input Management:** Strategic use of `.Focus()` and `.Clear()` to streamline the user workflow.
🫆 **OOP Principles:** Utilizes separate classes and forms to maintain a clean and scalable code structure.

### 📂 How to Use
1. Clone the repository.
2. Open the solution file `primo form.sln` in **Visual Studio**.
3. Ensure you have the **.NET Framework** installed.
4. Press `F5` to build and run the application.


*Developed as part of my 5-year Technical Specialization in Informatics & Telecommunications.*
