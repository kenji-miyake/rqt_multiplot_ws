# rqt_multiplot_ws

Workspace for rqt_multiplot

## Prerequisites

- ROS1 Melodic or Noetic

## Usage

```sh
# Clone repositories
git clone git@github.com:kenji-miyake/rqt_multiplot_ws.git
cd rqt_multiplot_ws
mkdir src
vcs import src < workspace.repos

# Build workspace
colcon build --cmake-args -DCMAKE_BUILD_TYPE=Release

# For workspace overlay
echo "source ~/rqt_multiplot_ws/install/setup.bash" >> ~/.bashrc
source ~/.bashrc

# Build your workspace
cd YOUR_COLCON_WORKSPACE
colcon build --cmake-args -DCMAKE_BUILD_TYPE=Release
```
