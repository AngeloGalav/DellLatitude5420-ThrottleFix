# Throttle Fixer for Dell Latitude 5420 laptops

Simple bash script to solve throttling in caused by `thermald` in Dell Latitude 5420 laptops using Linux. 
As of December 2022, Dell still hasn't solved this issue, and thus the CPU still occasionally throttles. 
On my Latitude 5420 using Manjaro, using the kernel version 5.18-rc1 does not solve this issue...

This fix is mostly made by the commands proposed by user @oisangui in [this thread](https://www.dell.com/community/Latitude/Latitude-5420-7420-7520-CPU-Throttling-Issue-on-Linux/td-p/7959019/page/17). 


## How to use
Just run this script with sudo, and your cpu frequencies will go back up asap.  