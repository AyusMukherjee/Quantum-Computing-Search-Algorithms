# Quantum-Computing-Search-Algorithms
Implemented the Grover and Deutsch-Jozsa search algorithms, as a matter of complexity


Grover's Algorithm:

Purpose: Grover's algorithm is primarily designed for searching an unsorted database of N items to find a marked item. It provides a quadratic speedup over classical algorithms.
Complexity:
Classical: O(N) in the worst case (linear search).
Quantum: O(√N) in the worst case.


Deutsch-Jozsa Algorithm:

Purpose: The Deutsch-Jozsa algorithm is used to solve a specific type of oracle function problem, where you determine whether a given Boolean function is constant (maps all inputs to the same output) or balanced (maps exactly half the inputs to one output and half to the opposite output).
Complexity:
Classical: O(2^n) in the worst case (exponential search).
Quantum: O(1) queries in the worst case.
