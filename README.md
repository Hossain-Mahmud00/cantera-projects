# Cantera Projects

Chemical engineering simulations with Cantera and Python.

## Methane combustion
- Adiabatic flame temperature vs equivalence ratio (equilibrium)
- Ignition simulation in a constant-pressure reactor
- Species evolution during ignition (CH4, CO, CO2, OH)
- Ignition delay vs temperature and pressure
- Arrhenius analysis of effective activation energy

Tools: Python, Cantera (GRI-Mech 3.0), NumPy, Matplotlib

## Plug flow reactor
- Ignition distance along a tube at constant pressure
- Effect of mass flow rate on ignition distance

## Thermodynamic properties
- Fluid properties and phase behavior with the Thermo library
- Vapor pressure curves for water and ethanol
- Real-gas behavior of methane with the Peng-Robinson equation of state (compressibility factor Z)

## Vapor-liquid equilibrium
- Ethanol-water boiling diagram using Raoult's law (ideal mixture)
- Non-ideal behavior with Van Laar activity coefficients
- Azeotrope calculation (x = 0.91, T = 351.45 K) compared with published data (about 0.89, 351.3 K)
