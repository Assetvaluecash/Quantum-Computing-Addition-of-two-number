# Quantum-Computing-Addition-of-two-number
Here we try to add two numbers using quantum computing.


This code first takes two numerical inputs a and b and converts them to binary strings a_bin and b_bin, respectively. It then pads the binary strings with zeros so that they have the same length.

Next, the code initializes a quantum circuit with max_len+1 qubits and applies an X gate to the qubits where the corresponding bit of b is 1. It then applies CX gates to perform quantum addition.

The quantum circuit is then measured, executed using the qasm_simulator backend, and the results are printed. The results show the sum of a and b and the carry bit (if any) in binary form.

Note that this is just an example code, and there are many ways to implement quantum addition using different quantum programming languages or frameworks.
