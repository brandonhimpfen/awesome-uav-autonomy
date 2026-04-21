# Awesome UAV Autonomy [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![DOI](https://zenodo.org/badge/1113484077.svg)](https://doi.org/10.5281/zenodo.19682086)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of frameworks, algorithms, research, simulators, datasets, flight controllers, onboard software, path-planning tools, and autonomy stacks for **UAV autonomy**, including perception, planning, SLAM, control, swarm intelligence, and safety systems.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Resources](#official-resources)
- [Autonomy Frameworks & Stacks](#autonomy-frameworks--stacks)
- [Perception, Mapping & SLAM](#perception-mapping--slam)
- [Path Planning & Navigation](#path-planning--navigation)
- [Control Systems](#control-systems)
- [Simulation & Testing Environments](#simulation--testing-environments)
- [Communication, Middleware & Ground Systems](#communication-middleware--ground-systems)
- [Swarm Intelligence & Multi-Agent Systems](#swarm-intelligence--multi-agent-systems)
- [Safety, Collision Avoidance & Redundancy](#safety-collision-avoidance--redundancy)
- [Datasets](#datasets)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [PX4 Autopilot](https://px4.io/) – Leading open-source flight stack for autonomous drones.
- [ArduPilot](https://ardupilot.org/) – Robust, feature-rich open-source autopilot.
- [MAVLink Protocol](https://mavlink.io/) – Lightweight messaging protocol for UAV systems.
- [ROS & ROS 2](https://www.ros.org/) – Robotics middleware widely used in autonomy research.

## Autonomy Frameworks & Stacks

- [PX4 + ROS Integration](https://docs.px4.io/main/en/ros/) – Perception, planning, and offboard control.
- [ArduPilot Companion Computers](https://ardupilot.org/dev/docs/companion-computers.html)
- [AirSim Autonomy Stack](https://github.com/microsoft/AirSim) – Interfaces for perception & planning.
- [Auterion Skynode](https://auterion.com/) – Enterprise PX4-based autonomy platform.
- [DroneCore](https://github.com/Dronecode/DroneCore) – SDK for PX4-based drones.
- [OpenPilot Research Frameworks](https://github.com/openpilot) – (Various autonomy components)

## Perception, Mapping & SLAM

- [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) – Visual, stereo, and inertial SLAM.
- [LIO-SAM](https://github.com/TixiaoShan/LIO-SAM) – LiDAR-Inertial Odometry + mapping.
- [RTAB-Map](https://github.com/introlab/rtabmap) – Real-time visual SLAM & mapping.
- [OKVIS](https://github.com/ethz-asl/okvis) – Keyframe-based visual-inertial odometry.
- [VINS-Mono / VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) – Robust VIO for drones.
- [ETH Zurich ASL Datasets & Tools](https://github.com/ethz-asl) – Extensive UAV autonomy research tools.

## Path Planning & Navigation

- [RRT*, RRT, RRT-Connect Implementations](https://github.com/ompl/ompl) – Sampling-based planners.
- [OMPL (Open Motion Planning Library)](https://ompl.kavrakilab.org/) – Widely used motion-planning toolkit.
- [PX4 Mission Planning Tools](https://docs.px4.io/main/en/flying/missions.html)
- [MAVROS Offboard Control](https://github.com/mavlink/mavros)
- [MoveIt (ROS)](https://moveit.ros.org/) – Motion planning for robotics.
- [TEB Local Planner](https://github.com/rst-tu-dortmund/teb_local_planner) – Efficient local trajectory optimization.

## Control Systems

- [PX4 Control Architecture](https://docs.px4.io/main/en/flight_stack/controller_diagrams.html)
- [University Flight Control Open-Source Repos](https://github.com/ethz-asl) – Nonlinear control, MPC, LQR demos.
- [MPC for Drones](https://github.com/ETHZ-RobotDynamics/MPC) – Drone model predictive control.
- [UAV PID Tuning Tools](https://ardupilot.org/copter/docs/pid-tuning.html)
- [Crazyswarm](https://github.com/USC-ACTLab/crazyswarm) – Control framework for Crazyflie drones.

## Simulation & Testing Environments

- [Gazebo](https://gazebosim.org/) – Classic robotics simulator with UAV plugins.
- [AirSim](https://github.com/microsoft/AirSim) – Photorealistic simulator for ML, control, and autonomy training.
- [Ignition Gazebo (Fortress, Garden)](https://github.com/gazebosim/gz-sim)
- [PX4 SITL (Software-in-the-Loop)](https://docs.px4.io/main/en/simulation/)
- [ArduPilot SITL](https://ardupilot.org/dev/docs/sitl-simulator-software-in-the-loop.html)
- [RotorS Simulator](https://github.com/ethz-asl/rotors_simulator) – Research-grade UAV simulator for ROS.
- [Flightmare](https://github.com/uzh-rpg/flightmare) – GPU-accelerated physics & RL training.

## Communication, Middleware & Ground Systems

- [MAVSDK](https://github.com/mavlink/MAVSDK) – MAVLink SDK for autonomous missions.
- [MAVROS](https://github.com/mavlink/mavros) – ROS bridge for MAVLink.
- [QGroundControl](https://github.com/mavlink/qgroundcontrol) – Mission planning, control, telemetry.
- [Mission Planner (ArduPilot)](https://github.com/ArduPilot/MissionPlanner)

## Swarm Intelligence & Multi-Agent Systems

- [Crazyswarm](https://github.com/USC-ACTLab/crazyswarm) – Multi-drone research platform.
- [SwarmLab](https://github.com/SwarmLab) – Research group tools and models.
- [ROS Multi-UAV Systems](https://github.com/ethz-asl/mav_multiagent_ws)
- [OpenSwarm Projects](https://github.com/OpenSwarm)
- [Multi-Agent Reinforcement Learning (MARL) Frameworks](https://github.com/openai/maddpg)

## Safety, Collision Avoidance & Redundancy

- [PX4 Collision Prevention](https://docs.px4.io/main/en/computer_vision/collision_prevention.html)
- [ArduPilot Rangefinder + Avoidance APIs](https://ardupilot.org/copter/docs/ac2_simple_avoidance.html)
- [VOXL Avoidance](https://modalai.com/pages/voxl) – Qualcomm-based perception/avoidance.
- [ROS Costmap_2D](https://wiki.ros.org/costmap_2d) – Local obstacle maps for avoidance.
- [Safety Pilot / Failsafe Modules](https://docs.px4.io/main/en/config/safety.html)

## Datasets

- [UZH FPV Dataset](http://rpg.ifi.uzh.ch/uzh_fpv.html) – High-speed drone racing dataset.
- [ETH Zurich MAV Datasets](https://projects.asl.ethz.ch/datasets/doku.php) – Widely used autonomy benchmarks.
- [Microsoft AirSim Datasets](https://github.com/microsoft/AirSim) – Synthetic + real flight data.
- [EuroC MAV Benchmark Suite](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)

## Learning Resources

### Tutorials & Guides
- [PX4 Autonomy Tutorials](https://docs.px4.io/)
- [ArduPilot Dev Guides](https://ardupilot.org/dev/)
- [ROS Autonomous Drone Tutorials](https://wiki.ros.org/ROS/Tutorials)
- [AirSim Autonomy Course](https://microsoft.github.io/AirSim/)

### Courses
- ETH Zürich – UAV Control & Autonomy  
- University of Zurich – Vision-based Navigation  
- MIT – UAV Systems Engineering  

### Research Papers
- UAV SLAM, MPC, Vision-based Navigation, Swarm Coordination, RL for Drone Autonomy (commonly found via arXiv Robotics).

## Related Awesome Lists

- [Awesome UAV & Drone AI](https://github.com/awesomelistsio/awesome-uav-drone-ai)
- [Awesome Robotics](https://github.com/awesomelistsio/awesome-robotics)
- [Awesome Computer Vision](https://github.com/awesomelistsio/awesome-computer-vision)
- [Awesome Reinforcement Learning](https://github.com/awesomelistsio/awesome-reinforcement-learning)
- [Awesome Autonomous Systems](https://github.com/awesomelistsio/awesome-autonomous-systems)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
