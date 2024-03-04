# Qton

Qton is written in Python.

Qton is for simulating and researching quantum computers.



## Version

Current version = `2.1.0`

Compare to `Qton 2.0.0` :

- added **copy** method
- kernel functions have been rewritten
- better scalability
- better performance
- bug fixing



## Install 

Place `qton` folder in your working directory, then import it as

```python
from qton import *
```

which is same to

```python
from qton import Qcircuit
```



## Requirement

Qton is designed as less relying on external package. The only exception is `NumPy`.

Current version is developed with

- *Python 3.9.7*
- *NumPy 1.20.3*



## Others

Detailed manual will come in future.

you can run the code in anaconda environment.

```bash
conda create -n qtonenv39 python=3.9 numpy
conda activate qtonenv39
```

```bash
pip install qiskit
pip install matplotlib
pip install pylatexenc
pip install ipython
```

after that, you can run the "Steane Code.ipynb" code in the `qtonenv39` environment.



