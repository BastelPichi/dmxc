# Kernel
DMXControl consists of multiple Components. One beeing the Kernel. The Kernel is doing all the work in the background, e.g. calculating effects, communicating with DMX Interfaces etc., while the GUI just displays Values from the kernels.

The Kernel is automatically started when laaunching DMXControl. Normally it runs in the background, however you can make it visible (and see error logs live) by going to Help -> Show Kernel.

It's not reccomeneded to close the Kernel by clicking on the X-Button in the Windowbar. Instead, type `shutdown` and press enter, or press Ctrl + C.  

Kernel and GUI can be run on two different PCs. This can be useful when working with multiple Computers on the same project, or when you want to load off power from the FOH PC to a more powerful Server.  
Following ports need to be whitelisted in your Firewall:  
![image](https://github.com/BastelPichi/dmxc/assets/63782569/abdb482f-7c4b-4f55-95d4-486265f09842)  
(windows should ask you automatically...)
