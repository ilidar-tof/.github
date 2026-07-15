![ilidar-tof-itfs.png](https://github.com/ilidar-tof/.github/blob/main/profile/ilidar-tof-itfs.png)

# iLidar-ToF

iLidar-ToF is a family of compact 3D solid-state
LiDAR sensors from HYBO. With no moving parts and an efficient optical design,
iLidar sensors provide a practical depth-sensing platform for robotics,
industrial safety, access monitoring, and other spatial-awareness
applications.

This GitHub organization provides the official APIs, examples, and ROS drivers
for the **iTFS** and **iTFS-LITE** product families.

## Software Packages

The V2 software packages use product-specific packet handling while providing
a consistent callback and multi-device workflow.

| Repository | Environment | Description |
|:---|:---:|:---|
| [iViewer V2](https://github.com/ilidar-tof/iviewer-v2/releases/latest) | Desktop Viewer | The new version of iViewer, providing viewer functionality for both iTFS and iTFS-LITE. |
| [ilidar-api](https://github.com/ilidar-tof/ilidar-api) | C++ / Python | Receive APIs and integration examples for iTFS and iTFS-LITE. Includes Helloworld, OpenCV, PCL, and Open3D examples. |
| [ilidar-ros](https://github.com/ilidar-tof/ilidar-ros) | ROS 1 / C++ | Catkin packages for iTFS and iTFS-LITE with images, organized point clouds, TF, diagnostics, and RViz visualization. |
| [ilidar-ros2](https://github.com/ilidar-tof/ilidar-ros2) | ROS 2 / C++ | Ament/colcon packages for iTFS and iTFS-LITE with standard ROS 2 messages, multi-device support, diagnostics, TF, and RViz2 visualization. |
| [ilidar-tool-py](https://github.com/ilidar-tof/ilidar-tool-py) | Python | Sensor setup and maintenance tools for iTFS and iTFS-LITE. |

### Platform Support

| Package | Supported environment |
|:---|:---|
| `iviewer_V2` | Windows 10, 11<br>Ubuntu 20.04, 22.04, 24.04 |
| `ilidar-api` | Windows and Linux in C++17-compatible native build environments<br>(Tested on Windows 10/11 and Ubuntu 18.04–24.04)<br>Python native bindings |
| `ilidar-ros` | ROS Kinetic (Ubuntu 16.04)<br>ROS Melodic (Ubuntu 18.04)<br>ROS Noetic (Ubuntu 20.04) |
| `ilidar-ros2` | ROS 2 Foxy (Ubuntu 20.04)<br>ROS 2 Humble (Ubuntu 22.04)<br>ROS 2 Jazzy (Ubuntu 24.04) |
| `ilidar-tool-py` | Python 3 |

Support for **ROS 2 Lyrical Luth (Ubuntu 26.04 LTS)** is planned.

## Start in 3 Steps

1. **Remove the protective film** — Unpack the sensor and remove the film from
   the optical window.
2. **Connect to the host** — Connect the sensor and host to the same network.
3. **Run the viewer or examples** — Start the viewer or an API/ROS example.

## Documentation

- [iTFS user manual (English)](https://github.com/ilidar-tof/user-manual/blob/main/iTFS_MANUAL_EN.md)
- [iTFS user manual (Korean)](https://github.com/ilidar-tof/user-manual/blob/main/iTFS_MANUAL_KR.md)
- iTFS-LITE user manual (English) — *Coming soon*
- iTFS-LITE user manual (Korean) — *Coming soon*

Detailed build instructions, message and topic definitions, parameters, and
troubleshooting guidance are included in each repository.

## Contact

- Technical inquiries: Junwoo Son, CTO — [json@hybo.co](mailto:json@hybo.co)
- Business inquiries: Joe, Sales Leader — [joe@hybo.co](mailto:joe@hybo.co)

Copyright © HYBO Inc.
