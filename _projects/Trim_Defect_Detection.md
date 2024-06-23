---
layout: page
title: Trim Defect Detection
description: Automating Quality Control for car trim pieces
img: assets/img/Trim_Defect_Detection/Trim_Quality_Control.PNG
importance: 4
category: computer vision
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Trim_Defect_Detection/Trim_Quality_Control.PNG" title="Trim Defect Detection" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Chrome and platinum trim defect tests where our pattern is clearly visible.
</div>


This project was completed during my time at Martinrea Alfield as part of the AIV team. 

The project's goal was to autonomously detect faulty car trim pieces to speed up the production process. What makes this project more difficult than regular QA is that these trim pieces are reflective as they could have a platinum, black or chrome finish.

To solve this problem we engineered a colored pattern to place in front of the trim pieces, and then analyzed the reflections' discoloration and the reflectiveness to detect both the trim finish and it's quality, rejecting those that do not meet our parameters.


