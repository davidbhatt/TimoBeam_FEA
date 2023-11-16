# TimoBeam_FEA
This repo consists of Wolfram language code to carry out frequency analysis of a rotating Beam using Euler and Timoshenko Theory in either 2D
This code includes the modules for vibration analysis of a rotating tapered Timoshenko Beam using finite beam element method
The method is outlined in the paper
A.Bazoune and Y.A.Khulief,"A finite beam element for vibration analysis of rotating tapered timoshenko beams",J.Sound Vib.,vol.156,no.1,pp.141-164,1992,doi:10.1016/0022-460X(92)90817-H.

The code implements the finite element analysis in modules to generate the stiffness matrices
Then generates analytical expressions for the stiffness matrices
This also include a function to calculate the natural frequencies of beam for both Euler and Timoshenko theory using eigenvalue analysis

All cells containing the modules have to be evaluated before evaluating the example cells