```.py

def difference(x): 
    max = 0
    for i in range(0, len(x)-1):
        d = x[i+1]-x[i]
        if d > max:
            max += d
    print(max)

difference([0,5,6,10])

```

![](quiz10diagram.jpg)
