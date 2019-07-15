# Streamwise Periodicity testcases

## `half_cylinder_2D`  
half cylinder massflow prescribed heated cylinder

## `pipe_slice_3D` 
analytical solution of the velocity magnitude for steady laminar pipe flow in a round pipe `v_mag (r) = -1/(4*mu) * (Delta p / Delta x) * (R**2 - r**2)` therefore a pressure drop Delta p is prescribed, heated walls

`Re = rho * v * L / mu = 1.0 * ? * 5e-3 / 1.8e-5` bei v -> averaged (mass or area weighted?) velocity the critical Re ~= 2300 (v = 0.6 for now) makes Re=167