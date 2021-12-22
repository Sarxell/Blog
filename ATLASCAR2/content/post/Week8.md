---
title: "Week8"
subtitle: "Testing the sensors"
date: 2021-12-19T21:53:31Z
---

This time I started testing the sensors :
* Sick LMS151 LIDAR 
* Point grey Flea2 camera
* Sick LD MRS LIDAR 

Starting with the first in the list:

I had some difficulties in testing this sensor because I changed the IP address of the LIDAR when testing
it with the SOPAS enginnering tool in Windows, so I needed to change it back. After that it was only needed to create a static IP address
in the range of the IP of the LIDAR and run the roslaunch file.

The results of the LMS151 LIDAR:

{{<figure src="/LIDAR_LMS151.png" alt="LIDAR_LMS151" >}}


The cameras where only tested using the flycap program, for that I launched the roslaunch file for the drivers of the camera
and when entering the flycap program they were working.

Here's the result:

{{<figure src="/Camera_test.png" alt="camera_test" >}}

The LIDAR LD MRS was supposed to be the hardest of the three, but I had so many complications with the other two that this 
one was the easiest.
After following the tutorial to install the drivers I just launched the roslaunch file and got the values of the LIDAR:

{{<figure src="/LIDAR3D.png" alt="3D_LIDAR" >}}


