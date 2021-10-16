baxter_simulator
==============

Rethink Robotics Baxter Simulator refactored for Gazebo11 with ROS Noetic.



Installation Instructions
--------------

- Install the following python packages:
::

     sudo apt install ros-noetic-driver-common ros-noetic-gazebo-ros-control ros-noetic-gazebo-ros-pkgs ros-noetic-ros-control ros-noetic-control-toolbox ros-noetic-realtime-tools ros-noetic-ros-controllers ros-noetic-xacro ros-noetic-tf-conversions ros-noetic-kdl-parser libyaml-cpp-dev


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



Other Baxter Repository Forks for ROS Noetic
-------------------------

+------------------+-----------------------------------------------------+
| baxter           | https://github.com/maymohan/baxter           |
+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/maymohan/baxter_interface |
+------------------+-----------------------------------------------------+
| baxter_tools     | https://github.com/maymohan/baxter_tools     |
+------------------+-----------------------------------------------------+
| baxter_examples  | https://github.com/maymohan/baxter_examples  |
+------------------+-----------------------------------------------------+
| baxter_common    | https://github.com/maymohan/baxter_common    |
+------------------+-----------------------------------------------------+

Latest Release Information
--------------------------

http://sdk.rethinkrobotics.com/wiki/Release-Changes
