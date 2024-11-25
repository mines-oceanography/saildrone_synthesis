---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.16.4
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# Test Notebook for the Saildrone: Juoyter-Book

```{code-cell} ipython3
import warnings
warnings.filterwarnings('ignore')
import numpy as np
import matplotlib.pyplot as plt

import xarray as xr
```

### Generate Data

```{code-cell} ipython3
mean_data = 1_000
std_data = 2_000
data = np.random.normal(mean_data, std_data,  size=[50, 50])
```

### Plot

```{code-cell} ipython3
fig, axes = plt.subplots(ncols = 2)
ax = axes[0]
ax.imshow(data, cmap = 'jet')
ax.set_xlabel('X dimension')
ax.set_ylabel('Y dimension')

ax = axes[1]
ax.hist(data.ravel())
ax.set_xlabel('Values')
ax.set_ylabel('Occurence')
print(f'The data follow a normal distribution centered around the mean = {mean_data} with a standard deviation of {std_data}.')
plt.tight_layout()
```

##### This is a dummy text. G.marechal
