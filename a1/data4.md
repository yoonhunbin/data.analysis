```
import random

import matplotlib.pyplot as plt

data_x = []
data_y = []
data_s = []

for i in range(100):
    data_x.append(random.randint(1, 100))
    data_y.append(random.randint(1, 100))
    data_s.append(random.randint(1, 100))

plt.scatter(data_x, data_y, s=data_s, c=data_s, cmap='jet', alpha=0.5)
plt.colorbar()
plt.show()
```
![](https://github.com/yoonhyunbin/data.analysis/blob/main/4.png)
