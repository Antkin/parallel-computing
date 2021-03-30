# Image transformation project

For this project I implemented a rotation transformation in parallel using both unified and explicit memory allocation and compared the runtime to the opencv implementation. The code can perform 90, 180, and 270 degree rotations. 
This project was written in python, and the image you want to rotate as well as the type of rotation must be specified in the notebook. The code for timing and
and comparing to opencv is included. We see better gains with larger image sizes (4k/8k).
