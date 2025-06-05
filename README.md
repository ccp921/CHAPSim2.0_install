# Prerequisites

GCC>=10.0 and OpenMPI-4.0.3 on Ubuntu-20.04 (just for the case here, other versions of OpenMPI need to be tested).

# Building guide for CHAPSim2.0

Use the ./lib/2decomp_fft_updated, just

```bash
mkdir bin mod obj
cd lib/2decomp_fft_updated
mkdir include
cd src
make
```

Then, you got the compiled 2decomp_fft. Turn to compile the CHAPSim2.0 now

```bash
cd ../../..
make all
```

