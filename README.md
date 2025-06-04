#### Building guide for CHAPSim2.0

Use the ./lib/2decomp_fft_updated, just 

```bash
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

