Charging speed is one of the most significant factors for batteries. To rival the gasoline-powered vehicles, and hence reduce transportation-related emissions, electric vehicles need batteries that charge quickly. Moreover, enabling truly fast charging will improve the experience of billions of battery-powered devices such as cellphones, computers, power tools, drones, robots, and so on. Though the caveat is that the fast charging reduces the longevity of a battery. The faster the charging, the shorter the life of a battery. 

## GBatteries approach and challenges
GBatteries Inc. is developing protocols for fast-charging of off-the-shelf li-ion batteries that defy the relationship between speed and longevity. A protocol generates the complex pulses for charging based on values of 36 charging parameters. The values of these parameters can be adapted within a charging cycle or between cycles based on real-time monitoring and analysis of a battery's internal state. The GBatteries Active Battery Management System (ABMS) periodically measures a degradation indicator (di) while charging. Higher di values are associated with more degradation of a cell in the long term. The values of charging parameters can be adapted to reduce di. However, the drawback to adjusting parameters in this way is that it usually also reduces the charging speed. But It is observed that, for some magical set of parameter values, the inverse relationship between longevity and the speed is defied.

The goal when developing the protocol is to find the best parameters that minimize the degradation and meet or exceed the charging speed requirement while complying with the system constraints (for example, the power delivered, maximum temperature, etc.). To evaluate a set of parameters, a battery is charged and discharged for as many cycles as possible before it dies. As most batteries cycle for hundreds (or sometimes thousands) of cycles before being obsolete, this results in months of testing. Iteratively sweeping through all possible sets of parameters could take forever. Also, this process incurs the cost of electricity. 

## Objective of the project

![alt text](https://github.com/VijayMaraviya/Charging-Process-Modelling/blob/master/Input%20and%20output%20of%20the%20charging%20process.png)

The objective of this project is to leverage the GBatteries’ dataset to develop a model of a charging process where inputs are charging parameters and outputs are degradation indicator and speed. The model that explains the functional relationship of degradation indicator and charging speed with charging parameters would provide the most value. An explainable model can be used to form an optimization problem to find the best parameters.

Read more in the[a relative link](Project_Report.pdf)
