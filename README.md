```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/PickNikRobotics/studio_packages/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/PickNikRobotics_studio_packages.list
echo "yaml https://raw.githubusercontent.com/PickNikRobotics/studio_packages/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-PickNikRobotics_studio_packages.list
```
