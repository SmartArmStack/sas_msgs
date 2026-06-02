# sas_msgs

> [!TIP]
> Repository for this module: https://github.com/SmartArmStack/sas_msgs. <br/>
> More information about SmartArmStack is available in https://smartarmstack.github.io/.

## Overview

This package contains custom ROS 2 interfaces used across the SmartArmStack project.

```bash
docker run --rm murilomarinho/sas:jazzy /bin/bash -c "ros2 interface list | grep sas_msgs"
```

Outputs the following interfaces:

```bash
sas_msgs/msg/Bool
sas_msgs/msg/Float64
sas_msgs/msg/InformationFromMaster
sas_msgs/msg/InformationToMaster
sas_msgs/msg/LogDatum
sas_msgs/msg/String
sas_msgs/msg/WatchdogTrigger
```
