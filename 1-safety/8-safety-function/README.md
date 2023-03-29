# 1.8 Safety Functions

The safety system of the robot is designed in dual configuration (HFT=1) to satisfy the safety performance (PL) = d Cat3 of [ISO13849-1:2015] and the safety integrity level (SIL) 2 of [IEC62061:2005], and continuously monitors the status of safety related devices. When an error is detected by self-diagnosis, or a safety related signal is inputted, the safety functions will stop the robot according to the classification of stop situations determined based on the risk assessment. Also, when any of the dual switches of the safety circuit is activated, the motor drive power and brake drive power will be cut off by the sfety functions to secure a safe state. Information on the relevant status can be checked through the teaching pendant.

![](../../_assets/1.8._안전기능(Hi6)-위험.png  )

The safety-related main functions of the robot are as follows.
