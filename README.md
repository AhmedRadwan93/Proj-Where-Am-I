# Project -Where-Am-I
## The project folder contains the following:
- ROS Package containing 
   - AMCL files.
   - teleop files.
   - Robot files
   - World and map files
- Screenshot(s) of localized robot in RViz

Notes: 
- Simulation setup have the appropriate number of landmarks or geometric features to perform localization.
- Launch file contains all required nodes:
       - Map Server node map_server
       - AMCL node amcl
       - Move Base node move_base
