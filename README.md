# Quadrotor_UAV_FLADRC
Design of FLADRC controller for UAV

Current progress：
Fuzzy controller
LADRC
Fuzzy-PID

Because the internal program of Px4 flight control is very complex, we need to realize the attitude loop control of UAV on the external airborne computer. Offboard is used to calculate the speed of UAV from outside and send it to flight control executive.
