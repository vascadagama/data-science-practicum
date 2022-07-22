# Optimization of steelmaking process
## Description
In order to optimize production costs, the metallurgical plant decided to reduce electricity consumption at the stage of steel processing. We have to build a model that will predict the temperature of the steel, and also determine the importance of the factors that affect the temperature.
## Description of processing steps
Steel is processed in a metal ladle with a capacity of about 100 tons. To withstand high temperatures, the ladle is lined with refractory bricks from the inside. Molten steel is poured into a ladle and heated to the desired temperature with graphite electrodes. They are installed in the lid of the bucket.

Sulfur is removed from the alloy (desulfurization), the chemical composition is corrected by adding impurities, and samples are taken. Steel is alloyed - its composition is changed - by feeding pieces of alloy from a bunker for bulk materials or wire through a special tribe apparatus (English tribe, "mass").

Before introducing alloying additives for the first time, the temperature of the steel is measured and its chemical analysis is carried out. Then the temperature is raised for several minutes, alloying materials are added and the alloy is purged with an inert gas. Then it is stirred and measured again. This cycle is repeated until the target chemical composition and optimum melting temperature are reached.

Then the molten steel is sent to finish the metal or enters the continuous casting machine. From there, the finished product comes out in the form of slabs.
## Input data
- data_arc.csv - data about the electrodes;
- data_bulk.csv - data on the supply of bulk materials (volume);
- data_bulk_time.csv - data on the supply of bulk materials (time);
- data_gas.csv - data on gas purge of the alloy;
- data_temp.csv - temperature measurement results;
- data_wire.csv - data on wire materials (volume);
- data_wire_time.csv - data about wire materials (time).

## Tools/Libraries
*Python, Pandas, Scikit-learn, Numpy, Catboost, Seaborn*
