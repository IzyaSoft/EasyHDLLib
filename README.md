# EasyHDLLibrary
A coocbook of HDL (primarily Verilog) modules

Modules

Data Stcructures:
1) Fifo with synchronous clear, push and pop bu clock, with parametrized data by data width and capacity.

Clock utils:
1) Clock divider by specific value (1-255). If divider is set to 1 than clock_divider works like repeater

Analysis
1) frequency_analyzer - for measuring time of action impulses with defined frequency (done for two frequencies, but easily could be expanded)

All modules contains tests with setting test signals by .tcl script and were successfully implemented in various applications.

Tested with Vivado 2016.2 Web Pack
