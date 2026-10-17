# COIN-TOSS
Quantum coin toss using Qiskit.


Quantum Coin Toss: A Random Bit Generator

1. Project Overview

This project demonstrates a quantum coin toss using Qiskit. It generates binary measurement outcomes, where 0 represents Tails and 1 represents Heads.

2. Problem and Motivation

A coin toss is a simple way to make a random choice. This project explores how quantum computing concepts can be used to simulate a coin toss and generate random binary outcomes.

I chose this idea because it is beginner-friendly and demonstrates an important quantum computing concept: superposition followed by measurement.

3. Quantum Circuit

The circuit uses one qubit and one classical bit.

- The qubit starts in the state |0⟩.
- A Hadamard gate creates an equal superposition of |0⟩ and |1⟩.
- Measurement records the outcome as a classical bit.
- The circuit is executed 1,000 times to collect measurement counts.

4. Technologies Used

- Python
- Qiskit
- Qiskit Aer local simulator
- Matplotlib

5. Installation

Install Python and run:

pip install qiskit qiskit-aer matplotlib pylatexenc

6. How to Run

1. Download or clone this repository.
2. Install the required libraries.
3. Run the program:

python quantum_coin_toss.py

4. View the printed measurement counts and graph.
5. The program saves the circuit diagram as "circuit_diagram.png" and the graph as "measurement_counts.png".

7. Results and Interpretation

The circuit produces measurement outcomes of 0 and 1. Ideally, each outcome has a probability of 50%.

After 1,000 shots, the counts should be approximately equal, although they may differ due to random sampling. The graph visualizes the observed counts.

Execution environment: Qiskit Aer local simulator. No physical quantum hardware was used.

8. Limitation

The experiment uses an ideal local simulator rather than a physical quantum processor. It does not fully represent the noise and imperfections that can affect real quantum hardware.

9. Future Improvements

- Run the circuit on real quantum hardware.
- Compare simulator results with hardware measurements.
- Repeat the experiment with different numbers of shots.
- Add a simple interactive coin-toss interface.

10. Acknowledgement

This project uses the open-source Qiskit and Qiskit Aer libraries. The implementation and explanation should be credited according to the actual contributions of the team members.
