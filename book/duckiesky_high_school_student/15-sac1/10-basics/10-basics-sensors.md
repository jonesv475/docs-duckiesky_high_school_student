# Intro to Sensors {#sac1-basics-sensors status=ready}

**Explain the definition of roll, pitch, and yaw.**

<figure>
    <figcaption>Roll, Pitch, and Yaw Diagram (https://upload.wikimedia.org/wikipedia/commons/0/04/Flight_dynamics_with_text_ortho.svg)</figcaption>
    <img style='width:12em' src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/Flight_dynamics_with_text_ortho.svg/1200px-Flight_dynamics_with_text_ortho.svg.png"/>
</figure>

With the help of this picture, teacher introduces the terms roll pitch and yaw, and then asks the students to identify which of the sensors measure each of them (IMU for roll and pitch, camera for yaw)

**Answers for Class Discussion Questions**

Question 1:

A: Analog-to-Digital Converter (ADC)! [Here (Material 3.15)](https://docs.duckietown.org/daffy/opmanual_sky/out/build_materials_included.html) is how it looks like. 

<div class='requirements' markdown="1">

Voltage or Current is produced by the sensors -> amplification (convert to voltage if necessary) -> ADC

</div> 

<figure>
    <figcaption>Analog and Digital Signal Diagram</figcaption>
    <img style='width:12em' src="https://www.allaboutcircuits.com/uploads/articles/An-Introduction-to-Digital-Signal-Processing-(1).png"/>
</figure>

Question 2:

A: Interpolation (estimate the data points in between known data) and extrapolation (using the current trend to predict the future data)

<figure>
    <figcaption>Interpolation and Exterpolation Graph</figcaption>
    <img style='width:12em' src="https://storage.ning.com/topology/rest/1.0/file/get/2656751898?profile=original"/>
</figure>

Question 3:

A: 

    - Filtering Frequencies: cut the frequency measurements that are unreasonably high or low

    - Combining data from multiple sensors

    - Cleverly decide which data are trustworthy

