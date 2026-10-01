# Gearbox-1
CAD model of a gearbox. It was built in Onshape following the FRC Design course gearbox.

## Images of model:
### Part studio:
<img width="922" height="767" alt="image" src="https://github.com/user-attachments/assets/984ea563-05d9-42c9-85c1-3383f0b80a32" />


### Assembled:
<img width="717" height="637" alt="image" src="https://github.com/user-attachments/assets/025de379-dfcb-4b25-81e7-46f125f98638" />
<img width="822" height="660" alt="image" src="https://github.com/user-attachments/assets/5fc4b5bb-592d-4e30-af44-ca20c3e3273f" />

## Overview
This project is a single-stage gearbox modelled in Onshape. The exercise is from the FRC Design course (Stage 1B: Power Transmissions, Exercise 1: Simple Gearbox). A 12-tooth pinion on a Falcon 500 motor drives a 60-tooth gear on the output shaft, giving a 5:1 reduction. The output shaft turns five times slower than the motor, can deliver up to five times the torque (ignoring friction losses), and spins in the opposite direction.

## Design details
- **Gear ratio:** $\frac{N_{driven}}{N_{driver}} = \frac{60}{12} = 5$, a 5:1 reduction in one stage
- **Layout sketch:** the two pitch circles are drawn tangent, which fixes the centre-to-centre distance. The motor outline is a 2.5" circle around the pinion
- **Plates:** two plates, each 1/4" thick
- **Spacing:** four 3/4" spacers hold the plates apart, placed using the Replicate tool
- **Shaft and hardware:** the shaft was made with the Robot Shaft FeatureScript, The bearings, gears, motor and bolts come from FRCDesignLib.

## What I learned
- **Using a layout sketch** I set the key dimensions (such as gear pitch circles and the motor outline) then I built the plates around them to ensure all of the components would fit.
- **Constraints** I used more constraints than in previous projects along with arcs, circles and the use tool to project from one plate onto the next.
- **Configurable parts** I used this to change a 40T gear to 60T without having to re-insert the part.
- **Assembly mates** I learnt how to use assembly mates, especially the fastened mate.


## Areas for improvement
- I would like to design a different variant of this gearbox without using a reference. I would choose different tooth counts and ratios and calculate the resulting speed and torque.
- I would like to see how two stage gearboxes change the layout and plate design and see how the ratios multiply.


## Credit
Based on [Exercise 1: Simple Gearbox](https://frcdesign.org/learning-course/stage1/1b/exercise1/) from the FRC Design course.
