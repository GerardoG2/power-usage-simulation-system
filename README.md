# power-usage-simulation-system

Power Simulation Instructions

1. Add your txt or csv file which holds all of the appliances and their info, such as the app.txt into the project folder. This file should have all the appliance details separated by commas- in the following format: LocationID,ApplianceDescription,OnWattage,ProbabilityOfBeingOn,isSmart(represented by true or false),percentPowerReduction(double between zero and one)

2. Add the Main.java , Appliance.java , and Location.java files to the same package folder. 

3. Run Main.java

4. Enter the inputs requested by the program. Allowed wattage (int), timesteps (int), and the name of the input file.

5. The user is prompted to select an option from the menu. Follow the directions on screen and select your desired option.

6. When the simulation is complete there will be two outputs:
      OUTPUT TO SCREEN: Total appliances set to low per timestep,total browned out locations per timestep, total affected locations per timestep, max affected location of            the entire simulation
      FILE OUTPUT: output.txt file containing the appliances affected per timestep, the locations affected per timestep
