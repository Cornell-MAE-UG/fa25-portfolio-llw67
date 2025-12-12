---
layout: project
title: Final Actuator Analysis
description: Homework Assignment to design a frame/mechanism to lift the maximum possible weight to the highest possible height
technologies: [python]
image: /assets/images/Beam-Diagram.jpeg
---

Problem Statement: Given a 2D design space of 150cm long and 50cm tall, a bar of a fixed length (your choice), 3 pin supports of which two need to be mounted on the ground and a linear actuator (pick from this online catalog, use max force values only), design a frame/mechanism to lift the maximum possible weight to the highest possible height. Assume all the support and actuator are rigid.

Part 1 - Ridged Beam

A) Referring back to the initial problem setup described above, we can look into defining some of the key parameters and objectives as defined in the question. Firstly, one of the biggest contraints we face in answering this question is working within the preset boundary of the 2D space, which is 150cm long and 50cm tall in this examples. These boundaries severely limit the length of material we have to consider, as well as present the further complication of introducing different angular positions in order to try and balance the length of bar wanted within the field against the angle it is setup at. Some other contraints to consider are that two supports need to be mounted on the ground and that the problem must contain a bar of fixed length and an actuator. Given the limitation in this setup, it can be assumed that the third pin support involve both the bar and actuator, acting as a connector of sorts between the two. The main objective of the problem is listed in the problem statement itself, which is to deisng a fram.mechanism to support the maximum possible weight to the height possible height, under the assumption that everything is ridged. 

B) Going back to the work I did in HW5,the first step I began with was to establish my parameters. I choose the length of my rigid bar to be 20 cm, as to not be limited by the height of the design space. I also choose the IMA actuator because it was one of the only few actuators that could fit within the vertical limitations of the design space if standing completely vertically (0.5m). When considering this question, there were two different aspects I focused in on: 1) Designing a frame/mechanism to lift the maximum possible weight and 2) Designing a mechanism to lift the maximum possible height. To create my final desing, I made the assumption that the weight being maximized (w) was held on the edge of the rigid rod (at length L away from the pivot point) and that the goal of the problem was to maximize the weight able to be supported and then from there determine the maximum height that which this wait can be held. From there, I took these boundaries and found the angle of theta between the rod and actuator that would maximize the weight being supported, balanced out my moments, and from there, calculated the height at which the weight was able to be held, which in this case would be the maximum height.

C)![Profile Picture]({{ "assets/images/Actuator-Diagram.jpeg" width="150" height="280" | relative_url }}){: class="profile-image"}

Part 2 - Non-Rigid Beam

A) Find the Maximum Deflection 

In order to find the maximum deflection of the beam, we need to first draw a proper diagram depicting the layout of the problem. Given the setup established in part A and the assumption given that we are only focusing on the components of forces acting transverse to the beam, we will be mainly examining the impact of the force of the actuator on the beam, the cos component of the weight force, and the overall contributions of the reaction force at the joint. Both the weight force and force at the actuator act at the same point, so the total force acting at that point can be calculated as:

F(total) = F(actuator) - wcos(theta)

theta = 68.2 degrees
F(actuator) = 36 kN
w = 96.9 kN

F(total) = 0 kN

Since the transversal force imparted on the rod due the actuator and the weight of the mass cancel out, the only force within the system acts parallel to the rod, therefore not imparting any sort of bending moment onto the rod. Unfortunately, this means that due to my initial setup it is not possible to account for any sort of bending in this new design as there is no transversal force acting on the beam. For part b), in order to keep the ertical deflection as low as possible and make the system as mass-efficient as possible, I would've most likely gone for some sort of carbon fiber material and a circular hollow tubular shape, maximizing I per unit area. 

C) Same Final Beam Design as Before



