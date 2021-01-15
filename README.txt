
This driver may require patches not yet available in the upstream
kernel.  Check the patches directory and apply those as needed.

5.10 kernels need the threaded-napi patch.


To build against your locally compiled kernel:

make V=1 -C ~/kernel/2.6/linux-5.10.x64 M=`pwd` modules

This driver may require patches not yet available in the upstream
kernel.  Check the patches directory and apply those as needed.

5.10 kernels need the threaded-napi patch.


To build against your locally compiled kernel:

make V=1 -C ~/kernel/2.6/linux-5.10.x64 M=`pwd` modules
