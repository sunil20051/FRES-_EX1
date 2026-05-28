## MODELLING AND SIMULATION OF 1kW SOLAR PHOTOVOLTAIC ARRAY.

## AIM:

To model and design a 1kW solar photovoltaic system using MATLAB Simulation and obtain the current, voltage, power values and solar PV characteristics curves. 

## APPARATUS REQUIRED:
 MATLAB 2021 or above 
 
## Theory:
The theory of solar cells explains the process by which light energy in photons is converted into electric current when the photons strike a suitable semiconductor device. The theoretical studies are of practical use because they predict the fundamental limits of a solar cell, and give guidance on the phenomena that contribute to losses and solar cell efficiency. Photons in sunlight hit the solar panel and are absorbed by semi-conducting materials. Electrons (negatively charged) are knocked loose from their atoms as they are excited. Due to their special structure and the materials in solar cells, the electrons are only allowed to move in a single direction. The electronic structure of the materials is very important for the process to work, and often silicon incorporating small amounts of boron or phosphorus is used in different layers. An array of solar cells converts solar energy into a usable amount of direct current (DC) electricity. The photon can pass straight through the silicon — this (generally) happens for lower energy photons. The photon can reflect off the surface. The photon can be absorbed by the silicon if the photon energy is higher than the silicon band gap value. This generates an electron-hole pair and sometimes heat depending on the band structure. 

<img width="481" height="305" alt="image" src="https://github.com/user-attachments/assets/7e841c5a-c9b2-46e5-a49c-8ef9d309a420" />


## CIRCUIT DIAGRAM:

<img width="726" height="541" alt="Screenshot 2026-05-27 155801" src="https://github.com/user-attachments/assets/58cf5348-870c-4051-87da-1dfeeb53b233" />


## Procedure:
1. Open MATLAB
2.  From Simulink library browser, pick the following components a. solar cell b. constant c. PS converter, S converter d. Current sensor, voltage sensor e. Variable resistor f. Ramp g. Scope, XY graph
4.  Connect the thirty-six solar cells in series with common irradiation and make it as a subsystem to form a panel.
5.  Form similar six panel and connect them in series to form an array with single irradiance input.
6.  Create a subsystem for the six panels.
7.  Connect the constant block with a value of 687 to the irradiance input through PS converter.
8.  From the output of the solar array connect a current sensor in series to the positive terminal and voltage sensor across the terminals.
9.  Connect a variable resistor across the solar pv array terminal.
10.  Connect a ramp signal to the variable resistor through the PS connector.
11. Using Simulink converter, connect the terminals of the current sensor and voltage sensor to the scope to record the graph.
12. Use divide block and convert to multiplication operation and multiply the current and voltage outputs to get the power output.
13. Set the minimum and maximum range in X-Y graph to obtain the IV and PV characteristics.

## OUTPUT:
<img width="702" height="623" alt="image" src="https://github.com/user-attachments/assets/cd89a5b4-dab8-4d37-8be0-49c961c07d96" />


## RESULT: 
Thus, the solar PV energy system is simulated using MATLAB and the I-V and P-V graphs are determined for the given panel rating.
    
