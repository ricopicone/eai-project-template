# Notebooks

This directory contains Jupyter notebooks for exploration and experimentation.

To create a new notebook:

1. In VS Code, open the Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Windows)
2. Select "Jupyter: Create New Blank Notebook"
3. Save it with a `.ipynb` extension in this directory

Example notebook workflow:

```python
# Cell 1
import torch
import numpy as np
import matplotlib.pyplot as plt

# Cell 2
data = np.random.randn(100)
plt.hist(data)
plt.show()

# Cell 3
tensor = torch.from_numpy(data)
print(f"Tensor shape: {tensor.shape}")
```

See the course notebooks for examples and best practices.
