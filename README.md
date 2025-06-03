# LWE_via_IP

Implementing an attack on the discrete version of the search Learning With Errors (LWE) problem via integer programming in Pyomo.

## Requirements

- `numpy`  
- `scipy`  
- `fpylll`  
- `pyomo`  
- An IP solver (we used CBC MILP)

You can install `numpy`, `scipy`, and `fpylll` by installing **SageMath 9.x** via `conda`.  

## Acknowledgments

- The integer programming formulation is based on the method introduced by Shirase in [ePrint 2023/1162](https://eprint.iacr.org/2023/1162.pdf).  
- LWE instances are generated using the [Too Many Hints](https://github.com/juliannowakowski/lwe_with_hints) framework.
