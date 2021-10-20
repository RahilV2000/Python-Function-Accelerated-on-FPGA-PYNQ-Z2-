# Python-Function-Accelerated-on-FPGA-PYNQ-Z2

I have accelerated the function of the FIR filter on the PYNQ z2 board
If you run this progrm you will se the results that execution time of software implementation is higher than the Hardware implementation
I have created a custom ip for zynq soc system of  fir filter ip(free available) and created overlay and uploaded it to the pynq. In hardware implementation i have used the AXI DMA channel for executing the fir filter function. Input goes int the Memory get processed using the overlay and output comes out of he memory.
I have included the bit file and tcl file of the dsign. 
