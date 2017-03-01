##Raspberry Pi TV rotator

Moment of Inertia for the tv
- approximated as a rod rotated about its center
  - I = (1/12) * M * L^2

Approximate specs for 40 inch tv:
- length = 37.2 inches
- weight = 21 lbs
- L = .68 m
- M = 9.5 kg
- I = 5.11 kg * m^2


Stepper Motor for precision control

The number of steps per revolution ranges from 4 to 400. Commonly available step counts are 24, 48 and 200.

Resolution is often expressed as degrees per step. A 1.8° motor is the same as a 200 step/revolution motor.

The trade-off for high resolution is speed and torque. High step count motors top-out at lower RPMs than similar size. And the higher step-rates needed to turn these motors results in lower torque than a similar size low-step-count motor at similar speeds.
