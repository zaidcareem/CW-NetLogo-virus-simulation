# Virus Simulation Using NetLogo

##	There are 4 types of people in this simulation.

>	- Healthy un-affected (Green) <br>
>	- Unhealthy un-affected (Orange) <br>
>	- Affected (Red) <br>
>	- Recovered (Blue)

The slider named “%unhealthyMaskWearers” refers to the percentage of unhealthy people who are wearing masks.

The slider named “%healthyMaskWearers” refers to the percentage of healthy people who are wearing masks.

There is a slider named “%infectiousness” which denotes the infectiousness of the virus. Once this is set to a value of choice by the simulator and the simulation started, based on this value and whether the person is masked or not, the healthy and un-healthy people’s susceptiveness to the virus will be assigned as follows.
> -	Healthy-masked	: 50% of the infectiousness <br>
> -	Healthy-unmasked	: 70% of the infectiousness <br>
> -	Unhealthy-masked	: 90% of infectiousness <br>
> -	Unhealthy-unmasked	: 100% of infectiousness

Lockdown and Social Distancing functionality can be implemented by setting the value of the slider named “travellingDistance” to 0. This means people remain stationary, not travelling. Thus, reducing the chance of infecting others.

While simulation is in lockdown state, if multiple people happen to be in the same patch, analogize it as a family living in the same house, they will be inside the house at the time of lockdown also.