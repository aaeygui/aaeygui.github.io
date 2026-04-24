---
layout: default
title: Testing
permalink: /testing/
---

# Testing

The following is a record of the various tests that were preformed on the R/C car during the spring quarter of the senior CapStone Project. 

The testing done to the car was to judge the competency pf the car based on requirements set by the student during Fall quarter. 

Testing done to the R/C car was a speed test that utilizes a large open space, about 100 feet, and a stop watch. This test is done to confirm the top speed of the car, the maximum operational time, as well as acceleration of the car. There was a destructive crash test that tests for the deformation of the bumper and chassis.

### Impact Testing 

The first test that was done was the head-on impact testing. This test was done to confirm calculations done to the amount of deflection the bumper and chassis will deflection when impacting a wall at 15 mph. 

This test was done first in the event of lossing control during the sprint race in the Baja competition. This ended up being a mistake to do first at impacting the car cause more damage to the rest of the car than expected. One of the components that was damaged was the steering servo, the steering gear sheared and was not repairable. This problem was mitigated by have a second servo on hand that could be swapped into the system. This servo was significantly worse than the primary servo and it did impact the time on the Slalom race.

The calculated delfection was .6 inches from normal. This was calculationed using the Euler's critial buckling equation for a rectangular column. The test was supposed to be run a total of five times to get accurate data. This test was run 2 to when the bumper broke beyond repair. 

After analyzing the testing image of the only successful test, as seen in Figure 1, the bumper appears to have deflected .632 inches, this is outside of the allowable deflection set by requirement 1d.2, The chassis must deflect less than .6 inches at a 15 mph impact.

It was suspected that the reason that it was outside of the requirement scope is due to the contruction. The bumpers design was altered to better absorb energy upon impact.

<figure style="flex:1 1 50%;margin:auto;">
  <img src="{{ '/assets/Testing-Image.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:50%;height:50%;" class="zoomable">
    <figcaption>Figure 1: Impact testing image.</figcaption>
  </figure>

This image shows the state of the RC car after the only successful impact.