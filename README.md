Introduction
This repository contains a Python script that defines a simple quantum circuit using the Qiskit library. 
The quantum circuit consists of five quantum bits (qubits) and five classical bits to store measurement results. 
The circuit applies Hadamard gates to all qubits and performs measurements.

Execution
The script then defines a function answer(result) that takes the measurement results as input and prints a humorous message based on the binary state obtained. 
The messages include playful scenarios related to the outcome of the quantum computation.

After defining the circuit and the function, the script executes the quantum circuit on an IBM Quantum computer named 'ibmq_quito'. 
The measurement results are then passed to the answer function to display the corresponding message.

Output
The output includes a visual representation of the quantum circuit, the measurement results, and a histogram plot showing the distribution of states.

Additional Information
The script uses the Qiskit library for quantum computing and assumes access to an IBM Quantum Experience account for executing the circuit on real quantum hardware.

Feel free to explore and modify the script to experiment with different quantum circuits and understand the outcomes of quantum computations.
