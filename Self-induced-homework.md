

X. Quantum Algorithms for the Development of Safe Superintelligence.

1. What are eigenstates?
1. What are eigenvalues?


1. [ ] Re-iterate on the Grovers's algorithm.
1. [ ] What is Quantum Entanglement again?
1. [ ] Re-iterarte Shor's algorithm.

1. [ ] Implement Grovers's algorithm in qiskit
1. [ ] Implement Shor's algorithm in qiskit

1. [ ] H/w implement a simple RSA algorithm in Rust?
1. [ ] H/w try implementing NTRU algorithm that is faster than RSA and resistant to quantum computing in Rust?

i

Being ADHD is like having quantium computer for brain, where all your thoughts and tasks are computed in constant superposition and entanglement. Medication collapses it to determenistic computer.

Is being ADHD 
Being ADHD is like 
Being ADHD is like having a quantum computer for brain where you think about all things in parallel and once measured you get explicit results. Like do I want ot surf in Sri Lanka/ what next things do I need to sell my house/ implemeting Grover's search algorithm. Medication turns the quantum brain off and allows to operatie in the determenistic space.


---

[ ] Polinomials refreshment
[ ] Fourier Transforms?



[ ] Try the error correction algorithgm from Practi



---

## Basic Error Correction

```
version 1.0
qubits 5

.Encoding
cnot q[0], q[1]
cnot q[0], q[2]

.Introduce_Error
x q[1]

.Error_Detection
cnot q[0], q[3]
cnot q[1], q[3]
cnot q[0], q[4]
cnot q[2], q[4]
measure q[3,4]

.Error_Correction
# Both b[3] = b[4] = 0
# do nothing

# b[3]=b[4]=1
c-x b[3,4], q[0]

# b[3]=1,b[4]=0
not b[4]
```






```

## Swap Circuit

```
version 1.0

# qubit definitions
.init
    # initialise inputs A=1, B=0 and carry_in=1
    {x q[0] | x q[1]}

    cnot q[0], q[1]
    cnot q[1], q[0]
    cnot q[0], q[1]

```



```


[ ] Implement Grover's Algorithm in QASM (for 3 and 4 qubits)

[ ] Implement Deutsch-Josza myself in Quantum Inspire



