# Nanocluster-KMC-Simulation
This is to be an ever improving version of 
a nanocluster Kinetic Monte Carlo simulation. 
Currently nckmcsim() takes in 4 variables: 

Nx : x dimension

Ny : y dimension

Na : number of deposited atoms

moves : number of moves per deposition.

This function returns a text file with 3 columns: com number, ipx and ipy.
The file is named with the following scheme: "*Nx*b*Ny*a*Na*m*moves*.txt"
For example if I input nckmcsim(50,50,500,500) the subsequent text file is named "50b50a500m500.txt"


 
