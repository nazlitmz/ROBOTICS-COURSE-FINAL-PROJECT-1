🤖 From-Scratch Linear Algebra for Robotics Simulation

A hands-on robotics project combining manual linear algebra implementation with real-time physics simulation.

✨ Project Summary

This project demonstrates how core linear algebra concepts can be implemented entirely from scratch and applied directly to robotics simulations.
Instead of relying on high-level numerical libraries such as NumPy, all matrix operations are manually designed to provide a deeper understanding of the mathematics behind robotic motion and transformations.

The project integrates these custom-built mathematical foundations with PyBullet, enabling realistic robot simulations and motion control.

🎯 Objectives

Build a custom Matrix class without using NumPy

Implement essential matrix operations manually

Apply linear algebra to robot kinematics and transformations

Simulate and control robotic motion using PyBullet

Strengthen conceptual understanding of robotics fundamentals

🧠 What This Project Covers

Matrix creation and manipulation

Matrix multiplication, transpose, and inversion

Homogeneous transformation matrices

Coordinate frame transformations

Robot joint control and motion updates

Physics-based simulation and visualization

All computations are performed explicitly to expose the mathematical logic behind every step.

🧩 Task Structure

The project is organized into two main parts: Task A and Task B, each progressively increasing in complexity.

🔹 Task A – Foundations & Incremental Development

A1:
Manual implementation of basic matrix operations and visualization

A2:
Integration of matrix operations with PyBullet simulations

A3:
Advanced matrix handling and real-time robotic simulation

A4:
Extended robot motion control and refined transformations

🔹 Task B – Applied Robotics

B1:
Initial robotics task implementation using custom matrix logic

B2:
Final, corrected, and optimized version of the robotics task
(Represents the completed and stable solution)

🛠️ Technologies Used

Python

PyBullet – physics and robotics simulation

Matplotlib – visualization

Standard Python libraries (math, time, copy)

🚫 NumPy is intentionally not used to preserve full manual control over all computations.

▶️ Running the Project

Install required libraries:

pip install pybullet matplotlib


Open the notebook:

jupyter notebook 202508331_nazlitemiz_Project_2_sourcecode.ipynb


Run the cells sequentially
(PyBullet simulations depend on execution order)

📈 Learning Outcomes

Strong intuition for matrix mathematics

Practical understanding of robotics kinematics

Insight into how numerical libraries operate internally

Experience bridging theory with real-world simulation

This project serves as a solid foundation for further studies in robotics, AI, and autonomous systems.

👩‍💻 Author

Nazlı Temiz
Student ID: 202508331
Fall 2025 – Course Project

📝 Notes

Designed for clarity and learning, not library-level optimization

Restarting the kernel may be required when re-running simulations

Code structure prioritizes readability and conceptual transparency
