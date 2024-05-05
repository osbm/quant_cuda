# quant_cuda
quant cuda cuda kernel python package


```
pip install git+https://github.com/osbm/quant_cuda
```

Before using this module you need to first import torch. Otherwise it wont work.

```python
>>> import torch
>>> import quant_cuda
>>> print(dir(quant_cuda))
['__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'vecquant2matmul', 'vecquant2recons_v2', 'vecquant3matmul', 'vecquant4matmul', 'vecquant4recons_v1', 'vecquant4recons_v2', 'vecquant8matmul']
```