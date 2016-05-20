# Residential Energy Efficiency Optimizer

This software makes inferences about the structural and behavioral drivers of
HVAC demand in single family residential houses.  These inferences can be used to compare, in one house, the relative
importance of different loads, such as losses due to leaky windows and doors, heat load from an attic space that may not be well insulated, conduction to the outside air, conduction to the ground underneath a home, heat load from solar flux on unshaded areas, and heat load from variable behaviors of occupants. In the case where the thermostat setting is not available as data to the software, an equivalent thermostat setting is inferred. In the case where thermostat data is available, the machine learning algorithm can be run with that data as input to get more accurate estimates of various loads, as well as providing a rough measure of whether the thermostat is located properly to monitor the "average" house circulating air.  

Across a set of buildings, these inferences can be used to understand the
likely reasons why one building’s usage is extraordinary in the context of the population. This comparison
can be used by an electric utility, for example, to target its outreach and communication efforts based on
an understanding of the most likely drivers of HVAC demand. The example use case is for utilities to
target their residential energy efficiency (EE) incentive programs.

This project is a work in progress.  Collaborations are welcome!
