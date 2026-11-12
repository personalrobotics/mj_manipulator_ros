# mj_manipulator_ros

> **Retired and archived** ([mj_manipulator#182](https://github.com/personalrobotics/mj_manipulator/issues/182)).
> This was the ROS 2 hardware bridge for [mj_manipulator](https://github.com/personalrobotics/mj_manipulator),
> which is retired too. It receives no maintenance. Its final state is tagged `v0.1.0`.
>
> | mj_manipulator_ros | Successor |
> | --- | --- |
> | `HardwareContext`, the arm and gripper clients, the state listener | ssrobot's ROS 2 runtime, [ssrobot#35](https://github.com/personalrobotics/ssrobot/issues/35), and its hardware profiles and calibration, [ssrobot#36](https://github.com/personalrobotics/ssrobot/issues/36) |
> | Trajectory conversion and execution on hardware | Guarded trajectories and planner commands on the physical robot, [ssrobot#38](https://github.com/personalrobotics/ssrobot/issues/38) |
> | Migrating `HardwareContext` | [ssrobot#40](https://github.com/personalrobotics/ssrobot/issues/40) |
> | The mock node | ssrobot's runtimes and their reference robots |

A ROS 2 bridge for mj_manipulator: `HardwareContext`, a mock node, and conversion between
mj_manipulator trajectories and ROS 2 `JointTrajectory`.
