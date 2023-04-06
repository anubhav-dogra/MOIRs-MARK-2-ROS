# MOIRs-MARK-2-ROS

This package compliments the tools in [MOIRs-MARK-2-URDF](https://github.com/anubhav-dogra/MOIRs-MARK-2-URDF) to run the models of any customized manipulator configurations (`n'-DoF), even with non-parallel and non-parallel jointed configurations, using the unconventional modular library in ROS Simulations such as Moveit and can send trajectories through [Kinova API](https://github.com/Kinovarobotics/kinova-ros). 

You need to have Kinova API installed in your PC if you have kinova hardware.
You would also need to generate as moveit configuration package for the developed robot configuration and link it with the kinova API similar to moveit packages available for Kinova. 
For any further info, you may contact us.

If you are using this work in any form, Please cite this article:

```
@article{DOGRAUnified2022,
title = {Unified modeling of unconventional modular and reconfigurable manipulation system},
journal = {Robotics and Computer-Integrated Manufacturing},
volume = {78},
pages = {102385},
year = {2022},
issn = {0736-5845},
doi = {https://doi.org/10.1016/j.rcim.2022.102385},
url = {https://www.sciencedirect.com/science/article/pii/S0736584522000722},
author = {Anubhav Dogra and Sakshay Mahna and Srikant Sekhar Padhee and Ekta Singla},
keywords = {Modular and reconfigurable design, Robot Operating System, Kinematics and dynamic modeling, Modular library, Reconfigurable software architecture}}
```
