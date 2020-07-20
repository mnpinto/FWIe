# FWIe
> Enhancing the Fire Weather Index with atmospheric instability information


## Install

`pip install fwie`

## How to use

```python
import numpy as np
from fwie.fwie import FWIe_calc

FWIe_calc(np.array([[50]]), np.array([[12]]))
```

    100%|██████████| 1/1 [00:00<00:00, 5857.97it/s]





    array([[61.7]])


