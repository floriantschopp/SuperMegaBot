---
layout: default
title: Additional Software
nav_order: 10
has_children: true
---

# Additional software
{:.no_toc}
This page introduces some additional software that can be used to simplify or help using the SuperMegaBot.

* Table of contents
{:toc}

## Mission Planner
A mission plan defines the logic how and when different missions are executed. The mission plan is implemented as a smach state machine. Each mission has its own mission data, containing relevant information for the mission (e.g. its waypoints). For more explanation please refer to the [MissionPlanner](https://github.com/ETHZ-RobotX/smb_mission_planner).


## NodeManager
When running the full software stack on the robot, a lot of ROS nodes are run simultaneously. [NodeManager](HowToUseNodeManager.md) can help in launching and monitoring the current status of each node.

## Mapping