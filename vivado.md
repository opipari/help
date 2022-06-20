
1. Create RTL project, do not specify sources, select Arty A7 100T as targetted board
2. Create block design
3. Insert MicroBlaze processor, run automation
4. Add UART block
5. Remove added sys_clk_i and reset pins, run automation to reuse first pins
6. Validate design
7. Create HDL wrapper on design sources
8. Run synthesis
9. Run implementation
10. Generate bitstream
11. Export hardware
12. Launch Vitis
13. Create platform project
14. Build project (ctrl-b)
15. Create application project
