# 5-DOF-Robotic-arm-design

This repository contains the final design of a **5 Degrees of Freedom (DOF)** robotic arm created using TinkerCAD. The model is inspired by real industrial manipulators and follows standard kinematic principles.

## Overview

The robotic arm simulates human-like motion using 5 distinct joints. Each joint contributes to one independent movement type, enabling complex positioning of the end-effector (gripper).

---

## Degrees of Freedom Breakdown

| Joint | Location                     | Movement Type | Description                        |
|-------|------------------------------|----------------|------------------------------------|
| 1     | Base                         | Yaw            | Rotates the entire arm horizontally |
| 2     | Lower Arm                    | Pitch          | Raises or lowers the base segment |
| 3     | Middle Arm                   | Pitch          | Extends or retracts the forearm   |
| 4     | Upper Arm (near wrist)       | Pitch          | Adjusts the angle of approach     |
| 5     | Wrist joint (before gripper) | Roll           | Rotates the gripper around its axis |

---

## Gripper (Not part of 5 DOF)

- **Function:** Opens and closes to grasp or release objects.
- **Note:** While essential for functionality, it is not counted as a DOF because it does not influence spatial positioning.

---

## Files

- `Final.png`: Final screenshot of the robotic arm
- `5 DOF .stl`: The exported 3D model of the robotic arm in STL format. You can import this file into 3D modeling tools or slicing software for 3D printing.

---

