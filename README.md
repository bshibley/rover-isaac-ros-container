To build the container image:

```
touch workspace/src/isaac_ros_common/scripts/.isaac_ros_common-config
PLATFORM=aarch64 CONFIG_DOCKER_SEARCH_DIRS=../../../../ ./workspace/src/isaac_ros_common/scripts/build_base_image.sh aarch64.ros2_humble.zed.user.rover rover_isaac_ros-aarch64 '' '' ''
```