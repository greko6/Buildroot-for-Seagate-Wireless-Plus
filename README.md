# Cross compiling binaries for embedded systems

### Description
This .config file is for [Buildroot] (http://buildroot.uclibc.org) to compile ffmpeg on embedded system. 

I wanted to compile it in a static way for Seagate Wireless Plus. It's a pretty neat hardware with ARM, cortex-8 and vfpv3 FPU. Generated ffmpeg is pretty big, but that small system is ok with that.

### cpuinfo
    Processor       : ARMv7 Processor rev 2 (v7l)
    BogoMIPS        : 299.38
    Features        : swp half thumb fastmult vfp edsp thumbee neon vfpv3 tls
    CPU implementer : 0x41
    CPU architecture: 7
    CPU variant     : 0x3
    CPU part        : 0xc08
    CPU revision    : 2

    Hardware        : am335xevm
    Revision        : 0000
    Serial          : 0000000000000000

