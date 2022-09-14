baxter_simulator
================

Rethink Robotics Baxter Simulator refactored for Gazebo11, ROS Noetic and Python3



Installation Instructions
-------------------------
The detailed installation and setup instructions are available in the `wiki of this repository <https://github.com/maymohan/baxter_simulator/wiki/Installation-Instructions>`__.


Other Baxter Repository Forks for ROS Noetic
--------------------------------------------


+------------------+-----------------------------------------------------+
| baxter           | https://github.com/maymohan/baxter                  |
+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/maymohan/baxter_interface        |
+------------------+-----------------------------------------------------+
| baxter_tools     | https://github.com/maymohan/baxter_tools            |
+------------------+-----------------------------------------------------+
| baxter_examples  | https://github.com/maymohan/baxter_examples         |
+------------------+-----------------------------------------------------+
| baxter_common    | https://github.com/maymohan/baxter_common           |
+------------------+-----------------------------------------------------+
| baxter_pykdl     | https://github.com/maymohan/baxter_pykdl            |
+------------------+-----------------------------------------------------+

Code & Tickets
--------------

+-----------------+----------------------------------------------------------------+
| Documentation   | http://sdk.rethinkrobotics.com/wiki                            |
+-----------------+----------------------------------------------------------------+
| Issues          | https://github.com/RethinkRobotics/baxter_simulator/issues     |
+-----------------+----------------------------------------------------------------+
| Contributions   | http://sdk.rethinkrobotics.com/wiki/Contributions              |
+-----------------+----------------------------------------------------------------+

baxter_simulator Repository Overview
------------------------------------

::

     .
     |
     +-- baxter_simulator/        baxter_simulator metapackage
     |
     +-- baxter_gazebo/           Gazebo interface for the Baxter that loads the models into simulation
     |   +-- src/
     |   +-- launch/
     |   +-- worlds/
     |
     +-- baxter_sim_controllers/  Controller plugins for Baxter
     |   +-- src/
     |   +-- include/
     |   +-- config/
     |
     +-- baxter_sim_examples/     Examples specific to Baxter in Simulation
     |   +-- scripts/             (use baxter_examples for examples that will work both in
     |   +-- include/              simulation AND the real Baxter robot)
     |   +-- launch/
     |   +-- models/
     |
     +-- baxter_sim_hardware/     This emulates the hardware interfaces of Baxter 
     |   +-- src/
     |   +-- include/
     |   +-- config/
     |   +-- launch/
     |
     +-- baxter_sim_io/           QT based navigator plugins for baxter
     |   +-- src/
     |   +-- include/
     |   +-- ui/
     |
     +-- baxter_sim_kinematics/     Implementation of IK, FK and gravity compensation for baxter 
     |   +-- src/
     |   +-- include/
     |   +-- launch/

