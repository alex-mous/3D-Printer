<h2> New 3D Printer </h2>
New 3D Printer design and build.
The goal of this project is to design and build and improved, easy to run, budget 3D printer costing less than $750 for home users to create high quality, high speed prints with a minimum print volume of 275x275x325mm (2.475x10<sup>7</sup> mm<sup>3</sup>).
<br>
Marlin Configuration stores the changed configuration files in Marlin. See MODIFICATIONS.txt for how to install and upload them to the Arduino Mega.
<br>

<h3> BOM and Cost </h3>
See BOM.csv for a list of the parts that need to be purchased. The total cost is around $700. However, your actual cost may vary depending on shipping, tax, etc. Note: the two rolls of PLA filament quoted are an estimate of how much plastic was used. You may find that you need more filament. Also, while you may be able to find cheaper alternatives to some of these parts, please be careful when economizing on very important parts such as the hotend. Some parts may need modification to work properly.

<h3> Tools </h3>
A list of the tooling used is in Tooling.csv. Please tell me if you find you need another tool so I can add the tool to the list.

<h3> 3D Printed Parts </h3>
The STL files for the 3D printed parts are in the STL files folder. See Printed Parts.csv for the amount of each part that needs to be printed.
Note: some designs may need small modifications after printing such as enlarging holes. Please notify me if of any modifications made to parts so I can update the design.

<h3> Assembly </h3>


<h3> Electronics </h3>


<h3> Software </h3>
I recommend using Ultimaker Cura for slicing. Cura can be installed from <a href="ultimaker.com/en/products/ultimaker-cura-software">the Ultimaker website</a>. A sample profile is the main directory. Follow the instructions detailed at <a href="ultimaker.com/en/resources/20441-manage-profiles">the Ultimaker website</a> to load the profile. To perform one of the test prints: load the test cube from the STL files folder into Cura, slice the cube, and put the GCODE on an SD card. Insert the SD card into the 3D printers LCD sreen controller board and select the file from the menu.

<h3> License and Credits </h3>
All work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license, except for the Marlin configuration files. Note: the Marlin configuration files (Configuration.h, Configuration_adv.h, pins_RAMPS.h, ultralcd.cpp) are licensed differently. For those files, see the LICENSE in the Marlin Configuration directory. This design was inspired by Tech2C's Hypercube, but all of the parts were designed by me from scratch.
