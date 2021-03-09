# Safe control ICRA21
ICRA 2020 Workshop [Guaranteeing Safe control of Robots with uncertain dynamics and environment information](https://vikasdhiman.info/safe-control-icra21/)

 + [Googledoc](https://docs.google.com/document/d/1ifEcoNndYLdgbDbvZlOTcYW-krcTJm1BW2DvdG05Cao/edit?usp=sharing)
 + keywords: SLAM, Semantic Scene Understanding, Sensor Fusion



## Overview

Guaranteeing safety is crucial for the effective deployment of robots. Control theory research has established techniques with theoretical safety and stability guarantees based on model predictive control, reference governor design, Hamilton-Jacobi reachability, control Lyapunov and barrier functions, and contraction theory. Similarly formal methods verification has been used to guarantee safety in systems. Existing techniques, however, predominantly assume that the robot motion dynamics and safety constraints are precisely known in advance. This assumption cannot be satisfied in the unstructured and dynamic real-world conditions. For example, an aerial vehicle aiding in disaster response must operate in an unpredictable environment subject to extreme disturbances. Similarly, a walking robot providing last-mile delivery has to traverse changing terrain while negotiating pedestrian traffic. 

Recent progress in machine learning allows learning robot dynamics and environment models from sensory data. For example, Gaussian Process regression and Koopman operator theory have shown promise in learning dynamics models. Similarly, deep neural network models have enabled impressive results in 3D reconstruction from visual data. Despite their empirical success, these works usually do not provide theoretical guarantees for safety and stability.

This workshop will bring together experts from two communities -- control theory and machine learning -- to address challenges in safe and stable robot control with learned motion and environment models. 
