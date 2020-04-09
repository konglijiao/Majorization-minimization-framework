# Majorization-minimization-framework
This is a demo of Majorization-minimization algorithm exampling in one-dimension phase retrieval problem, which is also known as Gerchberg-Saxton algorithm.
## Notations
1. The main program is "main_MM_PhaseRetrieval_DFT.m".
2. *main_MM_PhaseRetrieval_DFT.m* only generates test data and results visualization, the algorithm used is all implemented in *Gerchberg_Saxton_Algorithm.m*.
3. How to call *Gerchberg_Saxton_Algorithm.m* as a sub-function: *x_r = Gerchberg_Saxton_Algorithm(A,y,t)*
    Parameter | Description |  Type  
    -|-|-
    A | Measurement matrix. | complex double |
    y   | Observation signal, a column vector. | double |
    t    | The maximum number of iterations. | int |
    x_r | Recovery result, a column vector. | complex double |
4. For more details about mathematical theory, see reference [1].

## Demonstration
![2](/figures/1.jpg)

## Reference
[1] Qiu, Tianyu, Prabhu Babu, and Daniel P. Palomar. PRIME: Phase retrieval via majorization-minimization. IEEE Transactions on Signal Processing. 64.19 (2016): 5174-5186.

[2] Sun, Ying, Prabhu Babu, and Daniel P. Palomar. Majorization-minimization algorithms in signal processing, communications, and machine learning. IEEE Transactions on Signal Processing. 65.3 (2016): 794-816.