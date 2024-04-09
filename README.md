<!--
SPDX-FileCopyrightText: 2024, Yaskawa America, Inc.
SPDX-FileCopyrightText: 2024, Delft University of Technology

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# micro_ros_motoplus

Customised micro-ROS library for Yaskawa Motoman MotoPlus, used by [MotoROS2](https://github.com/yaskawa-global/motoros2).

## Downloading micro_ros_motoplus

Please find the latest (and historical) releases of `micro_ros_motoplus` on the [Releases](https://github.com/yaskawa-global/micro_ros_motoplus/releases) page.

## Building micro_ros_motoplus

Currently this project can't be built without access to Yaskawa internal tools and infrastructure.

The files in this repository are made available to users of MotoROS2 to more easily discover which specific packages are part of a certain `micro_ros_motoplus` release.

## Contacting the maintainers

Please open a thread on the [Discussion board](https://github.com/yaskawa-global/micro_ros_motoplus/discussions/categories/q-a) to request addition of or changes to interface packages included (messages, services and/or action definitions) or to discuss other aspects of `micro_ros_motoplus`.

Please only use [Issues](https://github.com/yaskawa-global/micro_ros_motoplus/issues) to report *problems* with `micro_ros_motoplus` or any of the libraries we [release](https://github.com/yaskawa-global/micro_ros_motoplus/releases) here.

## Versioning

`micro_ros_motoplus` version strings have the following structure:

```
<controller>-<ros_codename>-<YYYYMMDD>
```

where `<controller>` is the Yaskawa Motoman controller platform supported by a release, `<ros_codename>` encodes the ROS 2 version and `<YYYYMMDD>` denotes the date at which the set of included packages was synchronised with upstream releases (ie: micro-ROS itself and/or the main ROS 2 project).

This last element is loosely based on [calendar versioning](https://calver.org).

All version strings may be followed by an optional suffix, providing additional information to discriminate between releases (such as optimisation levels, debug options or supported features).

### Examples

Some examples of version strings:

- `dx200-humble-20221102`
- `yrc1000-foxy-20221102-dbg`
- `yrc1000u-galactic-20221102-alpha45`
