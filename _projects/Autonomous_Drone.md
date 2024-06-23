---
layout: page
title: Autonomous Drone for Nuclear Power Plant Inspection
description: Autonomous Drone system designed for our final Capstone Project
img: assets/img/Autonomous_Drone/CapstoneDrone.PNG
importance: 4
category: robotics
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Autonomous_Drone/Drone_Flight.gif" title="The Drone autonomously flying to different waypoints" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Drone autonomously flying to different waypoints
</div>


For our final year capstone project, my team and I build and programmed an autonomous drone system for a Nuclear Power Plant inspection task. The drone was flown in a drone lab at the University in a room full of obstacles which were not known apriori. 

For this project, our team of 4 split ourselves such that I worked on the path planning, obstacle avoidance, and was in charge of the testing tuning of our drone and software parameters. I also was responsible of the adminstrative aspect.  

The project was split up into 5 deliverables, starting from autonomous takeoff and landing, hovering on the spot, following a simple trajectory with no obstacles and finally autonomously navigating the environment to reach waypoints.

We used a realsense T265 for our visual odometry, a pixhawk flight controller and MAVROS, a library that enables us to receive telemetry from the pixhawk onto our ROS network. We used an onboard Jetson Nano for our computation. A lidar sensor was also added for altitude estimation. A color camera was used to perform obstacle detection.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Autonomous_Drone/CapstoneDrone.PNG" title="A diagram of our drone" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An annotated diagram of our drone.
</div>

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Autonomous_Drone/Obstacle_Avoid.PNG" title="The Drone's Obstacle Avoidance camera in action" class="img-fluid rounded z-depth-1" %}
        
        {% include figure.liquid loading="eager" path="assets/img/Autonomous_Drone/Trajectory.PNG" title="The Drone's Flight trajectory in the obstacle-free flight" class="img-fluid rounded z-depth-1" %}

        {% include figure.liquid loading="eager" path="assets/img/Autonomous_Drone/Drone_Camera.PNG" title="Custom Camera mount" class="img-fluid rounded z-depth-1" %}

    </div>
   
</div>

<div class="caption">
   Some pictures of the view of the drone's obstacle avoidance system in action, the obstacle-free flight trajectory and the custom camera mount modification to angle the camera to perform obstacle avoidance.
</div>







This project was done as the lead of the Robotics for Space Exploration's (RSX) Science sub-team. The goal is to make a system to autonomously excavate and contain soil samples for further analysis, and then analyze the soil for signs of life present in the environment. This was done as a part of the CIRC 2023 Competition in Drumheller, AB, Canada.

The Team comprised of myself and 6 other junior members and involved collaborating with the all the other sub teams at RSX. Beyond this module, the Science subteam designs scientific experiments to test for traces of signs of life, designs the mechanical and electrical systems used and implements the software required to autonomously complete the tasks.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RSX_Rover/Full_Rover.png" title="Full Rover in the Badlands" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Picture of the Full Rover with the Science Module in place, tested in the Alberta Badlands in 2023.
</div>

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RSX_Rover/Drill_On_Grass.png" title="Sample Retrieval Module being tested on the grass" class="img-fluid rounded z-depth-1" %}
        
        {% include figure.liquid loading="eager" path="assets/img/RSX_Rover/Full_Rover2.jpg" title="Another Angle of the rover in Alberta" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RSX_Rover/Drill_On_Rover1.png" title="Closeup of the  Sample Retrieval Module's drill in Alberta" class="img-fluid rounded z-depth-1" %}
   
        {% include figure.liquid loading="eager" path="assets/img/RSX_Rover/Rover_Assembly_In_Progress.jpg" title="Rover Assembly in Progress" class="img-fluid rounded z-depth-1" %}
    </div>
   
</div>

<div class="caption">
    Pictures of the Sample Retrieval Module being tested on grass and closeups of the drill in Alberta.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RSX_Rover/Drill_On_Table.png" title="Partially Assembled Sample Retrieval Module" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sideways profile of the Sample Retrieval Module after being partially assembled.
</div>
