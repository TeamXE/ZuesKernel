First Download Source And Extract, this could be done by using git clone or the download as Zip button on the bottom right.

Once downloaded and extracted navigate into the kernel directory and right click and select open terminal window here.

Once Tereminal is open type:

ARCH=arm CROSS_COMPILE=PATH TO YOUR TOOLCHAIN BIN FOLDER PLUS THE BIT IN FRONT OF THE FILES make msm7627a-perf_defconfig

The bit in front means if in the toolchain build folder the files have for example arm-eabi-gcc you would have to put:

ARCH=arm CROSS_COMPILE=xxx/xxx/xxx/bin/arm-eabi- the the rest.

Same goes for the next command:

ARCH=arm CROSS_COMPILE=PATH TO YOUR TOOLCHAIN BIN FOLDER PLUS THE BIT IN FRONT OF THE FILES make
