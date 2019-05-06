# Project title: Who treated it better? Membrane vs. StaRS edition
Team: gueSSeR
Team members: Rafael Heryapriadi, Sidney Lok, Steven Neumaier

## Introduction
Membrane filtration is an up-and-coming type of filtration option for water treatment plants. Membrane filtration is attractive because the pores are small enough to capture small bacteria like Cryptosporidium oocysts and the filter sheets are thin so they can be "stacked" very easily. This is a huge plus for saving space while efficiently filtering out nasty particles.

The goal of our design project is to compare the efficiency, cost, and feasibility of membrane filtration to AguaClara's Stacked Rapid Sand (StaRS) filters. AguaClara plants are designed with a purpose: to make safe drinking water more accessible to those who cannot afford a traditional drinking water treatment plant. Cost and efficiency of design are important to AguaClara plant design, so our work would reveal whether membrane filtration would be a better alternative to the existing StaRS filter.

## Our Plan
Our plan is use one of the AguaClara plants San Nicolás in Honduras as a comparison to the low pressure membrane from PALL.

 We are going to calculate the total material cost of both system (AguaClara sand filter and PALL membrane), excluding the labor. In this calculation we will need to consider the total area of most efficient and also the lifespan of both system.

 After comparing the cost, we will then see what is the most economical option to build the system. We then will get the technical data from PALL so we can compare the turbidity, types of pathogen (Giardia, Cryptosporidium) filtered, and also the flux of the system.

 Lastly, we will compare the average lifespan of the systems assuming both are handled with good maintenance.

Data to ask PALL and to get from AguaClara:
 - cost!!!!!
 - temperature - 33 degF to 104 degF
 - particle concentration (turbidity) ... influent = ? , effluent < 0.1
 - plan view area - we have

Pore size for membranes:
4-6 um Cryptosporidium
8-14 um Giardia

Membranes remove 99.9999% of Giardia and Cryptosporidium (6 log)


Flow rate of Moroceli plant: 16 L/s
Average turbidity before floc/sed: 14.23 NTU
Turbidity after floc/sed: 0.56 NTU
Average turbidity after filtration: 0.20 NTU
**Note: Data was taken from files that Monroe sent us from 2016**

## Important constraints
Some contraints we think will be important to our research are:
1. Plant Flow
2. Effluent Water Quality
3. Access to Electricity
4. Feed Water Quality
5. Chemical Cleaning Regime
6. Preventative Maintenance Program
7. Pretreatment Process/Chemistry, Cost/Benefit Evaluation at End of Membrane Life

##Trade-offs
Stack sand filter vs. Membrane filtration

Advantages of Membrane filtration
1. Less influenced by influent water conditions - flow and water quality
2. Effluent quality is mostly constant
3. Provide a physical barrier against suspended solids and smaller, nasty particles like Cryptosporidium, Giardia, Bacteria, Colloids
4. No need to buy coagulant

Disadvantages of Membrane filtration
1. Requires a pump and therefore requires electricity.
2. Flux depends on temperature and is greatly reduced in low temperatures
3. May require pumping air in for physical backwash and integrity testing
4. Requires chemical backwash - sodium hydroxide/hypochlorite or citric, sulfuric, phosphoric, or hydrochloric acids
5. Unable to remove dissolved organics as AguaClara floc/sed processes can with coagulant
6. Electricity and chemical costs


## Design alternatives
Membrane filtration is seen by many as an alternative for using flocculation, sedimentation (or floc/sed), and filtration. It is believed that using a membrane filter of a certain pore size will treat water as well as following the processes typically associated with flocculation, sedimentation, and filtration.

We will investigate the following three design alternatives:
1. Full AguaClara plant
2. AguaClara floc/sed + membrane filtration
3. Only membrane filtration

## Comparison of Design Alternatives
As mentioned before, the baseline for our comparisons will be the San Nicolás AguaClara plant. This plant handles 32 L/s flow.

We looked at several different membrane filtration systems that are commercially available. The Pall Corporation quoted us a system called the Pall Aria AP-6 Water Treatment System. This is the system we used in our comparison.


<p align="center">
  <img src="https://github.com/sidneylok/Personal/blob/master/Membrane%20v%20AguaClara%20Decision%20Tree%20(1).jpg?raw=true" height=500>
</p>
<p align="center">

**Figure 1:** A decision tree we made from our research that should help a user decide which technology to use.

### Cost
The code to calculate the cost of an AguaClara StaRS filter and of a membrane module for a 16 L/s plant is shown at the end of the report in the Calculations section.

Minty, an AguaClara engineer based in Honduras, provided us with the cost of a AguaClara stacked sand filter. The cost of one filter including the control box is 18500 USD, including materials and labor only. We will use this estimate to approximate the cost of a plant's stacked sand filtration system to be 1000 USD per L/s.

