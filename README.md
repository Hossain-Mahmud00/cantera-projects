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

## TCS distillation column design
- Vapor pressures and relative volatility of trichlorosilane (TCS) and silicon tetrachloride (STC)
- TCS-STC equilibrium curve (ideal mixture, Raoult's law)
- McCabe-Thiele design: Rmin = 1.41, R = 1.83, 22 theoretical stages, feed on stage 11
- Cross-check with Fenske-Gilliland shortcut method (22.6 stages)

## Heat exchanger sizing (TCS condenser)
- Heat duty from latent heat of trichlorosilane (183 kW for 1 kg/s)
- Chilled water flow and log-mean temperature difference (LMTD = 21.5 K)
- Overall U built from tube-side (Dittus-Boelter) and condensing-side (Nusselt) coefficients, with wall and fouling resistances
- Converged design: U = 797 W/m2K, area 10.7 m2, 30 tubes (2 passes), 0.23 bar water-side pressure drop
