---
layout: project
title: Final Actuator Analysis
description: Homework Assignment to design a frame/mechanism to lift the maximum possible weight to the highest possible height
technologies: [python]
image: /assets/images/Actuator-problem-statement.png
---

Problem Statement: Given a 2D design space of 150cm long and 50cm tall, a bar of a fixed length (your choice), 3 pin supports of which two need to be mounted on the ground and a linear actuator (pick from this online catalog, use max force values only), design a frame/mechanism to lift the maximum possible weight to the highest possible height. Assume all the support and actuator are rigid.

Part 1 - Ridged Beam

A) Referring back to the initial problem setup described above, we can look into defining some of the key parameters and objectives as defined in the question. Firstly, one of the biggest contraints we face in answering this question is working within the preset boundary of the 2D space, which is 150cm long and 50cm tall in this examples. These boundaries severely limit the length of material we have to consider, as well as present the further complication of introducing different angular positions in order to try and balance the length of bar wanted within the field against the angle it is setup at. Some other contraints to consider are that two supports need to be mounted on the ground and that the problem must contain a bar of fixed length and an actuator. Given the limitation in this setup, it can be assumed that the third pin support involve both the bar and actuator, acting as a connector of sorts between the two. The main objective of the problem is listed in the problem statement itself, which is to deisng a fram.mechanism to support the maximum possible weight to the height possible height, under the assumption that everything is ridged. 

B) Going back to the work I did in HW5,the first step I began with was to establish my parameters. I choose the length of my rigid bar to be 20 cm, as to not be limited by the height of the design space. I also choose the IMA actuator because it was one of the only few actuators that could fit within the vertical limitations of the design space if standing completely vertically (0.5m). When considering this question, there were two different aspects I focused in on: 1) Designing a frame/mechanism to lift the maximum possible weight and 2) Designing a mechanism to lift the maximum possible height. To create my final desing, I made the assumption that the weight being maximized (w) was held on the edge of the rigid rod (at length L away from the pivot point) and that the goal of the problem was to maximize the weight able to be supported and then from there determine the maximum height that which this wait can be held. From there, I took these boundaries and found the angle of theta between the rod and actuator that would maximize the weight being supported, balanced out my moments, and from there, calculated the height at which the weight was able to be held, which in this case would be the maximum height.



C)![Profile Picture]({{ "assets/images/Actuator-Diagram.jpeg" width="150" height="280" | relative_url }}){: class="profile-image"}

