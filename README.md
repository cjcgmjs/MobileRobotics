# my_stdr_control
A node that controls the STDR mobile robot with open-loop commands.

## Example usage
`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
to start the simulator.  Run a simple, open-loop command sequence with:
`rosrun my_stdr_control stdr_open_loop_commander`
