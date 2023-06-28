# Quantum_Adder
Implement the Classical Full Adder in qiskit, and then use each full adder to build an n-bit adder.

The aim of this project was initially to implement a full adder, with the goal to prove that any circuit that can be built on a classical device can likewise be replicated on a quantum device. 
However, my design for a full adder is not the most efficient, as it uses seven (7) qubits to implement the addition between three (3) bits. At this time, I am unable to minimize the circuit (any ideas are welcome).

After implementing the full adder, I thought why stop there... I could make the full adder circuit a gate and use it to make a general n-bit adder.

Afterward, I compared the runtime of my circuit to a simple function in Python. My circuit was much slower, but that was to be expected due to the large scaling of my circuit. 7 qubits for every bit.

All suggestions on improving/downscaling this circuit are welcome 🙂🙃.
