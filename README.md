# ROS2 Common Interfaces

A set of packages which contain common interface files (.msg and .srv) used during development of package/node/rcl.

## Made for

Used in RclNet rcl2cs, which generates C# classes out of msgs and services.

## Purpose

Isolating the messages to communicate between stacks in a shared dependency allows nodes in dependent stacks to communicate without requiring dependencies upon each other.
This repository has been designed to contain the most common messages used between multiple packages to provide a shared dependency which will eliminate a problematic circular dependency.

## Sources

https://github.com/ros2/common_interfaces

https://github.com/ros2/rcl_interfaces/tree/humble

https://github.com/ros2/unique_identifier_msgs/tree/humble/
