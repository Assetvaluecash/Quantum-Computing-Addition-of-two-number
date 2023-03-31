# Quantum-Computing-Addition-of-two-number
Here we try to add two numbers using quantum computing.


This code first takes two numerical inputs a and b and converts them to binary strings a_bin and b_bin, respectively. It then pads the binary strings with zeros so that they have the same length.

Next, the code initializes a quantum circuit with max_len+1 qubits and applies an X gate to the qubits where the corresponding bit of b is 1. It then applies CX gates to perform quantum addition.

The quantum circuit is then measured, executed using the qasm_simulator backend, and the results are printed. The results show the sum of a and b and the carry bit (if any) in binary form.

Note that this is just an example code, and there are many ways to implement quantum addition using different quantum programming languages or frameworks.


The code I provided uses the Qiskit library, which is a popular open-source quantum computing software development kit that allows you to simulate quantum circuits and run them on real quantum devices.

To run the code, you will need to have Qiskit installed on your computer. You can install it by running the following command in your terminal or command prompt:

pip install qiskit

Once Qiskit is installed, you can save the code to a file (e.g., quantum_addition.py) and run it in your terminal or command prompt using the following command:

python quantum_addition.py

This will execute the code and prompt you to enter the two numerical inputs a and b. After you enter the inputs, the code will perform quantum addition and print the results.

Note that the code I provided uses a quantum simulator to simulate the quantum circuit. If you have access to a real quantum device, you can modify the code to run the circuit on the device instead by specifying the appropriate backend in the execute function.







