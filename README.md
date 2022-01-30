# Quantumario
An interactive adventure through the world of QuantuMario, testing your knowledge of Quantum Key Distribution (QKD).

# Team
Jaime Park, Harun Gürhan, Shravika Pendyala, Sujan Khadka

# How to play the game
You play the game as Quantumario, who is trying to save Princess Peach from Bowser. On your way to Boswers castle, you face the Guardian Ducks who will ask you questions that you must answer to pass. To your aid you may have hints from the Princess, but only if you can create a secure channel to communicate with using QKD. But beware of interceptors...
Use the clues from Princess Peach and answer the Guardian Ducks' challenges to rescue Princess! 

# The Quantum in QuantuMario
The game consists of 3 levels in addition to /one final Quantum Challenge/ where Bowser ultimately defeats Bowser and rescues Princess Peach!
Throughout the game, the user is required to establish a secure Quantum Channel 3 times (once for each level) by choosing a string of 5 gates to measure Princess's qubits, and the Princess's key as well as Mario's final Keys are revealed. The user must then make the decision of whether or not to trust that Bowser has intercepted their channel. Whether or not Bowser intercepts their channel is random. If Bowser has intercepted, when solving the challenges, Mario will be given the incorrect clues which might confuse Mario when solving the challenges. Likewise if Bowser has not intercepted the channel, Princess will be providing clues to help solve the challenges. 

The use of QKD (BB84) to establish a secure channel between Mario and Princess Peach as well as making the decision of whether or not the channel is secure is representative of the real life application of QKD wherein the goal is to establish a secure channel and detect eavesdroppers. 

# Details about Implementation
The project has been implemented in qBraid with coding using the Qiskit. Simulations were carried out using the QuTech QX-34-L simulator while the final product uses the Spin-2 Quantum Processor. To use the program, copy the code in main.ipynb into qBraid and run it.

# Sources Used
The project uses BB84 protocol, with source code from QxQ lab material

# Our Presentation
https://docs.google.com/presentation/d/13o474he6ygFUT0840HEKZ0_ZZxhAhbZnZK0ymtiEEKI/edit?usp=sharing

# Our Experience with iQuHACK
It was an absolute pleasure to be competing in this challenge, we were definitely able to learn a lot about QC and how all the sytsems interact with each other to produce one defined result. Additionally, via the implementation of a QKD and the Game, we learned a lot about how to fix new types of errors and issues. We are extremely grateful for the entire iQuHACK team, mentors, and sponsors for organizing this project! Once again, thank you very much for providing this awesome experience!

# Date
29 january 2022 - 30 january 2022
