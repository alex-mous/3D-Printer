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

<h6> Note: drywall screws refers to the 1 1/2" screws unless otherwise noted. </h6>

Print all of the files in the Parts for IKEA Lack tables folder in the STL files folder as directed in Printed Parts.pdf. Attach the four type 1 Mounting/Strengthening Brackets to the bottom of the lower table. Next, place the upper table on top of the lower table and use four of the type 2 brackets to attach them together. Finally, attach the remaining four type 2 brackets to the underside of the upper table. To attach the casters, first push the caster adaptor onto the table leg. Next screw in the two drywall screws on the side. Finally, place the caster on top of the adaptor and screw in four of the 2" drywall screws.

<img alt="Caster adaptor" src="/Images/2.%20IKEA%20Lack%20tables/Caster_adaptor.jpg" align="top" width="200"><img alt="Table mounting/strengthening bracket" src="/Images/2.%20IKEA%20Lack%20tables/Mounting_bracket.jpg" align="top" width="200"><img alt="Assembled Tables" src="/Images/2.%20IKEA%20Lack%20tables/Tables.jpg" align="top" width="200">

Next, attach the main electronics (power supply, SSR, and Arduino/RAMPS combination) to the underside of the top table. Place the electronics as shown below and screw down using drywall screws. (I will cover the wiring later. You may notice that the power wires are soldered to the RAMPS board. That is because the RAMPS board I recieved did not come with an input jack. If your RAMPS also does not come with an input jack, either find an input jack or modify the RAMPS board as I did.)

<img alt="Electronics placement" src="/Images/2.%20IKEA%20Lack%20tables/Electronics_placement.jpg" align="top" width="300"><img alt="Power Supply" src="/Images/2.%20IKEA%20Lack%20tables/Power_supply.jpg" align="top" width="200">

For the filament storage, two PVC pipes are clamped on the sides of the upper IKEA Lack table with PVC Pipe Clamps and the remaining two pipes are clamped perpendicular to the sides with PVC Pipes Joiners. To install the PVC Pipe Clamps, carefully measure and mark half-way between the top and the bottom of the upper table on all four table legs. Next, using the square, create a line that passes through the marks on the legs. Place the PVC Pipe Clamp on the leg and mark where the holes should go. Finally, drill the holes and screw the PVC Pipe Clamps on. Slide a PVC pipe through one of the PVC Pipe Clamp, two of thw PVC Pipes Joiners and finally through the another PVC Pipe Clamp.

<img alt="PVC Pipe Clamps test fit onto PVC pipe" src="/Images/2.%20IKEA%20Lack%20tables/PVC_pipe_clamps.jpg" align="top" width="500">

<img alt="PVC pipes joiner" src="/Images/2.%20IKEA%20Lack%20tables/PVC_pipe_joiner.jpg" align="top" width="175"><img alt="Mark the place where the PVC Pipe Clamps go" src="/Images/2.%20IKEA%20Lack%20tables/Marking_PVC_pipe_clamp_holes.jpg" align="top" width="200"><img alt="Fully installed PVC Pipes" src="/Images/2.%20IKEA%20Lack%20tables/PVC_pipes_installed.jpg" align="top" width="225">

<h4> The next two steps involve using TAP Acrylic Cement, which contains a chemical that is suspected of causing cancer. Follow all precautions labelled on the can or use a different adhesive. </h4>
Next, the acrylic hinges need to be attached to two spacers each, drilled with two holes for the coarse thread screws, and attached to the acrylic door panels (the panels on the front and the back of the printer). Also, door knobs need to be attached to the door panels. First, use a saw to cut six 10x25 mm pieces from the 10x10cm acrylic spacer panel. Next, place a spacer on one side of a hinge, making sure that the spacer does not interfere with the joint. Add a drop of acrylic cement to the crack between the hinge and the spacer (the acrylic cement should be automatically spread out inside the crack with capillary action). Repeat these steps for five more acrylic hinges (for a total of six hinges with spacers). Next, drill two holes in each hinge (I recommend stepping up the sizes of drill bits one by one).

