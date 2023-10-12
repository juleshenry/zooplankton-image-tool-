# ZIT (Zooplankton Image Tool)

Makes plankton photos look real good. 

![Plankton Example](composited.png)

CLI:
```
python3 zit.py
```

![Lovely Example](mari_comp.png)

# Documentation

You will find the `composite_from_frames` method useful for creating composites of plankton locomotion.

***skip*** allows for selection of specific frames window

***interval*** deteermines the cadence of video screen captures, in seconds

***noise_delta*** is based on the average pixel of the overlay. If the overlayed pixel is itself noise, do not overlay it

***composite_epsilon*** is the difference between overlay and background threshold required to perform the overlay in composition
