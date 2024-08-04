---
layout: page
title: FAD Fluorescence Test
description: An experiment to find signs of life in a soil sample.
img: assets/img/FAD_Fluorescence/ISO_Landscape.jpg
importance: 1
category: physics
related_publications: false
---


This project was done before I was the lead of the Science Subteam at Robotics for Space Exploration's (RSX) and was perfected during my term as lead. The project's goal is to be a "first stage" non-destructive experiment by detect signs of life in a soil sample without contaminating the soil sample. The experiment was designed by me and 2 other members.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FAD_Fluorescence/FAD_Fluorescence_Diagram.png" title="System Diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Diagram Explaining how the FAD Fluorescence Experiment works.
</div>

The idea behind this experiment is to detect FAD, a molecule present in all organic life used to generate ATP, in a soil sample. Using the fact that when exposed to light around 450 nm (blue), FAD emits fluorescence at around 525 nm (green). By controlling the light in the environment, we can infer a correlation between the amount of 515 nm light to the input of 450 nm. By measuring the 515 nm light in an enclosed area where only 450 nm light is present, we can deduce that there is a high likelihood that there is FAD fluorescence, hence FAD and therefore organic life, extant or extinct.

See the above diagram for a visual representation of our experiment. 

The experiment centers around the use of a PMT (Photomultiplier Tube), which acts just like a photon counter. PMT's do not distinguish between wavelengths (at least theoretically), so we use a series of filters to isolate the wavelengths we are interested in. We use a dichroic mirror to allow wavelengths greater than 505 nm pass through, and those less than 505 reflect. To further ensure that we filter any stray beams of light emitted by our LED, we then use a bandpass mirror to filter out everything we aren't interested in. 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FAD_Fluorescence/ISO_Landscape.jpg" title="Built prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   The Completed Prototype.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FAD_Fluorescence/Top_Down.jpg" title="Built prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Top down view of the completed prototype.
</div>

The prototype worked well enough, but one issue we faced is to ensure that the box had to be fully sealed off from all external light, which was somewhat difficult to do perfectly as the box needed to be opened to insert the samples. In addition to this, the test tubes used to hold the samples complicated things a bit as they reflected the blue light and scattered it around which added in a bit of error.