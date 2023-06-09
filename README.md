# Optimal Economic Dispatch Mixed-Integer Linear Program
Mixed-integer linear program that simulates the optimal economic dispatch over a 24-hour horizon for a local power system with hydroelectric generators. MATLAB code written for the Power Systems Restructuring: Operations and Economics graduate course at my undergraduate university (Spring 2022).

## Built With

* MATLAB
  * YALMIP toolbox

<!-- ABOUT THE PROJECT -->
## Project Details

Information from the power system model diagrammed in `Course Project.xlsx` was used to write a mixed-integer linear program (LP) for optimal economic dispatch.

The following data were considered when writing the mixed-integer linear program:
* Hydroelectric unit capacity limits: minimum and maximum power, startup costs, duty factors
* Reservoir elevation limits
* Locational marginal prices over a 24-hour horizon

## Power System Layout
![image](https://github.com/abrahamcanafe/power-systems-optimal-economic-dispatch/blob/main/hydro_power_system.png)


<!-- GETTING STARTED -->
## Sample output
![image](https://github.com/abrahamcanafe/power-systems-optimal-economic-dispatch/blob/main/EEE259_Final_Project_Output.png)


