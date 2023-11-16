This code extends the vibration analysis of a rotating tapered Timoshenko Beam using finite beam element method
 outlined in the paper "A.Bazoune and Y.A.Khulief,"A finite beam element for vibration analysis of rotating tapered timoshenko beams", J.Sound Vib.,vol.156,no.1,pp.141-164,1992,doi:10.1016/0022-460X(92)90817-H." to 3D beam element.
The method is outlined in
Di.Zhou,J.Fang,H.Wang,and X.Zhang,"Three-Dimensional Dynamics Analysis of Rotating Functionally Gradient Beams Based on Timoshenko Beam Theory",Int.J.Appl.Mech.,vol.11,no.4,2019,doi:10.1142/S1758825119500406.

The stiffnes matrices are unusually complex, So numerical method is resorted..This code generates matrices numerically and calculates \
the natural frequencies using eigen value method.
There is option to select either Euler or Timoshenko theory for the beam.
One can also choose to include or exclude the coriolois effect.
Sample results are also generated at the end

To run evaluate the notebook..
The coriolois.mx and 3dmodules.nb file should be in same folder to run the code succesfully
All modules have to be evaluated before evaluating the examples cell