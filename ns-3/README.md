# Reproduce the results of DRR in ns-3

## Steps to reproduce

* Step 1: Clone this repo:

``git clone https://github.com/vilas897/Implementation-of-Deficit-Round-Robin-in-ns-3``

* Step 2: Enter the ns-3 directory

* Step 3: Configure and build the cloned repo:

```
./waf configure
./waf
```

* Step 4: Run DRR examples available under ``scratch`` directory:

```
./waf --run scratch/first-bulksend
./waf --run scratch/second-bulksend
./waf --run scratch/third-mix
```

Result will be generated under ``results/`` directory.
