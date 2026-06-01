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

A seecond test was run with the change to the front bumper to allow for better impact absorption.

During this test the deflection was 0.58 incehes from normal, this value is under the allowable limit making this change a successful change.

### Acceleration Testing
The second test that was done for this project was the acceleration test. This test was done to determine if the drivetrain was able to achieve a speed of 10 mph within 10 seconds. 

This was done to determine if the car would be able to compete during the sprint section of the competition. This was a successful test, however there was a incosistancy that could be the cause of data discrepency. This test was looking at the time that the car took to reach a specific speed. 

The predicted value for this test was 7 seconds to reach the required 10 mph, however, during testing the time came out to an average of 2.48 seconds. 

This data is well under the required 10 seconds, however it is believed that the reason for the discrepency is due to the drivetrain change at the beginning of spring quarter.

<figure style="flex:1 1 50%;margin:auto;">
  <img src="{{ '/assets/Acceleration_Testing Set_Up.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:50%;height:50%;" class="zoomable">
    <figcaption>Figure 2: Acceleration testing image.</figcaption>
  </figure>

This image shows the testing set-up that was used for the acceleration test.

### Ramp Testing
The third test that was conducted for this project was the ramp test. This test was done to determine if the drivetrain was able to climb a 45-degree ramp. 

This is to confirm that the car would be able to handle jumps during the Baja competition. This test was done twice, once with the bumper attached, and once with the bumper dettached. 

The car was successfull for both test runs. the reasoning behind the test was that the test with the bumper attached looked more like that the car was pushing itself up the ramp, while the second test showed that it was actually driving up the ramp. This indicates to the principle engineer that the car did not have enough ground clearance with the bumper attached. 

This issue can be solved in a number of ways, however due to time restrictions this was not chosen. one of the ways that could have solved this was to reduce the overall size of the front platform to allow the suspension to articulate further, allowing for more ground clearance. 

<figure style="flex:1 1 50%;margin:auto;">
  <img src="{{ '/assets/Ramp_Testing_Set_up.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:50%;height:50%;" class="zoomable">
    <figcaption>Figure 3: Ramp Testing Set-up.</figcaption>
  </figure>

This image shows the testing set-up for the ramp test.

<figure style="flex:1 1 50%;margin:auto;">
  <img src="{{ '/assets/Ramp_Testing_image.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:50%;height:50%;" class="zoomable">
    <figcaption>Figure 4: Ramp Testing with Bumper.</figcaption>
  </figure>

This image shows the events of one of the five testing trials for the ramp testing, this image was taken during a trial with the bumper attached. 

### Top Speed Testing
The fourth and final test that was conducted on the RC Baja competition car, was the top speed test. This test was conducted to confirm the top speed of the car at 3 different motor powers. The car was required to achieve a top speed of 30 mph.

This test was unsuccessful as the car at 100% motor power did not reach the required RPM to hit 30 mph with four inch diameter tires. During testing, the car reached 10.0 mph for 50% motor power, 16.0 mph for 75%, and 26.6 mph for 100%. This test would have been considered successful if the 100% was within 5-10% of 30 mph.

The reason for this is most likely that there is more friction in the system that anticipated. Where exactly the friction is can be in a number of places, howver it is believed, based on observation, that the bulk of the friction is cause by a tolerance issues location on each of the rear axles that connect to the wheels. 

This could have been fixed if this test was conducted earlier in the quarter, however this would have needed the rear shock tower assembly and axle connection to undergo a redesign.

<figure style="flex:1 1 50%;margin:auto;">
  <img src="{{ '/assets/Top_Speed_Testing_Setup.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:50%;height:50%;" class="zoomable">
    <figcaption>Figure 5: Top Speed Test Set-up.</figcaption>
  </figure>

This image shows the set-up used during the top speed test.

<div style="display:flex;justify-content:center;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/VFXqHBOIg3Q" frameborder="0" allowfullscreen></iframe>
</div>
<p style="text-align:center;">Video 1: Top Speed Test 50% motor power</p>

<div style="display:flex;justify-content:center;">
  <iframe width="315" height="560" src="https://youtube.com/embed/0gx_bQQRFd4" frameborder="0" allowfullscreen></iframe>
</div>
<p style="text-align:center;">Video 2: Top Speed Test 75% Motor Power</p>

<div style="display:flex;justify-content:center;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/m89fLIEs4Nw" frameborder="0" allowfullscreen></iframe>
</div>
<p style="text-align:center;">Video 3: Top Speed Test 100% Motor Power</p>