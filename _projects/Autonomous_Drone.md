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

