
okay, I did work for money for two years as a matlab programmer. Actually it was a quite classy environment. University style. I worked on polhemus motion tracker, the small black box. with the g4 sensors (6). I really liked the hardware, my money was ok (far less than what the administrators got at the office, but for me it was ok), and I had a room, with a huge imac. 

If you check the viper polhemus page, you can see, that the delay is 1ms, meaning, they could not get it real time, moving the sensor, and the drawing of the movement on screen. They told me to use matlab, which was a good idea (the hardware is very good), because it would've been nearly impossible to save and use the motion data later. But Matlab........ and graphics...... had to create a minimal graphics engine with a pseudo 3d visualization, and somehow I got the delay to 0ms. That was what they could not do.

But I had support, and not from my employer. Like forums, etc. Mostly hardware related. Something like an interrupt. Had to feedback some error, or delay I don't remember. Yes I think it was a feedback to error in the coordinates (yes, I'm talking about coordinates), so somehow that took advantage of something intentionally or unintentionally programmed hardware instability, more like a glitch. 

There is an inherent error in the accuracy of the coordinate transmission from the electromagnetic measurement conversion to float. If you feedback the error in the recalculation, or something...... like if there's weak wifi signal if it's rainy. Have to send the packets over and over again. If you feedback the error (and other tricks too, but that was it), then somehow the glitch becomes productive... hahahahaha

I'm just writing because that was years ago, now it's obsolete anyway. But you might want to use it for theater graphics modeling, attaching the sensors to the arm, etc.....

The pain was in getting a good measurement calibration (that was the support, and the interrupt communication method). One pixel was a movement, and how many millimiters was in the sensor.... I honestly can't recall.... most of it is .... hahaha

so, if you moved the sensor with a steady even hand, then you got pixel to pixel movement, ok. The error was an erratic jerk, seemingly totally random pixellation... or not?

So, just had to let the cube know when is the error. This implied an assumption, that the hardware had some sort of intelligence. 