The cost of the AguaClara StaRS filter ended up coming to 16000 USD.

 The model number AP-6 may have up to 60 modules and treats between 45 and 150 m^3/hr of water. They quoted the price to be .... for the system. (This information is still yet to be retrieved. We were unable to get this information from the phone calls we made to the companies.) Utility requirements for the Aria AP-6 System are 460v and 70 A. Chemical costs are not published... cal, Pall for recommended CIP procedures and specifications for chemicals Must call again for this info. The lifetime of the Aria Membrane filters are 10+ years.

The cost of the Pall Aria AP-6 came out to ...

### Temperature
The Pall Aria module data sheet mentions that the maximum temperature that the module could operate in is 40 degrees Celsius. However, membrane filters are known to not do so well with colder water temperatures. According to Farahbakhsh and Smith (2006), interactions between the temperature and the polymeric membrane may result in lower porosity and increased tortuosity at lower water temperatures. As AguaClara plants are able to operate without much dependence on water temperature, this should not be a problem.

Therefore, in comparing AguaClara plants with membrane filters for decision-making on which technology to use, AguaClara plants may be the better bet in regions that experience colder temperatures while both AguaClara plants and membrane filters are feasible in hotter regions.

### Particle Removal
AguaClara plants typically have an output turbidity of 3 NTU, meeting Honduran standards but not US EPA standards. The Pall Aria module data sheet notes that the output turbidity of their filters should be less than 0.1 NTU, which is under US EPA standards. The Pall Aria module is also capable of removing Cryptosporidium, Giardia, and MS2 coliphage or bacteriophage.


### Plan-view Area
The specifications of the Pall Aria Module say that the required space for the AP-6 system is 27 feet by 17 feet. An AguaClara StaRS filter is approximately $4m^{2}$ (Monroe estimate).

The AguaClara StaRS filter is much smaller than the necessary membrane filter equivalent. However, the data we have for the AguaClara StaRS filter does not include the footprint for the control system. Neither include the space for operators to access the filter controls.

The footprint of an AguaClara StaRS filter is $4 m^{2}$ and the footprint of the Aria system is $42.64 m^{2}$.


## Calculations
We are planning to make our calculations for designing the membrane filter to be adaptable to any flow rate needed to be designed for. However, for the purposes of comparing design alternatives, we will be using the Moroceli plant StaRS filter as a baseline for efficiency, cost, and feasibility perspectives.

```python
import aguaclara
from aguaclara.core.units import unit_registry as u
import numpy as np
from aguaclara.core import utility as ut
import math as m

```
Here are the dependent variables or inputs for the calculations of costs and plant areas.

```python
#Using the Moroceli plant as a baseline for comparison
Design_Plant_Flow_Rate = 16 * u.L/u.s
#Average electricity cost in Honduras from https://energypedia.info/wiki/Honduras_Energy_Situation
elec_cost = 0.1034 * u.USD / u.kWh
```
**Cost estimation**
Our estimated cost for an AguaClara plant stack sand filter with control is:

```python
StaRS_Cost = Design_Plant_Flow_Rate * 1000 * u.USD / (u.L/u.s)
print('An AguaClara stacked sand filter that treats', Design_Plant_Flow_Rate, 'is a one time cost when you do not include maintenance or labor that is ', StaRS_Cost)
```

Our estimated cost of the Pall Aria AP-6 system is:
```python
#Given values for Aria AP-6 system
Max_Aria_flux = 150 * u.m ** 3 / u.hr
Aria_price = 1 * u.USD
Number_Aria_skids_necessary = m.ceil(Design_Plant_Flow_Rate / Max_Aria_flux)
Aria_lifetime = 10 * u.year

#Electricity requirements for Aria AP-6 system
Voltage = 460 * u.V
Current = 70 * u.A
Wattage = Voltage * Current
Energy_Cost = (Wattage * 24 * u.hr * elec_cost / u.day).to(u.USD/u.day)

#Chemical costs are unknown right now. Need to get information from Pall
Chemical_Cost = 1000 * u.USD / u.year

#Annual Cost Analysis
Other_Costs = Chemical_Cost * Aria_lifetime + Energy_Cost * Aria_lifetime
Total_Aria_Cost = Number_Aria_skids_necessary * Aria_price + Other_Costs
Annual_Aria_Cost = Total_Aria_Cost / Aria_lifetime

print('The annual cost for the Aria Membrane system, excluding labor and maintenance is ', Annual_Aria_Cost)
```

**Size Comparison**

```python
StaRS_Footprint = 4 * u.m ** 2
Aria_Footprint = 27 * u.ft * 17 * u.ft

print('The footprint of an AguaClara StaRS filter is ', StaRS_Footprint, 'and the footprint of the Aria system is',Aria_Footprint.to(u.m**2))
```
