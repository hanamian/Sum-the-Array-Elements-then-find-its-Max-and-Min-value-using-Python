
# Sum the Array Elements the find its Max and Min value using Python
```python
import numpy as np
input = [3,4,5,
        6,7,8]

#Sum all of them
sumAll= np.sum(input)
i=0
while i< len (input):
  a= sumAll-input[i]
  print(a)
  i+=1
```
#### The answer should be **30 29 28 27 26 25**
```python  
#maximal
allSum =[30,29,28,27,26,25]
maxi=np.max(sum)
maxi

#minimal
minim=np.min(sum)
minim
```
