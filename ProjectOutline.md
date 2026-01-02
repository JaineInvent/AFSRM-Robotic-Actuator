The main constraints of the project are the electrical limitations associated with PCB Stators.

Early-Stage Design:

1. Electrical
    - Use the KiCad coil-pluin  and coil optimization notebook to produce wedge coil, or a shape that maximizes copper area on the PCB. 
    - Use Biot-Savart python simulation to find the B-field in the x and z directions

    Calculate Max Torque, Power, and RPM using a python script: 
    - Use Pandas to import coil geometry as a CSV and other inputs associated with the SRM Torque-inductance formula to calculate maximum torque, rpm, and power
    - Create a function to process the CSV to calculate Area
    - Calculate Inductance using Area function
    - Set current to PCB limit of 2A and supply voltage to 5V
    - Simplify SRM Torque formula to calculate max torque
    - Use il x B to calculate Magnetic force(F_m)
    - Calculate rpm by using F_m and dynamics 

2. Mechanical 
    - Use python to apply scaling laws to a typical in-hub E-bike motor 
    - Solve any defecencies due to Electrical constraints using Axial-Flux friendly solutions(ie planetary gears)
    - Model the AFSRM casing and components using SolidWorks 
    - Learn to use Ansys to model and regulate thermal output of the motor
    - Consider space for sensors and control electronics within the casing
    - Consider debris limitations

3. Controls
    - Create a plectica to display the connection between motor driver, hall sensor, and AFSRM
    - Create a mock BMS(Battery Management System)

Note: Since this is an early-stage design outline, Eddy currents, Magnetic Saturation, and Torque Ripple are not yet factored into the design. 
Once a prelimanry design is built and tested, the above will be used to improve the AFSRM. 
