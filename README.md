# CS4222LightAnalyzer
<br/><br/>
Team members:<br/>
1. Ong Teck Sheng (Dex) - A0097706U<br/>
2. Matthew Saw - A0097556M<br/>
3. William Kimsha - A0100234E
<br/><br/>
Task 3 - Limitations of using light sensor<br/>
1. If artificial light such as torchlight is shine on the sensor directly, the lux value will increase drastically.<br/>
2. If the user is holding the phone whereby the sensor is facing close to the body, the lux value will drop even if the user is outdoors.<br/>
3. Weather conditions will affect the lux value of outdoor readings, and indoor lighting conditions may change situationally, e.g. Room vs Photography Studio
<br/><br/>
Summary of analysis:<br/>
Please look at file "Nexus Light.xlsx" for detailed numerical analysis. </br>
For this analysis, we observed that normal indoor lighting did not exceed a lux value of 260. We also observed that outdoor sunlight far exceeds the strength of indoor light by magnitudes of order. Therefore we determined that a light threshold of 450 lux was suitable for determining if the user was indoors or outdoors in strong sunlight. Since we do not have any data for other weather conditions, we are unable to determine a better threshold that may be more universal.</br>