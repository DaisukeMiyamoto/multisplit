# multisplit
easy to use wrapper for multisplit method in the NEURON  

## usage
### make special
nrnivmodl mod  

### run
cd hoc  
mpiexec -np 1 python init.py  
mpiexec -np 8 python init.py  