<img alt="Prepare tools needed" src="/Images/2.%20IKEA%20Lack%20tables/Prepare_tools_needed.jpg" align="top" width="375">

<img alt="Cutting out the 10x25mm spacers" src="/Images/2.%20IKEA%20Lack%20tables/Cutting_spacers.jpg" align="top" width="275"><img alt="Finished hinges with spacers attached and holes drilled" src="/Images/2.%20IKEA%20Lack%20tables/Finished_hinges.jpg" align="top" width="200">

The finished hinges and door knobs can now be attached to the main door panels. First, mark out where the hinges and door knob are going to go on one panel. Space the hinges equidistant from each other on one side of the panel (the side of the hinge without the spacer should be on the panel, and the side with the spacer should be off the panel). As before, check that the hinges are placed far enough away from the edge of the panel so the edge does not interfere with the movement of the hinge. The knob can be placed halfway up the panel on the other side of the panel and around x cm in. Using the square to make sure the hinges and knob are aligned, apply acrylic cement as before. Repeat for the second panel.

<img alt="Mark out where the hinges and knob should go on an acrylic panel" src="/Images/2.%20IKEA%20Lack%20tables/Marking_acrylic_panel.jpg" align="top" width="375">

<img alt="Align the hinges on an acrylic panel" src="/Images/2.%20IKEA%20Lack%20tables/Align_hinges.jpg" align="top" width="350"><img alt="Finished acrylic panel" src="/Images/2.%20IKEA%20Lack%20tables/Finished_panel.jpg" align="top" width="200">

Before attaching the acrylic panels to the IKEA Lack table, the seal strip should be applied. Peel back the plastic layer on the back of the strip to expose the adhesive. Apply the seal strip as shown in the picture below. (Cut the strip with a box-cutter or scissors.)

<img alt="Seal strip installed" src="/Images/2.%20IKEA%20Lack%20tables/Seal_strip_installed.jpg" align="top" width="250">

Holding a finished acrylic panel up to the front (or back) of the IKEA Lack table, mark out where the holes for the screws should go. Next, drill pilot holes. While holding the panel up, screw the screws in most of the way. (You may want to add a foam spacer to adjust the tension on the hinges from the seal strip.) Fine tune the depth the screws are screwed in to maximize the seal and minimize stress on the acrylic panel. Repeat for the second panel.

<img alt="Drilling the holes for an acrylic panel" src="/Images/2.%20IKEA%20Lack%20tables/Drill_holes_panel.jpg" align="top" width="60"><img alt="Installed acrylic panel" src="/Images/2.%20IKEA%20Lack%20tables/Installed_panel.jpg" align="top" width="300">

Now it is time to attach the toggle clamps and panel clamps to secure the acrylic panels. First print out the parts for the Acrylic Toggle Clamps and Acrylic Panel Clamps as directed in Printed Parts.pdf. The toggle clamps must be assembled before they are installed. Follow the steps demonstrated in the pictures to assemble the 10 total clamps. Install the toggle clamps as shown in the picture below by first marking out the locations with a pencil and the square, drilling pilot holes, and screwing in the screws (the edge of the clamp should be flush with the surface of the IKEA Lack table, but check for interference before drilling holes). The Acrylic Panel Clamps do not require assembly, but the installation is a bit trickier. Using the square and the acrylic panel and clamps for reference on the size, mark out where the panel clamps should go (see the picture below, and as before check for interference before installing). To install the set screws, drill pilot holes of 2.5mm. Now screw in the set screws. I found that the hex head on the set screw stripped immediately, so I used two nuts tightened together (as detailed in the picture below) to screw them in. See the picture below for what the finished installation should look like.

<img alt="Layout for the Acrylic Panel Clamps" src="/Images/2.%20IKEA%20Lack%20tables/M3_set_screw_layout.JPG" align="top" width="60"><img alt="Installing set screw" src="/Images/2.%20IKEA%20Lack%20tables/Install_set_screw_panel_clamp.JPG" align="top" width="60"><img alt="Installed set screw with panel clamp" src="/Images/2.%20IKEA%20Lack%20tables/Panel_clamp_installed.JPG" align="top" width="60"><img alt="Finished" src="/Images/2.%20IKEA%20Lack%20tables/Acrylic_panel_clamps_done.JPG" align="top" width="60">

