
1. Create RTL project, do not specify sources, select Arty A7 100T as targetted board
2. Create block design
3. Insert MicroBlaze processor, run automation
4. Add DDR3 SDRAM to fix critical D-cacheable memory messages
5. Remove added sys_clk_i and reset pins, run automation to reuse first pins
6. Validate design
7. Create HDL wrapper on design sources
