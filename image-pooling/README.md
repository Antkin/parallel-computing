# Simple Pooling Example
This small example uses cuda-c to parallelize a 2x2 pooling image operation. To run the notebook place the pooling.ipynb file and the image you want to pool into the same directory.
In the notebook you then run the first two cells, "included files" and "lab0code". You can then run the execution cell. The command "!nvcc kernel.cu lodepng.cu -o kernel"
to compile the files, and then "!./kernel <image to pool name> <pooled image name> <num threads>"