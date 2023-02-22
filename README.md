# QOSF
In this code, we first create a quantum circuit with two registers, one for each integer, and apply Hadamard gates to the first register to create a superposition of all possible states. 
We then apply a phase oracle to mark the state that represents the larger integer. 
The phase oracle applies a conditional phase shift to the state that represents the larger integer, which causes the amplitude of that state to be inverted. 
Next, we apply the diffusion operator to amplify the amplitude of the marked state. 
The diffusion operator consists of two steps: 
    first, we apply a reflection about the average state (which is achieved using the Hadamard gates and the multi-controlled Toffoli gate); 
    and second, we apply a phase inversion about the initial state (which is achieved using the conditional phase shift gate). 
Finally, we measure the first register to obtain
