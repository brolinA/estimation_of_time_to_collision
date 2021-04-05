# Estimating Time To Collision (TTC)
This is the 3rd project in the Sensor fusion nano-degree. Here we calculate the Time to Collision (TTC) based on both camera only and Lidar only measurements and comparison between the different detector-descriptor type is made to evaluate the performance.

The detailed  report of the findings can be seen in the **`project_report.pdf`** file in the report directory.

## Usage instruction.

Once you create the executable file using the `cmake ..` & `make` command in your build directory, a executable will be created in the name `3D_object_tracking`. You can run the code using the following command

`./3D_object_tracking <detector_type> <descriptor_type>`

Various detector-descriptor available are shown below. The values are case-sensitive. So use **Only Caps Letter** to defince the detector and descriptor types.
Detectors implemented:
1. Harris.
2. BRISK.
3. FAST.
4. ORB.
5. SIFT.
6. AKAZE.

Descriptors implemented:
1. BRIEF.
2. ORB.
3. FREAK.
4. SIFT.
5. AKAZE.
