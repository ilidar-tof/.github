<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="./ilidar-tof-git-pc-dark.svg">
  <source
    media="(prefers-color-scheme: light)"
    srcset="./ilidar-tof-git-pc-light.svg">
  <img
    src="./ilidar-tof-git-pc-light.svg"
    alt="HYBO iLidar ToF product lineup"
    width="800">
</picture>

# iLidar-ToF

iLidar-ToF is a family of compact 3D solid-state
LiDAR sensors from HYBO. With no moving parts and an efficient optical design,
iLidar sensors provide a practical depth-sensing platform for robotics,
industrial safety, access monitoring, and other spatial-awareness
applications.

This GitHub organization provides the official APIs, examples, and ROS drivers
for the **iTFS** and **iTFS-LITE** product families.

## Software Packages

| Repository | iTFS | iTFS-LITE | Function |
|---:|:---:|:---:|:---|
| [`iViewer V2`](https://github.com/ilidar-tof/iviewer-v2/releases/latest) | ✓ | ✓ | Sensor monitoring and visualization<br><small>Support: Windows 10/11 · Ubuntu 20.04 - 24.04</small> |
| [`ilidar-api`](https://github.com/ilidar-tof/ilidar-api) | ✓ | ✓ | C++ and Python APIs and examples<br><small>Support: C++17 · Python 3 · Windows 10/11 · Ubuntu 18.04 - 24.04</small> |
| [`ilidar-ros2`](https://github.com/ilidar-tof/ilidar-ros2) | ✓ | ✓ | ROS 2 drivers and RViz2 packages<br><small>Support: Foxy · Humble · Jazzy · Lyrical<sup>*</sup></small> |
| [`ilidar-ros`](https://github.com/ilidar-tof/ilidar-ros) | ✓ | ✓ | ROS 1 drivers and RViz packages<br><small>Support: Kinetic · Melodic · Noetic</small> |
| [`ilidar-tool-py`](https://github.com/ilidar-tof/ilidar-tool-py) | ✓ | ✓ | Python sensor configuration tools<br><small>Support: Python 3</small> |
| [`lite-fw`](https://github.com/ilidar-tof/lite-fw) | · | ✓ | Python iTFS-LITE firmware updater<br><small>Support: Python 3</small> |

<small><sup>*</sup> Planned for Ubuntu 26.04 LTS.</small>

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
