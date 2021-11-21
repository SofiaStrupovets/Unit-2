```.py
def average(x):
    a = 0
    for i in range(0, len(x)):
        n = len(x[i])
        a += n
    ave = a / len(x)
    return ave
h = average(["cat", "dog", "hat"])
print(h)

```
![](quiz12.png)
![](quiz12diagram.jpg)
