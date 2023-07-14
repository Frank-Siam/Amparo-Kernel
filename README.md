# Amparo-Kernel
a windows compatiple OS kernel for x86 and ARM 32/64bit

note: there is nothing usefull, yet. i just start the project.

this kernel is loaded by the bootloader. it consist of ntoskrnl.exe vidmem.dll hal.dll.

these modules are native PE modules.
we can build all in 32bit or all in 64bit.

the kernel provides kernel services as exported functions to the rest of the system.
the next level of services will be drivers and a executive or subsystem. win32-subsystem will be the most important one.

this repo will hold ntoskrnl bootvid kdcom hal

the next level of the os is the native API ntdll smss other subsystems  this modules will be organized? i will decide later
