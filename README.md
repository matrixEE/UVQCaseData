# UVQCaseData
The power generation and load data in the case studies of the paper "Uncertain Voltage Quantification for Risk-Constrained Volt/Var Optimization in Power Distribution Systems".  
The active power outputs of photovoltaic units are obtained using the actual solar irradiation data provided by SolarAnywhere [1]. The load data are obtained by normalizing the load drawn from real-world measurements [2], and then multiplying it by the nominal load from the original load data of the systems [3], [4].

## The power generation and load configuration of the modified IEEE 33-bus system
The system contains 4 PV units and 32 power loads. The nominal power generation of each PV unit is 1 MW and the nominal load of each bus is found in [3].  

## The power generation and load configuration of the modified IEEE 123-bus system
The system contains 9 PV units and 85 power loads. The nominal power generation of each PV unit is 0.8 MW and the nominal load of each bus is found in [4].  

## File format
".mat" type of Matlab.  
"IEEE33_PV&Load_Data.mat' is the data file in the modified IEEE 33-bus system.  
"IEEE123_PV&Load_Data.mat' is the data file in the modified IEEE 123-bus system.

## Variable format:  
"PV_hourly_normalized" is the hourly data of the normalized active power of PV units, of which each column represents a PV unit.    
"load_hourly_normalized" is the hourly data of the normalized loads, of which each column represents a load.  
"timeLabel_hourly" is the time label of the hourly data from Jan. 1, 2011 to Dec. 31, 2014.  

## Reference
[1]	[Online]. Available: https://data.solaranywhere.com/Data/Public  
[2]	Trindade, Artur. ElectricityLoadDiagrams20112014. UCI Machine Learning Repository, 2015. doi: 10.24432/C58C86.  
[3]	S. K. Goswami and S. K. Basu, “A new algorithm for the reconfiguration of distribution feeders for loss minimization,” IEEE Trans. Power Del., vol. 7, no. 3, pp. 1484–1491, Jul. 1992, doi: 10.1109/61.141868.  
[4]	L. Bobo, A. Venzke, and S. Chatzivasileiadis, “Second-order cone relaxations of the optimal power flow for active distribution grids: Comparison of methods,” Int. J. Electr. Power Energy Syst., vol. 127, 106625, May 2021, doi: 10.1016/j.ijepes.2020.106625.  


