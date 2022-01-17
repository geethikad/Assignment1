# Assignment1
# using matplotlib library, I plotted subplotgrid
import matplotlib.pyplot as plt
import numpy as np
t=np.arange (1, 11)
y1=[12,23,45, 65, 10,3,14, 16, 32,33]
y2=[58,2, 65, 99, 12, 32, 23, 56, 78, 6]
y3=[45,3,23, 65, 91, 73, 82, 19, 61, 45]
fig=plt.figure()
f1=plt.subplot2grid((5,6),(0,0),rowspan=1,colspan=3)
f2=plt.subplot2grid((5,6),(0,3),rowspan=1,colspan=1)
f3=plt.subplot2grid((5,6),(0,4),rowspan=1,colspan=2)
f4=plt.subplot2grid((5,6),(1,0),rowspan=3,colspan=1)
f5=plt.subplot2grid((5,6),(1,1),rowspan=1,colspan=2)
f6=plt.subplot2grid((5,6),(1,3),rowspan=1,colspan=3)
f7=plt.subplot2grid((5,6),(2,1),rowspan=1,colspan=1)
f8=plt.subplot2grid((5,6),(2,2),rowspan=3,colspan=2)
f9=plt.subplot2grid((5,6),(2,4),rowspan=3,colspan=1)
f10=plt.subplot2grid((5,6),(2,5),rowspan=3,colspan=1)
f11=plt.subplot2grid((5,6),(3,1),rowspan=1,colspan=1)
f12=plt.subplot2grid((5,6),(4,0),rowspan=1,colspan=2)
plt.tight_layout()
plt.show()
