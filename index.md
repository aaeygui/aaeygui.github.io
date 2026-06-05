---
layout: default
title: Home
---

<div style="display:flex;justify-content:center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZYedM977Cpg" frameborder="0" allowfullscreen></iframe>
</div>
<p style="text-align:center;">Video 1: Fall Presentation Video</p>

<div style="display:flex;justify-content:center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Fp49TOFtsI" frameborder="0" allowfullscreen></iframe>
</div>
<p style="text-align:center;">Video 2: Winter Presentation Video</p>

<div style="display:flex;justify-content:center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/mAf0pw3eMEU" frameborder="0" allowfullscreen></iframe>
</div>
<p style="text-align:center;">Video 3: Spring Presentation Video</p>

<p style="text-align:center;margin:1rem 0;">
  <a href="{{ '/MET489_Engineering_Report_RC_Baja.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:0.5rem;text-decoration:none;color:inherit;">
    <span style="font-size:1.2rem;margin-right:0.35rem;line-height:1;">📄</span>
    Engineering Project Report
  </a>
</p>

## Project Overview
This is a project done for the CWU ASME Baja R/C competition. The project addresses a need for a R/C car that is capable of completing a series of races with success. These races include the Slalom-and-sprint and the Baja competition. The scope of this piece of the project will only include the Chasssis and Drivetrain for the Baja car. The drivetrain will to be able to achieve a speed of 20 mph for success in the Slalom-and-sprint and the chassis will be durable enough to be able to withstand the offroad track of the Baja Competition.

The R/C car chassis is be made from aluminum as this material is light weight and durable enough to complete the success criteria to a satisfactory degree. This R/C car uses a single 7.2V brushed motor to drive the drivetrain and is also made from aluminum. This website will include a series of detial sketches and designs documenting the process from project conception to completion. 

<div style="display:flex;gap:1rem;flex-wrap:wrap;align-items:flex-start;">
  <figure style="flex:1 1 45%;margin:auto;">
  <img src="{{ '/assets/design-idea-non-rule-breaking.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:100%;height:auto;" class="zoomable">
    <figcaption>Figure 1: Main Sketch of Chassis and Drivetrain for R/C Baja car .</figcaption>
  </figure>
  <figure style="flex:1 1 45%;margin:0;">
  <img src="{{ '/assets/Final-Top-Assembly.png' | relative_url }}" alt="Sketch of the device - view 2" style="width:100%;height:auto;" class="zoomable">
    <figcaption>Figure 4: Current complete Assembly.</figcaption>
  </figure>
</div>

<div style="display:flex;gap:1rem;flex-wrap:wrap;align-items:flex-start;">
  <figure style="flex:1 1 45%;margin:0;">
  <img src="{{ '/assets/alternate-design-idea.png' | relative_url }}" alt="Sketch of the device - view 1" style="width:100%;height:auto;" class="zoomable">
    <figcaption>Figure 2: Alternate Design 1.</figcaption>
  </figure>
  <figure style="flex:1 1 45%;margin:0;">
  <img src="{{ '/assets/alternate-design-idea-2.png' | relative_url }}" alt="Sketch of the device - view 2" style="width:100%;height:auto;" class="zoomable">
    <figcaption>Figure 3: Alternate Design 2.</figcaption>
  </figure>
</div>

## Results

<table style="width:100%;border-collapse:collapse;">
  <thead>
    <tr style="background-color:white;">
      <th style="border:1px solid #ddd;padding:12px;background-color:white;text-align:left;">Test</th>
      <th style="border:1px solid #ddd;padding:12px;background-color:white;text-align:left;">Predicted Value</th>
      <th style="border:1px solid #ddd;padding:12px;background-color:white;text-align:left;">Testing Value</th>
      <th style="border:1px solid #ddd;padding:12px;background-color:white;text-align:left;">Pass/Fail Requirement</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color:white;">
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Impact Testing</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">0.6 inches</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">0.632 inches</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Fail</td>
    </tr>
    <tr style="background-color:white;">
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Impact testing pt.2</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">0.6 inches</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">0.58 inches</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Pass</td>
    </tr>
    <tr style="background-color:white;">
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Acceleration Testing</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">7 seconds</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">2.48 seconds</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Pass</td>
    </tr>
    <tr style="background-color:white;">
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Ramp Testing</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Pass</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Pass</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Pass</td>
    </tr>
    <tr style="background-color:white;">
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Top Speed Testing</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">30 mph</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">26.6 mph</td>
      <td style="border:1px solid #ddd;padding:12px;background-color:white;">Fail</td>
    </tr>
  </tbody>
</table>

This Project turned out to be more successful than anticipated. The success critria outlined during fall quarter was that the car needed to place 3rd overall in the Baja competition to be successful. The car ended up taking 1st place in the Slalom, and the Sprint sections of the race, and 2nd place in the offroad Baja competiton section. This puts the car in 1st overall.

For testing the car was mostly successful in each test with appropriate design updates. The test that was unsuccessful could have been fixed had the test been conducted earlier in the quarter. 