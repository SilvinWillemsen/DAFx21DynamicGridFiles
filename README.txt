This repository accompanies the following publication: "S. Willemsen, S. Bilbao, M. Ducceschi and S. Serafin, "Dynamic Grids for Finite-Difference Schemes in Musical Instrument Simulations", Proceedings of the 23rd Int. Conf. on Digital Audio Effects (DAFx), 2021.

The dynamicGrid.m file is a MATLAB implementation of the Dynamic Grid.

The Sound Files folder contains audio of the system initialised with a raised cosine (rather than the excitation used in the paper u_1 = 1) for more pleasant audio. The grid configurations are altered over the course of the simulation.

Two files show a smooth transition between grid configurations over the course of two seconds:
- N50to600in2Sec: Goes from N = 50 to N = 600 in 2 seconds (frequency decrease)
- N600to50in2Sec: Goes from N = 600 to N = 50 in 2 seconds (frequency increase)

The four other files showcase the method using pentatonic melodies with slow and fast transitions between the notes. Two of the files start by decreasing in frequency and increase thereafter, the two others do the inverse. This is to show that in both cases, the notes played at the start are not (much) influenced by the process of adding and removing grid points. 