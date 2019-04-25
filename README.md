# franka_ssi

## Launch the robot in gazebo along with moveit using effort controller 
  `roslaunch franka_gazebo franka_moveit.launch`

  This will open the rviz with moveit plugin and gazebo. If you are not able to see the robot in rviz, try adding the Robot Model and change fixed frame from map to world.

## Testing jog motion
`roslaunch jog_launch franka.launch`

This will open another rviz which is having joint mode and cartesian mode to move the robot. Try moving robot with different modes like translation x,y,z and rotation x,y,z.

## Testing Xbox
`roslaunch jog_controller joypad.launch`

First we to identify the device. Below link to follow (I will do it in TeamViewer)
https://github.com/tork-a/jog_control/blob/master/jog_controller/README.md
