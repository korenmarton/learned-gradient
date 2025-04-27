# learned-gradient
first-release

Top boundary condition for Urban Boundary Layer (UBL) Largy Eddy Simulations

The DNN model is described in the following paper: ???
Koren, M., & Kristóf, G. (2025). Learned Upper Boundary Windshear Conditions For Large Eddy Simulation. 

The DNN models' inputs are non-dimensional variables in the following order:

input_names = ['x-velocity', 'y-velocity', 'z-velocity','dx-velocity-dx','dx-velocity-dy','dy-velocity-dx','dy-velocity-dy','dz-velocity-dx', 'dz-velocity-dy','pressure','dp-dx','dp-dy']

The DNN models' outputs are non-dimensional variables:

'dx-velocity-dz';
'dy-velocity-dz';
'dp-dz'
