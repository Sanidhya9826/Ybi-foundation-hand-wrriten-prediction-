Import Library

✓[1] import pandas as pd

(x)

[6]

✓[2] import numpy as np

✓[3] import matplotlib.pyplot as plt

Import Data

✓[4] from sklearn.datasets import load_digits

[5] df load_digits()

,axes plt.subplots (nrows-1, ncols-4, figsize (10, 3))

for ax, image, label in zip(axes, df.images, df.target):

ax.set_axis_off()

ax imshoufimage стan-nlt.cm. gray c. interpolations nearest")
