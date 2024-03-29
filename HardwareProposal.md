<h1><b>Hardware Proposal</b></h1>
An in-depth analysis of a hardware proposal's functionality is necessary to make sure that it fits user needs. 
When evaluating the suitability of our hardware proposal for its intended application and satisfies the expectations of its users, a thorough examination was done. To do this, the team considred mutilple key points such as purpose, perforance, usability and compatibiltiy. The team was able to better grasp how a hardware proposal fits user wants and product requirements through its functioning by taking into account these elements. 
<br>
<br>
The team's design was made to collect multiple datapoints in a short perod of time in order to present relevent data quickly. Thus we used external ADCs to ensure this was possible for our two analog subsystems (them being the anemeometer and the humidity sensor). This also made it so that room could be saved on the PCB by grouping multiple systems to the same pins (the pins being clock, MISO, MOSI, and Digital input). Only needing to turn them on with a chip select pin connecting to a corresponding GPIO pin. 
<br>
Although the humidity sensor and the motor driver are their own separate componets, there is no clear anemeometer. The team didn't want to risk their being a daughter board on the parts list, since this was not allowed. The team resolved to making an analog humidity sensor with an attachment to a motor. The Operational amplifier was used to boost the amount of output to the ADC, so that it could give a wider range and thus more accurate calculations could be made.


<br><br>
![Diagram](HardwareProposal.jpg)
<br>

This was the previous board. We had to change multiple things for this project to fit user and class needs. The anemeometer had to be added into the schematic so that the microcontroller took in multiple data points. The motor driver circut is incorrect to the point of no function, so this also had to be fixed. Lastly the external ADC connected to the humidity sensor is not connected to anything, making it impossible to control if the microcontroller gets data. 
<br>
This was due to severe miscommunication, poorly guided feedback, and a misunderstanding of the subsystems in palce. 

<br><br>
![Diagram](HardwareProposal.JPG)
<br>

<a href="https://egr314-team308.github.io/Appendix#appendix-b-bill-of-materials"><u>Bill of materials</u></a><br>
