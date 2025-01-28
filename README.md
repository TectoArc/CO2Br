## **CO2Br**

This python module is built on the non-iterative approach to compute the phase attributes of $\mathrm{CO_2}$--brine mixtures at geological carbon--storage and sequestration conditions. It can be integeated in large scale isothermal flow and transport simulations. Given a pressure field and temperature, it computes :
```
1. Solubility - carbon-dioxide solubility in brine or pure water
2. Density - density of carbon-dioxide--brine/pure water mixture
3. Viscosity - viscosityof carbon-dioxide--brine/pure water mixture
```
All the attributes can be used to enfore Dirichlet boundary conditions (in numerical simulations) and compute end-member ($\mathrm{CO_2}$ saturated vs unsaturated) quantities.

**applicability range**

pressure and temperature range : 
```
P <= 1000 bar (100 MPa); T<=623.15 degree K (350 degree C)
```
salinity components and molality ranges: 
```
K2SO4 <= 1.5 mol/kg
MgSO4 <= 3.3 mol/kg
NaCl <= 6.0 mol/kg
KCl <= 6.0 mol/kg
MgCl2 <= 2.0 mol/kg
CaCl2 <= 5.0 mol/kg
```
**dependencies**
```
- python 2.0 or higher
- numpy
```

**installation**

**documentation**

**references**
* John