Attach Printer to top table

<h4> Step 3: Print Bed </h4>

Create

Install parts

Bed supporting plate

<h4> Step 4: Z axis </h4>

Print parts

Add 10mm rods

Bearings to bed supporting plate

Z leadscrew and nut + parts

Endstop and adjustable screw (cover software routine)

<h4> Step 5: Y axis </h4>

Print parts

Motor Mount

Idler Bearing Mount

12mm Rod Clamp type 1 and 2

y endstop

motors

<h4> Step 6: X axis </h4>

Print parts

aluminum rods and bushings

Hotend carriage

XY Joiner

GT2 Belts

Hotend install and fan install

<h3> Wiring </h3>
Line up the pins of the RAMPS 1.4 board with the sockets on the Arduino Mega (after the Arduino Mega is fully screwed down onto the IKEA Lack table). Press the RAMPS 1.4 board down until the pins are fully into the Arduino Mega. Next, solder wires to the switch as shown below in the pictures. Follow the wiring diagram below (this diagram is in SVG format and can therefore be scaled) (Note: some wires/cables will need to be extended. You can splice four wires into multi-core cable listed in the BOM instead of using seperate pieces of wire (see pictures below for an example)). Add 3D-printed wire clamps (see the STL files folder and Printed Parts.pdf), zip-ties and labels as necessary. Below the wiring diagram are some pictures of the wiring.

<h4> Wiring Diagram </h4>
<img alt="Wiring schematic SVG" src="/Images/Wiring/Wiring.svg">

<h4> Switch wiring </h4>

<img alt="Switch wiring back" src="/Images/Wiring/Switch_Wiring.jpg" align="top" width="200"><img alt="Switch wiring front JPG" src="/Images/Wiring/Switch_Finished.jpg" align="top" width="200">

<h4> Multi-core Cable spliced to Endstop wires </h4>

<img alt="Splicing wires to cable" src="/Images/Wiring/Splice_wires.jpg" align="top" width="350"><img alt="Spliced wires to cable" src="/Images/Wiring/Spliced_wires.jpg" align="top" width="350">

<h4> Starting Wiring </h4>

<img alt="Starting wiring" src="/Images/Wiring/Starting_Wiring.JPG">

<h4> Finished Wiring </h4>

<img alt="Finished wiring" src="/Images/Wiring/Finished_Wiring.JPG">


<h3> Firmware </h3>
Marlin firmware is used for this 3D printer(see <a href="https://marlinfw.org">marlinfw.org</a>). The Marlin Configuration folder stores the changed configuration files in Marlin. See MODIFICATIONS.txt for how to install the configuration files and upload Marlin to the Arduino Mega.

<h3> Software </h3>
I recommend using Ultimaker Cura for slicing. Cura can be installed from <a href="https://www.ultimaker.com/en/products/ultimaker-cura-software">the Ultimaker website</a>. A sample profile is the main directory. Follow the instructions detailed on <a href="https://www.ultimaker.com/en/resources/20441-manage-profiles">this page on the Ultimaker website</a> to load the profile. To perform one of the test prints: load the test cube from the STL files folder into Cura, slice the cube, and put the GCODE on an SD card. Insert the SD card into the 3D printers LCD sreen controller board and select the file from the menu.

<h3> License and Credits </h3>
All work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license, except for the Marlin configuration files. Note: the Marlin configuration files (Configuration.h, Configuration_adv.h, pins_RAMPS.h, ultralcd.cpp) are licensed differently because they are from Marlin (see <a href="https://marlinfw.org">marlinfw.org</a>). For those files, see the LICENSE in the Marlin Configuration directory. This design was inspired by Tech2C's Hypercube, but all of the parts were designed by me from scratch.
