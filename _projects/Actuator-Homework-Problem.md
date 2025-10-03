---
layout: project
title: Actuator Analysis
description: Homework Assignment to design a frame/mechanism to lift the maximum possible weight to the highest possible height
technologies: [python]
image: /assets/images/Actuator-problem-statement.png
---
Homework Problem: Given a 2D design space of 150cm long and 50cm tall, a rigid bar of a fixed length (your
choice), 3 pin supports of which two need to be mounted on the ground and a linear
actuator (pick from this online catalog, use max force values only), design a
frame/mechanism to lift the maximum possible weight to the highest possible height.
Assume all the supports and bar/actuator are rigid.

In order to go about solving this problem, the first step I began with was to establish my parameters. I choose the length of my rigid bar to be 20 cm, as to not be limited by the height of the design space. I also choose the IMA actuator because it was one of the only few actuators that could fit within the vertical limitations of the design space if standing completely vertically (0.5m). 

When considering this question, there are two different aspects to focus in on: 1) Designing a frame/mechanism to lift the maximum possible weight and 2) Designing a mechanism to lift the maximum possible height.

Starting with design aspect 1, when looking to design a frame to carry the maximum possible weight, you would want to a) the angle at which the actuator is applied force onto the rigid arm and b) The distance from the pin of support that which the . In order to maximize the component of the force acting on the rigid body, the actuator should be set to apply its force perpendicular to rigid arm, this way the entire force of the actuator is being applied to induce a moment on the rigid arm. On top of that, the force applied by the actuator should be applied at the furtherest possible distance from the pin support in order to maximize the moment. The moment around any pin joint is equal to 0 (m = 0 Nm), therefore the importance of maximizing the moment induced by the actuator is so that the moment induced by the weight (w) can be as large as possible, therefore allowing the overall system to support the heaviest weight possible. 

However, the system that is able to lift the maximum possible weight is not necessarily the system that reaches the maximum possible height. The maximum possible height the system could reach would occur with the rod is made to stand completely vertical, from the angle of actuator and the force it applies.

Given the wording of the problem statement, which is to "design a frame/mechanism to lift the maximum possible weight to the highest possible height", it seems as though the focus of the question is to lift the maximum possible weight, and then based on the setup of the system, determine what the maximum height would be that this max weight can be lifted to. The general broadness of the question requires for there to be some assumptions made, as there is a lot of variability in where the weight can be placed, the angle of the actuator, the location of the actuator on the rod, etc.

For this system, we will assume that:
1. The weight being maximized (m) is held on the edge of the rigid rod (at length L away from the pivot point)
2. The goal of the problem is to maximize the weight able to be supported and then from there determine the maximum height that which this wait can be held.

Using the method learned in class: 

Given: /assets/images/Actuator-Diagram.jpeg

Required: The maximum load M that can be supported by this system

Plan: 
1) Find the value of angle theta
2) Calculate the moment about B
3) Calculate the height of the weight

Solve:
1) theta = tan^-1(0.5/0.2) (* units in terms of m *)
theta = 68.2 degrees

2) M = 0 = -(r*Fa) + wcos(theta)*(r)
Fa = 36 kN
r = 0.2m
theta = 68.2 degrees

M = 0 = (20*36) - wcos(68.2)*20
w = 96.9 kNm

3) height = 20sin(theta)
height = 18.6 cm

Therefore, the maximum possible weight that the system can support is 96.9 kNm, at a height of 18.6cm.

Discussion: Given the parameters we set to solve this equation, this answer makes plausible sense as it maximizes the force being applied to the rigid rod, therefore giving the system the potential to support the largest amount of load. Other ways you can play around with the question would be to focus in on maximizing the height rather than the weight, and possibly looking into playing around with the location of the weight on the rod; if the weight were lower on the rod, the weight could potentially be higher but also this would decrease the height, so it realy depends on what question you're asking. 
