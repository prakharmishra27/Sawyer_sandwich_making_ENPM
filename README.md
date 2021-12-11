# Sawyer_sandwich_making_ENPM
enpm 662

Download the sawyer dependencies and setup the workstation: https://sdk.rethinkrobotics.com/intera/Workstation_Setup

Follow the above instruction and set the workstation, check for ./intera.sh sim command for checking the server

If its working, now unzip the project 2 folder

Run the following command in one termainal (after running ./intera.sh sim) roslaunch sawyer_gazebo sawyer_world.launch electric_gripper:=true

Now Run the second command in other terminal (after running ./intera.sh sim) rosrun picknplace ik_pick_and_place_demo.py

Now the whole system should pop up and successfully start doing the pick and place of sandwiches.
