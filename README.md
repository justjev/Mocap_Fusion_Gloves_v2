#My Changes will be in the interest of keeping the same quality but at the lowest pricepoint possible, and eventually implementing with a Dual Kinect V2 setup for full motion, hand, and facial mocap at once.
#Particularly to be used with metahumans in Unreal Engine 5
#My Youtube channel where I will catalog the videos is www.youtube.com/hockeytree
#I intend to remove the need for the Vive Tracker completely, or replace with a DIY solution
#I intend to replace the Flex Sensors with my own Open Source design


# Mocap_Fusion_Gloves
Arduino Motion Capture Gloves visit www.MocapFusion.com for tools created by the original Mocap Fusion Gloves
<br>
## Assembly Guide:
[![Youtube Tutorial](https://raw.githubusercontent.com/guiglass/LUXOR/gh-pages/img/fusion_gloves/IMG_E0795.JPG)](https://www.youtube.com/watch?v=PCBvUHJH8Gw)
<br>
Files for assembling and programming these super low latency "DIY" motion capture glove using an Arduino and DIY Clone of 5x SEN-08606 Flex Sensor 4.5" for each finger and a Vive tracker that is strapped to the 3D printed hand strap.
<br>
<br>
Parts:
<br>

SEN-08606 Flex Sensor: https://www.sparkfun.com/products/8606 #Design Affordable DIY solution that is as good of quality

Knit Gloves: https://www.amazon.com/OPT-Brand-Winter-Gloves-Wholesale/dp/B07XZL1ZK8

Dynaflex (black): https://www.amazon.com/18280-DYNAFLEX-Black-Building-Material/dp/B000BQWXEO

Arduino Mega, or Clone 

<br>
<br>
Wiring Diagrams:
<br>

![Code Example 1](https://github.com/guiglass/Mocap_Fusion_Gloves/blob/main/Code%20Example%201/connection_guide_template_1.png)
Example #1 requires only a single Arduino Mega and is wired directly to the mocap PC through USB.

***
<br>

![Code Example 1](https://github.com/guiglass/Mocap_Fusion_Gloves/blob/main/Code%20Example%202/connection_guide_template_2.png)
Example #2 Uses a Arduino Mega for for the gloves and sends the finger data wirelessly to a receiving Arduion Uno connected to the mocap PC through USB.

***
<br>

![Code Example 1](https://github.com/guiglass/Mocap_Fusion_Gloves/blob/main/Code%20Example%203/connection_guide_template_3.png)
Example #3 two Arduino Unos or Boneduinos connected to each glove individually, both send the finger data wirelessly to a receiving Arduino Uno connected to the mocap PC through USB.


