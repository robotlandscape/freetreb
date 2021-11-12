***Reminder on the honor system: Please do your own work here. If you need to, feel free to use this as a reference, but do your own work and make sure you understand it.***

> Calculations including: 
> - X and Y components of velocity, 
> - initial velocity vector shown graphically (as the sum of the components) and calculated analytically, 
> - and maximum height. 
> 
> You will be supplied with the time of flight and range of your projectile.

I'll work in terms of variables for now, then substitute my values in afterwards. 

```
d = distance
t = time of flight
h = release height, sqrt(1.3815^2 + 1.3815^2) + 1.2553 = 3.111 for our particular trebuchet
g = -9.81
                                        # when I do this it means I'm explaining a line
------------------------

v_x = d/t                               # Speed is distance over time

v_y:
x = x_i + v_i t + atˆ2/2                # Position formula
a is g
x is 0
x_i is h
x_f - atˆ2/2 = x_i + v_i t 
x_f - atˆ2/2 - x_i = v_i t 

v_y = (0 - (gtˆ2/2) - h)/t                  # rearrange for v_i

-------------------------

velocity vector: 
direction/angle: atan(v_y/v_x)                   # aTan gives the angle from a slope
magnitude: sqrt(v_y^2 + v_x^2)                  # Pythagoras :D

-------------------------

Maximum height: 
v = v_i + at
0 = v_y + gt                                    # We're kinda looking for the time at which the velocity is 0, so let's set v = 0
(v_y)/(g) = t                                   # rearrange for t
x = x_i + v_i t + atˆ2/2                        # now plug that into t in the position equation
x = x_i + v_i (v_y)/(g) + a((v_y)/(g))ˆ2/2      # woah that's long
h_max = h + v_y^2/g + g((v_y)/(g))ˆ2/2          # simplified a bit

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Launch 1:
d = 32 m
t = 2.6 s

v_x = d/t
= 12.307 m/s
= 44.28 mph!

v_y = (0 - (gtˆ2/2) - h)/t
= 11.556 m/s
= 41.6 mph

v = sqrt(v_y^2 + v_x^2)
= 16.882 m/s
= 60.7 mph! 

Θ = atan(v_y/v_x)
= 0.753 rad
= 43.19 degrees                                 # if only I had done this before, I would have changed the release angle a bit

max height: 
h_max = h - v_y^2/g + g((-v_y)/(g))ˆ2/2
= 24.116 m

(Only doing the first launch because the second launch was a misfire and the person recording didn't record the time for the third launch.)
```
