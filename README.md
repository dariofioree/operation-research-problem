# Optimal Bookshelf Design Using Integer Programming and Gurobi
This project presents an optimization model for designing a bookshelf that minimizes construction costs while accommodating a set of books with predefined dimensions. The study formulates the problem as an integer programming model and implements it using Python and Gurobi.

The key aspects of this project include:

- Mathematical Model: A formalized integer programming approach to optimize shelf height while ensuring book placement constraints.
  
- Constraints and Objective Function: Ensuring all books fit within a fixed shelf width while minimizing the total bookshelf height.
  
- Implementation in Python and Gurobi: The model is coded in Python, leveraging Gurobi for optimization.
  
- Handling Multiple Copies: A modified version of the model accounts for cases where each book ID appears as many times as its ID value.
  
- Computational Efficiency: Comparisons between naive and optimized models, demonstrating an 80% reduction in variables and constraints.
  
- Upper and Lower Bound Estimation: The project explores heuristic approaches and relaxation techniques to estimate solution bounds efficiently.
  
This repository contains the full Python implementation, problem formulation, and analysis of results. 
