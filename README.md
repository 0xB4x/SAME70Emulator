# SAME70Emulator
Side project to emulate SAME70 ROM code using Qiling


# Installation
1- Download "Pre-install prep" from (https://docs.qiling.io/en/latest/install/)  
2- Install afl-fuzz https://aflplus.plus/building/  
3- Install Qiling after applying patch file  
> git clone  https://github.com/qilingframework/qiling.git  
> cd qilinq  
> git apply QilingCortexM7Support_SAME70ROM_Fuzzer.patch  
> pip install .

![ROM](./emulator.png)  

![Fuzzing](./fuzz.png) 


Ref: https://0x01team.com blog
