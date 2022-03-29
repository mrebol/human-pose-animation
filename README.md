# Human Pose Animation on UMA 2 Character in Unity

This Unity project animates an UMA 2 character given human pose input.
    
![Human pose animation](https://github.com/mrebol/human-pose-animation/blob/master/media/human-pose-animation.gif)

*Human pose animation*


## Dependencies
+ Unity 2019.4
+ UMA 2 - Unity Multipurpose Avatar (Free Download in Unity Asset Store)


## Run

Open the project in Unity and press Play in the Unity Editor to run a test sequence.

## Human Pose Format
This is an example file with 10 frames. The timesteps are separated by line breaks. 
<t1_joint1_x_float> <t1_joint1_y_float> <t1_joint1_z_float> ... <t1_joint49_x_float> <t1_joint49_y_float> <t1_joint49_z_float>   
<t2_joint1_x_float> <t2_joint1_y_float> <t1_joint1_z_float> ... <t2_joint49_x_float> <t2_joint49_y_float> <t2_joint49_z_float>   
.
.
.
<t10_joint1_x_float> <t10_joint1_y_float> <t10_joint1_z_float> ... <t10_joint49_x_float> <t10_joint49_y_float> <t10_joint49_z_float>   



