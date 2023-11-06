__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-06*
__________________________________________________________________________

The *gait* of a robot refers to the particular way a robot moves. It is characterized by the sequence of lifting and lowering legs and placing feet on the ground.

The number of possible gaits depends on the number of legs a robot has. To find the number of different gaits possible given a number of legs $K$, use the following formula: $N = (2K - 1)!$
- For humanoids $(K = 2): N = 3! = 6$ different gaits
- For a hexapod $(K = 6): N = 11! = 39,916,800$ possible gaits.

## Properties of Gaits
- **Stability** -> the robot does not fall
- **Speed** -> the robot can move quickly
- **Energy efficiency** -> efficient energy does not use too much energy
- **Robustness** -> gait can recover from some types of failures
- **Simplicity** -> the controller for generating the gait is not unwieldy
#### Sources
__________________________________________________________________________
1. 