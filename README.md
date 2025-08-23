# Web-Based Verilog Linter & Visualizer

This is an intelligent tool built for hardware engineers and students to improve RTL code quality. The application lints Verilog code for common errors and dynamically generates a visual block diagram of the module's structure.

## Key Features

- **Smart Linting:** Automatically checks Verilog code for common mistakes, such as incorrect use of blocking/non-blocking assignments and missing semicolons.
- **Module Visualization:** Parses the RTL code to generate a clean, easy-to-read block diagram of the module's inputs and outputs.
- **Professional UI:** Features a modern, dark-themed interface with a circuit board background and glassmorphism effects.

## Technologies Used

- **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript
- **Core Logic:** Python (running in the browser via Pyodide)
- **Diagrams:** Mermaid.js