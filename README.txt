# DP-Lick-Detector
Distribution Package for Dual Port Lick Detector
This distribution package includes files relevant to building the lick detector, described in 

Williams et. al, 2018 "A Novel Device For Real-time Measurement And Manipulation Of Licking Behavior In Head-fixed Mice"
https://doi.org/10.1152/jn.00500.2018

For more detailed instructions on how to construct the detector, refer to the appendix of the above publication.

Basic instructions:
1. Use the STL file 'DividedDualPort.STL' in the CAD folder, to 3d print the base.
2. Solder the connections to the sensors. Use 'SensorToBoard.pdf' in Circuit folder for reference.
3. Glue the sensors to the 3D printed base. Refer to 'DividedDualPort.PNG' in CAD folder for recommended glue areas.
4. Make the circuit board. Refer to 'circuit schematic.pdf' in Circuit folder for details on what the circuit should look like.
5. Solder the connections from sensor to board. Refer to 'SensorToBoard.pdf' and 'Circuit.jpg' for details.
6. Solder the connections to power and BNC. Refer to 'power+bnc leads.png' and 'Circuit.jpg' for details.

For an overall look at the final product, refer to the images in the Example folder.

These files are provided free of charge and free to reuse.
Original author of these files is Brice Williams, Haider Lab, Georgia Institute of Technology


Directory list:

CAD
--detector2018.SLDASM
--DividedDualPort.PNG
--DividedDualPort.SLDPRT
--DividedDualPort.STL
--FeedingTube.SLDPRT
--Rod.SLDPRT
--Sensor8mm.SLDPRT
Circuit
--Data Sheets
----ds14001.pdf **Data sheet from Diodes incorporated, for ESIA diode
----en-ee_sx3070_4070.pdf **Data sheet from Omron, for photosensor
----MC78L00A-D-94916.pdf **Data sheet from Semiconductor Components Industries, LLC, for voltage regulator
--circuit schematic.pdf
--circuit schematic.png
--Circuit.jpg
--DiagramModular.pdf
--DiagramModular.png
--OmronSensor.jpg
--power+bnc leads.png
--SensorToBoard.pdf
--SensorToBoard.png
Example
--IMG_1316.jpg
--IMG_1522.jpg
--IMG_1524.jpg

