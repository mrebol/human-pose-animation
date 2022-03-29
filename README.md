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
This is the format for a file with 10 frames. The timesteps are separated by line breaks. 
```
<t1_joint0_x_float> <t1_joint0_y_float> <t1_joint0_z_float> ... <t1_joint48_x_float> <t1_joint48_y_float> <t1_joint48_z_float>   
<t2_joint0_x_float> <t2_joint0_y_float> <t1_joint0_z_float> ... <t2_joint48_x_float> <t2_joint48_y_float> <t2_joint48_z_float>   
.
.
.
<t10_joint0_x_float> <t10_joint1_y_float> <t10_joint0_z_float> ... <t10_joint48_x_float> <t10_joint48_y_float> <t10_joint48_z_float>   
```
The 49 joints have the following order:
+ 0 neck
+ 1-3 right arm shoulder to wrist
+ 4-6 left arm shoulder to wrist
+ 7-27 left hand
+ 28-48 right hand

Note: Wrist joints 6==7 and 3==28.

The hand joints have the following order:
![Hand joints](https://github.com/mrebol/human-pose-animation/blob/master/media/hand-joints.png)
