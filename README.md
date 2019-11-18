# pynqfpga

1) Used FPGA Xlinx Ultra96 for running
  - Gaussian Blur
  - Sobel Filter for edge detection
  - Code for the these algorithms done can be found in this [file](https://github.com/varchanaiyer/pynqfpga/blob/master/basic%20blurring%20and%20edge%20detection-Copy1.ipynb)
  
  
<b>The project uses [overlays](https://pynq.readthedocs.io/en/v2.1/pynq_overlays.html)</b>

Use two types of SAR Images
  - Small Image of resolution 201 X 250- the file can be found [here](https://github.com/varchanaiyer/pynqfpga/blob/master/200.jpeg)
  - Bigger Image of resolution 803 x1232- the file can be found [here](https://github.com/varchanaiyer/pynqfpga/blob/master/Sandia%20mini%20SAR%20image.jpg)
  
  
You can notice the time taken for
  - Single/Serial processing PS vs FPGA-
  - Multi- processing        PS vs FPGA
  
 For smaller image:
  - The processing file can be found [here](https://github.com/varchanaiyer/pynqfpga/blob/master/small-image-pynq-Copy1.ipynb)
  For the larger image:
  - The processing file can be found [here](https://github.com/varchanaiyer/pynqfpga/blob/master/big-image%20(2).ipynb)
 
