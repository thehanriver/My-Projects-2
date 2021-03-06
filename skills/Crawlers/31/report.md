#  LIDAR v3

Author: Mario Han

Date: 2020/12/1
-----

## Summary

So I collected the values from SCL and SDA over I2C. The LIDAR sends data over 2 bytes; both of the bytes are read. Then the distance is calculated. The distance is displayed on console. Since it uses I2C, I used the accelerometer code from previous quest as well as a code snippet on piazza. The wiring was done using the datasheet.

## Sketches and Photos

![IMG_9425](https://user-images.githubusercontent.com/45515930/100811907-c63a6d80-3409-11eb-80f7-93c1727b2b9a.JPG)

## Modules, Tools, Source Used Including Attribution

[Link to datasheet](https://static.garmin.com/pumac/LIDAR_Lite_v3_Operation_Manual_and_Technical_Specifications.pdf)

## Supporting Artifacts

[Link to my code](https://github.com/BU-EC444/Han-Mario-1/tree/master/skills/cluster-5/31/code)

-----
