# CMP9767M
Steps to launch simulation:
1) Run command roslaunch bacchus_gazebo vineyard_demo.launch with additional parameters as launch_move_base:=false and world_name:=<WORLD_NAME> (f.e. vineyard_small). Optionally add gui:=false if world is too resource heavy.
2) Source the local package from it's directory using the command source devel/setup.bash
3) Run roslaunch uol_cmp9767m_tutorial move_base.launch
4) Run roslaunch uol_cmp9767m_tutorial topo_nav.launch
5) Select the topo_nav.cfg from the Rviz config menu.
