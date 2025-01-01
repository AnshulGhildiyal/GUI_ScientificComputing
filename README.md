# Scientific Calculator GUI

Welcome to the **Scientific Calculator GUI** project! This application provides a comprehensive platform for performing a wide variety of mathematical computations, ranging from basic arithmetic to solving transcendental equations, numerical integration, and more. The GUI is built with Python's PyQt5 framework and includes advanced mathematical functionalities to assist users in diverse scientific computing tasks.

---

## Key Features

1. **Quadratic Equation Solver**:
   - Computes the roots of a quadratic equation.
   - Handles real and complex roots.

2. **Cubic Equation Solver**:
   - Solves cubic equations with real and complex roots.
   - Provides detailed step-by-step results.

3. **Basic Calculator**:
   - Performs standard arithmetic operations.
   - Includes a user-friendly dark-themed interface.

4. **ODE Solver (Euler Method)**:
   - Solves ordinary differential equations using the Euler method.
   - Accepts user-defined functions and parameters.

5. **Transcendental Equation Solver**:
   - Solves transcendental equations using Newton's method.
   - Provides iterative solutions with convergence details.

6. **Newton Interpolation Calculator**:
   - Performs polynomial interpolation using Newton's method.
   - Allows input of custom data points.

7. **Numerical Integration**:
   - Computes definite integrals using:
     - Trapezoidal Rule
     - Simpson's 1/3 Rule
     - Simpson's 3/8 Rule
   - Dynamically chooses the most appropriate method based on input.

---

## Technologies Used

- **Programming Language**: Python
- **GUI Framework**: PyQt5
- **Mathematical Libraries**:
  - NumPy
  - SciPy
  - SymPy
- **Visualization**: Matplotlib
- **Styling**: QDarkStyle for consistent dark-themed UI

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/scientific-calculator-gui.git
   cd scientific-calculator-gui
   ```
2. **Set Up Environment**: Install the required dependencies using pip
   ```bash
   pip install -r requirements.txt
   ```
3. *Run the Application**:
   ```bash
   python Scientific_Calculator.py

## Usage

   - Launch the application and select the desired tool from the main menu.
   - Enter the required inputs in the provided fields.
   - Click the corresponding action button (e.g., `Solve`, `Calculate`, etc.).
   - View results displayed in the application interface.


## Future Scope

1. **Integration with Advanced Solvers**:
   - Incorporate support for solving partial differential equations (PDEs) and higher-order ODEs.

2. **Graphical Enhancements**:
   - Add dynamic graph plotting features for visualizing equations and solutions.

3. **Mobile Compatibility**:
   - Develop a mobile-friendly version of the application using frameworks like Kivy/PyQt5.

4. **Cloud-Based Computations**:
   - Enable support for cloud-based computations for handling complex and large datasets.

5. **Additional Methods**:
   - Extend the numerical integration and interpolation modules to include methods like Monte Carlo integration and Lagrange interpolation.

6. **User Customizations**:
   - Allow users to save their preferred configurations and customize themes or layouts.

7. **Real-Time Collaboration**:
   - Introduce real-time collaborative features for shared problem-solving.
  
## Contributing

Contributions are welcome! If you have suggestions for improving the application or adding new features, please:

1. Fork the repository
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
3. Commit your changes and open a pull request.

---------------------------------------------------------------

Thank you for using the Scientific Calculator GUI!
