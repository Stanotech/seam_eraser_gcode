# seam_eraser_gcode

![1](https://user-images.githubusercontent.com/48159338/215918633-2ca2246c-3ce1-4df7-be53-318049ff1b27.jpg)


This program is for repairing G-CODE generated bu CURA 3.10. When you want to print in vase mode with single layer of outer wall you need to prepare yours object as a surface with no thicnkess. Than using spiralize mode you will get most time-optimized g-code. But unfortunately Cura generating some artifacts in place where there souldb ne no seam. Cura also create last layer with wrong extrusion for every single point. This program delete arfifacts, recalculate it to proper nozzle moves with recalculated extrusion amount, and recreate properly last layer with proper X Y Z and E parameters.
