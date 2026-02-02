# Multi-Purpose Utility Suite & Advanced Calculator 🇮🇹<br>

A comprehensive Windows Forms desktop application developed in C# that integrates advanced mathematical logic, geometric calculations, and system utility modules. This project demonstrates modular software design and a dynamic user interface.

### 🌟 Key Features <br>

‼️ **Dynamic UI Architecture:** Features an interface that switches in real-time between **Base**, **Scientific**, and **Geometric** modes by managing control visibility and group box states.<br>
‼️ **Scientific Computing:** Includes trigonometric functions (Sin, Cos, Tan), square roots, and powers using the `Math` library.<br>
‼️ **Recursive Algorithms:** Implements a custom recursive function to calculate factorials.<br>
‼️ **Geometry Engine:** A dedicated module for calculating **Area and Perimeter** of multiple shapes (Rectangle, Square, Rhombus, Circle, Parallelogram) with intelligent input fields that adapt to the selected figure.<br>
‼️ **Modular Integration:** Acts as a central hub to launch external specialized modules for **File Management**, **String Manipulation**, and **Date Handling**.<br>

### 🛠 Technical Deep Dive<br>

🫆 **Event-Driven Programming:** Managed complex user interactions through synchronized event handlers for buttons, checkboxes, and radio buttons.<br>
🫆 **Error Handling & Validation:** Built-in safeguards to prevent common application crashes, such as:<br>
    🧠 **Division by Zero:** Includes custom alerts and state resets.<br>
    🧠 **Selection Logic:** A validation method (`VerificaChecked`) ensures only one scientific operation is active at a time to prevent logic conflicts.<br>
    🧠 **Input Management:** Strategic use of `.Focus()` and `.Clear()` to streamline the user workflow.<br>
🫆 **OOP Principles:** Utilizes separate classes and forms to maintain a clean and scalable code structure.<br>

### 📂 How to Use<br>
1. Clone the repository.<br>
2. Open the solution file `primo form.sln` in **Visual Studio**.<br>
3. Ensure you have the **.NET Framework** installed.<br>
4. Press `F5` to build and run the application.<br>


*Developed as part of my 5-year Technical Specialization in Informatics & Telecommunications.*
