<h2> New 3D Printer </h2>

<h3> Introduction </h3>
<h4> Background </h4>
In 2016, I built an Anet A8 budget 3D printer from a kit. During two years of use, the following
issues became evident: <br>
• Print quality (surface quality and amount of ringing) rapidly degraded with an increase in
print speed <br>
• A lack in frame sturdiness caused low quality parts from shaking
induced by the moving axes <br>
• Bolts loosened with use causing rapid degradation in calibration,
giving rise to repeated long setup times <br>
• The heat bed was underpowered and could not heat up quickly or
reach temperatures above 95℃ (required to print certain plastics) <br>
• Print volume was limited to 220x220x230mm

<h4> Engineering Goal </h4>
The goal of this project is to design and build and improved, easy to run, budget 3D printer costing less than $750 for home users to create high quality, high speed prints with a minimum print volume of 275x275x325mm (2.475x10<sup>7</sup>mm<sup>3</sup>).

<h4> Criteria and Constraints </h4>
• Parts and materials must cost less than $750 <br>
• At a print speed of 60mm/s, ringing must be less than a 3 on a ringing scale of 1-6 (1 is negligible, 6 is significant) and roughness must be less than a 3 on a roughness scale of 1-6 (1 is smooth, 6 is rough) <br>
• Print tolerance of ±0.2mm on a 25mm cube <br>
• A minimum print volume of 275x275x325mm (2.475x107mm3) <br>
• Sturdy frame and design <br>
• Powerful heat bed capable of quickly heating to more than 110℃ <br>

<h4> Test Plan </h4>
The following tests were printed on both the Anet A8 and the new printer. The test prints were
then compared and analyzed. <br>
1. Calibration cubes (25x25x25mm) at print speeds from 30-80mm/s in 10mm/s steps with an
acceleration of 1250mm/s2 testing for: <br>
&nbsp&nbsp&nbsp&nbspa. Ringing <br>
&nbsp&nbsp&nbsp&nbspb. Surface quality <br>
&nbsp&nbsp&nbsp&nbspc. Tolerance <br>
2. #3DBenchys to test the ability to print difficult features (such as overhangs, bridges, complex
rounded shapes, etc.) <br>
3. Paper Basket Torture Tests to verify the maximum practical print volumes and identify any
additional common printing issues  <br>


<h4> Results/Conclusion </h4>
<table>
  <tr> <th>Critera and Constraints</th> <th>Result</th> </tr>
  <tr> <td>Parts and materials must cost less than $750</td> <td>✓</td> </tr>
  <tr> <td>At a print speed of 60mm/s, ringing must be less than a 3 on a
ringing scale of 1-6 (1 is negligible, 6 is significant) and roughness
must be less than a 3 on a roughness scale of 1-6 (1 is smooth, 6
is rough)</td> <td>✓</td> </tr>
  <tr> <td>Print tolerance of ±0.2mm on a 25mm cube</td> <td>✓</td> </tr>
  <tr> <td>A minimum print volume of 275x275x325mm (2.475x10<sup>7</sup>mm<sup>3</sup>)</td> <td>4% less than
theoretical due to V3 of Hotend Carriage</td> </tr>
  <tr> <td>Sturdy frame and design</td> <td>✓</td> </tr>
  <tr> <td>Powerful heat bed capable of quickly heating to more than 110℃</td> <td>✓</td></tr>
</table>

<h3>
Warning! This project involves AC wiring and temperatures in excess of 200&degC. Proceed only if you are sure that you know what you are doing!
</h3>

<h3> BOM and Cost </h3>
See BOM.pdf for a list of the parts that need to be purchased. The total cost is around $725. However, your actual cost may vary depending on shipping, tax, etc. Note: the two rolls of PLA filament quoted are an estimate of how much plastic was used. You may find that you need more filament. Also, while you may be able to find cheaper alternatives to some of these parts, please be careful when economizing on very important parts such as the hotend. Some parts may need modification to work properly.

<h3> Tools </h3>
A list of the tooling required is in Tooling.pdf. Please tell me if you find you need more tools so I can add those tools to the list.

<h3> 3D Printed Parts </h3>
The STL files for the 3D printed parts are in the STL files folder. See Printed Parts.pdf for the amount of each part that needs to be printed. Note: some designs may need small modifications after printing such as enlarging holes. Some of these modifications are listed in the Printed Part.pdf file. Please notify me of any modifications made to the parts so that I can update the design files.

<h3> Assembly </h3>
<h4> Step 1: Aluminum Frame </h4>
First, print some of the M6 spacers (see Printed Parts.pdf). Next, prepare an aluminum L-bracket as shown below with two T-slot nuts, two M6x20 screws and two spacers. Repeat this for 28 of the L-brackets.

