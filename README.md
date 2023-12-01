Modified based on XDMA driver (dma_ip_drivers) of Xilinx, to support P2P DMA with dedicated physical address to/from another device(e.g. based on BAR addr of memory through AXI BYPASS bus in another FPGA).

The original code can be get from https://xilinx.github.io/dma_ip_drivers/

Example testing command(in the directory XDMA\linux-kernel\tests)： ./run_test physical_addr(decimal)
