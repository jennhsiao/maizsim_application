## Assessing Climate Impacts on Yield with a Process-based Crop Simulation Model
### Objective
In this problem set we are going to investigate the influence three different climate factors have on crop growth and yield: temperature, vapor pressure deficit, and atmospheric CO2 concentrations. We will use outputs of a process-based crop simulation model to help us tease apart the independent impacts each of these climate factors have on crop yield, and gain a mechanistic understanding on how various physiological processes respond to climate perturbations. 

### Model experiments and output
We have model outputs of a process-based crop simulation model for 5 model experiments: Control, warmer temperature (Temp), higher vapor pressure deficit (VPD), elevated atmospheric CO2 concentrations (CO2), and the combination of all three. 
-	“Control”: model simulations ran with weather station data input
-	“Temp”: 2˚C warming without drying the air (no change in VPD).  
-	“VPD”: drying of air associated with 2˚C warming, but with temperature held constant.
-	“CO2”: doubling CO2 levels from 400 ppm to 800 ppm.
-	“All”: a combination of changes in Temp, VPD and CO2.

* Some background: VPD is an atmospheric index used to describe the dryness in the air. A higher VPD indicates a drier environment. Under natural environments, VPD is tightly correlated with temperature – when temperature increases, VPD often increases as well (air dries when you warm it; think when you turn on the heater in your house in winter). 

We can use these experiments to identify what magnitude of impact each of these projected changes in climate factors will have on crop growth and yield, as well as understand their overall combined effect. If you feel ambitious, you can look into the interactions between each climate treatment as well. We can also use the various model outputs (see below for a list of selected model outputs) to better our understanding on the physiological processes involved in shaping final yield, and how they might be affected under a changing climate. 

### General Guidelines
1.	Choose one location within the dataset that you wish to analyze. There are simulations from 4 maize growing regions in the US (Iowa, Nebraska, Ohio, and Oklahoma). The simulations are all for the growing season of year 2011. 
2.	Analyze the impact each climate factor (Temp, VPD, CO2) had on final yield. 
3.	Analyze the yield impact of all climate treatments combined (All). 
4.	Choose at least two physiological model outputs (see below for list of model outputs) and analyze how these processes were influenced by the climate treatments.
5.	Bonus analysis: Compare between locations. Are there differences between climate impacts on final yield?
6.	Bonus analysis: How do responses differ between phenological stages throughout the growing season?
7.	Bonus analysis: look into how temperature, VPD and CO2 interact with one another to influence final yield.

### Model Outputs
Here is a selection of relevant model outputs: 
-	jday: day of year
-	date: month/day/year
-	time: hour of day
-	Leaves: number of leaves developed
-	Dropped: number of leaves dropped
-	LA.pl: total leaf area (cm2)
-	LAI: leaf area index 
-	LeafWP: leaf water potential (MPa)
-	ETdmd: potential evapotranspiration (g H2O plant-1 hr-1) 
-	ETsply: actual evapotranspiration water supply from soil (g H2O plant-1 hr-1)
-	Pn: net photosynthesis (g plant-1 hr-1) 
-	Respir: respiration (g plant-1 hr-1)
-	av_gs: averaged hourly stomatal conductance (g H2O m-2 s-1)
-	totalDM: total dry mass (g)
-	shootDM: shoot dry mass (g)
-	earDM: ear dry mass (g)
-	GrleafDM: green leaf dry mass (g)
-	rootDM: root dry mass (g) 


### Model Applications and Interpretations	
1. Which location did you choose to analyze?
2. Analyze the yield impact of each climate treatment (Temp, VPD, CO2): 
    - Plot out ear biomass throughout the growing season for all three treatments. Briefly describe your results and any additional 
      patterns you observed. The value at the very end of the growing season can be interpreted as final yield.
    - Compare the final yield simulated under each climate treatment with the control simulation: <br/>
      Yield Impact=(Yield_treatment-Yield_control)/Yield_control * 100%

3. Analyze how physiological processes were influenced under each climate treatment: 
    - Which model outputs did you choose to analyze and why (list at least two)? 
    - Plot out how your chosen model output changed throughout the growing season for all three climate treatments. 
    - Calculate the percent change of your model output following the equation: <br/>
        ∆Model Output=(Model Output_treatment-Model Output_control )/Model Output_control *100%
    - How did each climate treatment influence these processes? 
    - Which process was influenced by the climate treatment the most?
4. Provide a mechanistic explanation of your results from question 3: what do you think led to the changes you saw in your chosen physiological processes? How do you think that contributed to the final yield?
5. Following question 2, what was the yield impact when all climate treatments were combined (All)? Briefly describe your results.
6. Describe how an overall changing climate can influence crop growth and production based on the climate impacts and physiological responses you analyzed in questions 2-5. 
