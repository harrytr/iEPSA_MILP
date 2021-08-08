# iEPSA_MILP

This is the Mixed-Integer Linear Programming implementation of the root LP iEPSA algorithm. It implements a simple branch and bound procedure to find the integer optimal solution (if it exists).

The algorithm is called in MATLAB as follows:

[f,x,Niter] = iepsa_bnb('filename',1);

The inputs are the name of the .mat file MILP problem (without the extension) and the number of nodes at which an update of status will be printed in the command window.
