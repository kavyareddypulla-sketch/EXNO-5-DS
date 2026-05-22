# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 ```
import matplotlib.pyplot as plt
x_val = [0,1,2,3,4,5]
y_val = [0,1,4,9,16,25]
plt.plot(x_val,y_val)
plt.show()

```

<img width="722" height="522" alt="image" src="https://github.com/user-attachments/assets/d22b9fc3-f780-4485-adb1-cbdf40f804c9" />

```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()

```

<img width="720" height="566" alt="image" src="https://github.com/user-attachments/assets/568d910d-970a-4999-aabd-4b91b78bb0d0" />

```

import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,5,3]
plt.plot(x1,y1,label = 'line 1')
x2 = [1,2,3]
y2 = [3,1,6]
plt.plot(x2,y2,label = 'line 2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on the same graph")
plt.legend()
plt.show()

```

<img width="715" height="567" alt="image" src="https://github.com/user-attachments/assets/cbd7bb4c-af30-444f-8d6f-6d0e477c777a" />

```

import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]
plt.fill_between(x,y1,color = 'blue')
plt.fill_between(x,y2,color = 'orange')

```

<img width="710" height="553" alt="image" src="https://github.com/user-attachments/assets/2852379f-380d-4e91-8aa7-a2884b7f4761" />

```

plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
plt.legend(loc = 'upper left')
plt.title('Stacked line charts')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()

```

<img width="705" height="573" alt="image" src="https://github.com/user-attachments/assets/960a4dac-b11b-4aeb-a3d8-cf3ed79b5c89" />

```

import numpy as np
import matplotlib.pyplot as plt
val = [2,4,7,3]
names = ['A','B','C','D']
plt.bar(names, val,color = 'purple')
plt.show()

```

<img width="694" height="530" alt="image" src="https://github.com/user-attachments/assets/e979b65c-ccb8-4119-88f8-dd80aef622c2" />

```

import matplotlib.pyplot as plt
import numpy as np
ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
range = (0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title('histogram')
plt.show()

```

<img width="694" height="552" alt="image" src="https://github.com/user-attachments/assets/8414d519-1f97-4a22-a9f4-0f8ae4ce6b0f" />

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data

```

<img width="709" height="443" alt="image" src="https://github.com/user-attachments/assets/db0ba53d-55d9-4e01-b634-f104f9bf095e" />

```

fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel("data")
ax.set_ylabel("values")
ax.set_title("box plot")

```

<img width="733" height="605" alt="image" src="https://github.com/user-attachments/assets/74b2d40c-dcbf-493e-8738-87cea946d156" />

```

import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

<img width="535" height="516" alt="image" src="https://github.com/user-attachments/assets/bccfefc1-e7db-4aed-a106-d715eb15a252" />



# Result:
 Include your result here
