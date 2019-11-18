# pynqfpga

1) Used FPGA Xlinx Ultra96 for running
  - Gaussian Blur
  - Sobel Filter for edge detection
  - Code for the these algorithms done can be found in this [file]()
  
  
<b>The project uses [overlays](https://pynq.readthedocs.io/en/v2.1/pynq_overlays.html)</b>

Use two types of SAR Images
  - Small Image of resolution 201 X 250- the file can be found [here](https://github.com/varchanaiyer/pynqfpga/blob/master/small-image-pynq-Copy1.ipynb)
  - Bigger Image of resolution 803 x1232- the file can be found [here](https://github.com/varchanaiyer/pynqfpga/blob/master/big-image%20(2).ipynb)
  
  
You can notice the time taken for
  - Single/Serial processing PS vs FPGA
  - Multi- processing        PS vs FPGA 
 
