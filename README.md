# Coulomb_Counting_Battery_SOC
Simulink Project for Measuring Battery SOC Using Coulomb Counting Method

# Coulomb Counting Battery SOC Measurement

## Project Description
This Simulink project demonstrates the coulomb counting method for measuring the State of Charge (SOC) of a battery pack configured with 6 cells arranged in a 2x3 configuration (2 parallel and 3 series). The model includes:
- A controlled current source to provide current to the battery.
- Integration block to calculate the SOC using the formula: `SOC = 1 - Integral(I) / Capacity of Battery`.
- Monitoring of SOC using a scope.

## Features
- Configures a battery pack using series and parallel cell connections.
- Measures SOC using the coulomb counting method.
- Monitors SOC in real-time.

## Files Included
- `Coulomb_Counting_Battery_SOC.slx`: The Simulink model file.
- `README.md`: Project description and details.
- Optional: Additional documentation in the `docs` folder.

## How to Use
1. Clone this repository to your local machine.
2. Open `Coulomb_Counting_Battery_SOC.slx` in MATLAB Simulink.
3. Run the simulation and observe the SOC output on the scope.

## Author
- Jayesh Verma
- [LinkedIn](https://www.linkedin.com/in/jayeshv45/)
