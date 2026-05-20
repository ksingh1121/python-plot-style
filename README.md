# Plot styles

My personal Matplotlib plotting styles.

## Usage

```python
import matplotlib.pyplot as plt

plt.style.use(
    "https://raw.githubusercontent.com/ksingh1121/python-plot-style/main/physics.mplstyle"
)
```

## Retina display in Jupyter notebooks

For sharper plots inside Jupyter notebooks, use the retina display format:

```python
from matplotlib_inline.backend_inline import set_matplotlib_formats

set_matplotlib_formats("retina")
```

A typical notebook header is therefore:

```python
import numpy as np
import matplotlib.pyplot as plt
from matplotlib_inline.backend_inline import set_matplotlib_formats

set_matplotlib_formats("retina")

plt.style.use(
    "https://raw.githubusercontent.com/ksingh1121/python-plot-style/main/physics.mplstyle"
)
```

The `.mplstyle` file controls the appearance of the plot, while `set_matplotlib_formats("retina")` makes the inline notebook image sharper.
