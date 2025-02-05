## Instructions

1. Check the params.yaml to change ros params.
2. Demo videos are provided in ```videos/```
3. Report about algorithms and parameter description are provided in ```report/```
4. final race logs are provided in ```final_race_log/```
4. Make sure you have the ```f110-skeletons-spring2020``` race simulator also compiled in the catkin_ws


## Run after compiling workspace
* For Pure wall following
``  $ roslaunch virtualfastkeyboardfurious_final_race pure_wall_following.launch 
``

* For final race 
``  $ roslaunch virtualfastkeyboardfurious_final_race final_race_launch.launch 
``

* For Error Tracking 
``  $ rosrun virtualfastkeyboardfurious_final_race error_analysis.py 
``


* For generating RRT based waypoints go virtualfastkeyboardfurious_final_race/scripts/
``  $ python rrt_race.py
``

  ![alt text](./images/Wall_Following_waypnt.png)
