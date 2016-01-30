# tailwindflyer / Pi2D2

Pi2D2 is a Dynon D2 knockoff based on the Raspberry Pi with AHRS data from the Stratux project. 
Please refer back to Pi2D2 and Stratux for full details of these impressive projects.  

This fork is intended to experiment with the following changes to the baseline Pi2D2 project to meet my requirements for an experimental VFR flight display and data logging system for flight testing of experimental amateur build aircraft:

1.  Addition of pitot-static sensed airspeed (to replace GPS groundspeed display) using a differential pressure sensor.
2.  Deselection of heading and altitude bugs - not required.
3.  Deselection of the CDI and glideslope capability along with associated VOR/ILS data - not required.
4.  Addition of AoA display based on differential pressure from a 2 port pitot tube.  
5.  Data logging of flight parameters, AHRS and GPS data for post flight review.  

