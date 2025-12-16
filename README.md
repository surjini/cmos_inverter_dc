# cmos_inverter_dc
## REG NUM :25015534
## NAME :Surjini.R
## EXPERIMENT 2.b Design CMOS inverter and Perform DC and OP analysis.

## Aim: To Design CMOS inverter and Perform DC and OP analysis.

## Tools Used: 
Virtuoso Schematic Editor is used for the design and analysis.

## Theory:
CMOS inverter consists of a p-channel MOSFET(PMOS)and an n-channel MOSFET(NMOS)connectedinseriesbetweenthepowersupply(V_DD)andground.Whentheinputvoltage is low, the PMOS transistor turns ON, pulling the output to high (V_DD),while the NMOS is OFF. When the input is high, the NMOS turns ON, pulling the output to low (ground),and the PMOS turns OFF. This complementary action produces an output that is the logicalInversion of the input. CMOS inverter shave low static power consumption and high noise margins, making them ideal for digital logic circuits.

## Procedure:
•	Click new->libraryattachtoanexistingtechnologylibrarygpdk045(in technology file)
•	New cell view (name of the layout)

## For schematic:
A.TRANSISTOR DIAGRAM 

<img width="183" height="159" alt="cmos INVERTER DIAG" src="https://github.com/user-attachments/assets/8ff9a85b-ea31-4e90-9178-3e4b215f5db5" />

Fig: CMOS inverter Transistor schematic

B.CADENCE DIAGRAM 
•	Pick the components NMOS, PMOS, ground, VDD and voltage source.
•	Connect the wire as per the schematic diagram.

<img width="937" height="455" alt="image" src="https://github.com/user-attachments/assets/d4d97ee1-afd8-4d2e-8055-66f544c4caf7" />

Fig: CMOS inverter schematic

## For symbol:

<img width="952" height="483" alt="image" src="https://github.com/user-attachments/assets/1d7e26ab-a96a-4fd3-a048-5f68b2b16daa" />

Fig: CMOS inverter symbol

## DC Analysis and OP:
a)	In the Analysis section, select dc.
b)	In the DC Analysis section, turn on Save DC Operating Point.
c)	Turn on the Component Parameter.
d)	Double Click the Select Component, which takes you to the schematic window.
e)	Select input signal vpulse source in the test schematic window.
f)	Select “DC Voltage” in the Select Component Parameter form and click OK.
g)	Intheanalysisformtypestartandstopvoltagesas0to1.8 respectively.
h)	Check the enable button and then click Apply.
Click OK in the Choosing Analyses Form.
DC Operating Point:
a)	In Simulation Window, select Results and choose Print Option and click on DC Operating Point
b)	Select the component from the schematic.

## Execute Outputs:
To be plotted–Select on Schematic in the simulation window.
Follow the prompt at the bottom of the schematic window, Click on output net Vout, input net Vin of the Inverter.

## Waveform:
<img width="975" height="553" alt="image" src="https://github.com/user-attachments/assets/ccaf1fa9-b92a-42fe-9b28-fe6456a61442" />



## RESULT:
Design of CMOS inverter and dc analyses is performed and output waveforms are obtained. 





