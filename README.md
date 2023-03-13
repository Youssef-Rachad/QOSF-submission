# QOSF-submission
Youssef Rachad - QOSF 2023 submission 

I chose to do task 4 - Random Circuit. 

## Requirements:
- The code is tested on python 3.9+ (though it should work without too many break in 2.7+)
- Qiskit 0.21.0
- Numpy 1.23.4

## Functionality

The basic code works by:
- Iterating over the number of layers
- Choosing a random gate and an appropriate number of qubits
- Appending to the circuit
- Repeat for all qubits in a given layer, then for all layers
- Return a circuit ready to be used and drawn

## Going the extra mile
I followed the task guidelines, then wrote a more advanced version where I included:
- Manual seeding \[int] (for reproducible results and testing facility)
- Measurement flag \[boolean] to control if the circuit gets measured or not
- 3 Qubit gates and parametered gates, this allows for richer diversity in the possible circuits.
  Their implementation was a bit tricker and got me to think about generalising the way I generate circuits
  
Overall, this task was a lot of fun to implement and always a pleasure to complete.
I made heavy use of Qiskit and Numpy documentation - these were easy for me to read and utilise.

I look forward to working further in quantum computing, contributing to research and growing as an engineer in this field!

Cheers
