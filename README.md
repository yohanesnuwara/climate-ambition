# Monte Carlo Simulation of CCS Ambition

![ccs-ambition](https://user-images.githubusercontent.com/51282928/72867252-e2ad4a00-3d10-11ea-9fb0-1a2ae3e56843.png)

In 2019, **International Energy Agency** (IEA) released a scenario in its World Energy Outlook, called the Sustainable Development Scenario (SDS), to highlight that Carbon Capture, Utilization, and Storage (CCUS) contribute to 9% reduction of global CO<sub>2</sub> emission by 2050. This reduction is meant to reach 2015 Paris Agreement. IEA stated that to reach the 9% contribution, by 2050, **the mass of CO2 captured and permanently stored (captured CO<sub>2</sub> capacity) must reach 2.8 billion tonnes per annum**. In other words, a world institute for CCS, the **Global CCS Institute** further stated that to achieve the level outlined in the SDS, **number of CCUS facilities needs to increase a hundredfold by 2040**.

Do we really have to add new CCS fields a hundredfold by 2050 to reach this target? A simulation using Monte Carlo will answer this. 

p.s. Open directly my [carbon-capture-storage-to-meet-target.ipynb](https://github.com/yohanesnuwara/climate-ambition/blob/master/carbon_capture_storage_to_meet_target.ipynb) notebook to learn and run the simulation. 

## What is Monte Carlo Simulation?

Monte Carlo Simulation is a stochastic simulation that simulates the probability of an occurence based on probable parameters. It's the same as you roll 2 dices at the same time, multiply the 2 numbers that came out, and repeat this experiment 100 times. After that, you will see a probability distribution of the multiplied results, and you know with 80% what result will come up. 

## Result

![montecarlo](https://user-images.githubusercontent.com/51282928/72867516-cc53be00-3d11-11ea-804c-458ad2dca470.png)

Opening 50 in-planned plus 75 pilot projects in operation for 30 years from 2020 to 2050 will surpass the target. 80% chance we have CO<sub>2</sub> captured and stored ranging between 34,000 to 40,500 million tons per year, far beyond the target. We can confidently surpass the target with CCS. Therefore, increasing to a hundredfold is not too necessary. 

## Resource to learn more about Monte Carlo Simulation

[Aegis](https://aegis4048.github.io/uncertainty-modeling-with-monte-carlo-simulation)