<img alt="Side of bracket" src="/Images/1.%20Frame/L-bracket.jpg" align="top" width="200"><img alt="Top of bracket" src="/Images/1.%20Frame/L-bracket-top.jpg" align="top" width="200">

<br>

Lay out four of the 470mm lengths of aluminum extrusion; this will create the bottom. Place an aluminum L-bracket at each intersection and start to tighten the screws. Use a square to make sure the frame is square. Repeat these steps for the top (using the remaining four 470mm extrusions). Next, attach the 440mm extrusions at the four corners of the bottom frame using two angle brackets. Use the square to check that the frame is still square. Finally, place the top on top of the 440mm extrusions and attach using the same method as the bottom. Tighten the screws fully while checking the entire frame for squareness. 

<img alt="Partially assembled frame" src="/Images/1.%20Frame/Assembling_frame.jpg" align="top" width="200"><img alt="Three-way joint" src="/Images/1.%20Frame/Joint.jpg" align="top" width="200"><img alt="Assembled frame" src="/Images/1.%20Frame/Complete_frame.jpg" align="top" width="200">

<h4> Step 2: IKEA Lack Tables </h4>

Print the files in the ... in the STL files folder. Attach the four type _ Mounting/Strengthening Brackets to the bottom of the lower table. Next, place the upper table on top of the lower table and use four of the type _ brackets to attach them together. Finally, attach the remaining four type _ brackets to the underside of the upper table.

<img alt="Caster adaptor" src="/Images/1.%20Frame/Caster_adaptor.jpg" align="top" width="200"><img alt="Table mounting/strengthening bracket" src="/Images/1.%20Frame/Mounting_bracket.jpg" align="top" width="200"><img alt="Assembled Tables" src="/Images/1.%20Frame/Tables.jpg" align="top" width="200">

<h3> Wiring </h3>
Line up the pins of the RAMPS 1.4 board with the sockets on the Arduino Mega (after the Arduino Mega is fully screwed down onto the IKEA Lack table). Press the RAMPS 1.4 board down until the pins are fully into the Arduino Mega. Next, solder wires to the switch as shown below in the pictures. Follow the wiring diagram below (this diagram is in SVG format and can therefore be scaled) (Note: some wires/cables might need to be extended. You can also splice four wires into the multi-core cable instead of using seperate pieces of wire (see pictures below for an example)). Add 3D-printed wire clamps (see the STL files folder and Printed Parts.pdf), zip-ties and labels as necessary. Below the wiring diagram are some pictures of the wiring.

<h4> Wiring Diagram </h4>
<img alt="Wiring schematic SVG" src="/Images/Wiring/Wiring.svg">

<h4> Switch wiring </h4>

<img alt="Switch wiring back JPG" src="/Images/Wiring/Switch_Wiring.jpg" width="200"><img alt="Switch wiring front JPG" src="/Images/Wiring/Switch_Finished.jpg" width="200">

<h4> Starting Wiring </h4>

<img alt="Starting wiring JPG" src="/Images/Wiring/Starting_Wiring.JPG">

<h4> Finished Wiring </h4>

<img alt="Finished wiring JPG" src="/Images/Wiring/Finished_Wiring.JPG">



<h3> Firmware </h3>
Marlin firmware is used for this 3D printer(see <a href="https://marlinfw.org">marlinfw.org</a>). The Marlin Configuration folder stores the changed configuration files in Marlin. See MODIFICATIONS.txtfor how to install the configuration files and upload Marlin to the Arduino Mega.

<h3> Software </h3>
I recommend using Ultimaker Cura for slicing. Cura can be installed from <a href="https://www.ultimaker.com/en/products/ultimaker-cura-software">the Ultimaker website</a>. A sample profile is the main directory. Follow the instructions detailed on <a href="https://www.ultimaker.com/en/resources/20441-manage-profiles">this page on the Ultimaker website</a> to load the profile. To perform one of the test prints: load the test cube from the STL files folder into Cura, slice the cube, and put the GCODE on an SD card. Insert the SD card into the 3D printers LCD sreen controller board and select the file from the menu.

<h3> License and Credits </h3>
All work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license, except for the Marlin configuration files. Note: the Marlin configuration files (Configuration.h, Configuration_adv.h, pins_RAMPS.h, ultralcd.cpp) are licensed differently because they are from Marlin (see <a href="https://marlinfw.org">marlinfw.org</a>). For those files, see the LICENSE in the Marlin Configuration directory. This design was inspired by Tech2C's Hypercube, but all of the parts were designed by me from scratch.
