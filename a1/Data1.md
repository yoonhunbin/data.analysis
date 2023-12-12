```
import matplotlib.pyplot as plt

x_data = [1, 2, 3, 4, 5]

y_data = [10, 20, 30, 50, 40]

y2_data = [20, 30, 70, 30, 20]

y3_data = [15, 20, 35, 100, 55]

plt.rc("font", family = "Malgun Gothic")

plt.rc("axes", unicode_minus = False)

plt.title('그래프')

plt.plot(x_data, y_data
        )
plt.plot(x_data, y2_data)

plt.plot(x_data, y3_data)

plt.show()
```
![](https://github.com/yoonhyunbin/data.analysis/blob/main/1.png)
