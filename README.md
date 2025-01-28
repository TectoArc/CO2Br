## **CO2Br**

This python module is built on the non-iterative approach to compute the phase attributes of $\mathrm{CO_2}$--brine mixtures at geological carbon--storage and sequestration conditions. It can be integeated in large scale isothermal flow and transport simulations. Given a pressure field and temperature, it computes :
```
1. Solubility - $\mathrm{CO_2}$ solubility in brine or pure water
2. Density - density of $\mathrm{CO_2}$--brine/pure water mixture
3. Viscosity - viscosityof $\mathrm{CO_2}$--brine/pure water mixture
```
All the attributes can be used to enfore Dirichlet boundary conditions (in numerical simulations) and compute end-member ($\mathrm{CO_2}$ saturated vs unsaturated) quantities.

**Applicability Range**

Pressure and temperature range : 
```
P <= 1000 bar (100 MPa); T<=623.15 $^0$K (350 $^0$C)
```
Salinity components and molality ranges: ``` K2SO4 <= 1.5 mol/kg, MgSO4 <= 3.3 mol/kg, NaCl <= 6.0, KCl <= 6.0, MgCl2 <= 2.0, CaCl2 <= 5.0 ```
