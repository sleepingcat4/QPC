<h1>Quantum Password Cracker</h1>
<h2>Introduction</h2>
<p>Shor's algorithm is a quantum algorithm for factoring integers that was developed by mathematician Peter Shor in 1994. It is the most efficient classical algorithm known for this problem, but it is also a prime example of the power of quantum computing.</p>
<h2>Implementation</h2>
<p>This implementation of Shor's algorithm is written in Python, using the Qiskit library for quantum computing and the Tkinter library for the user interface. It allows the user to enter a number and factorize it using a quantum circuit.</p>
<h2>Usage</h2>
<p>To use the program, first make sure you have Qiskit and Tkinter installed. Then, run the file <code>shor.py</code> in your Python environment. A user interface will appear, where you can enter a number and press the "Factorize" button to run the algorithm. The factors of the number will be displayed in the output label.</p>
<h2>Note</h2>
<p>This is a simplified version of Shor's algorithm and there are many different variations of the algorithm that can be implemented using Qiskit. Additionally, the above code is only an implementation of the first part of the Shor's Algorithm, the Quantum Fourier Transform, which is used to find the period of a function. The second part, the Classical part, is not included here and it is responsible for finding the factors of the number using the period found in the QFT.</p>



