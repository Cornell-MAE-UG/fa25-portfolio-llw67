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

In order to go about solving this problem, the first step I began with was to establish my parameters. I choose

```python
    import numpy as np
    import math
    ```