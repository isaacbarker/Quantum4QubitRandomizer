### Quantum randomizer with 4 qubits.

#### The problem:

Use superposition to generate equal amplitudes for each output state which will then result in equal probabilities creating a theoretically random result.

### Circuit design:

In order to create a superposition in all 4 qubits each qubit needs to have a Hadamard gate to create a 50/50 probability of a $\ket1$ or $\ket0$ state in all qubits. Then each qubit can be measured onto 4 classical bits. 
