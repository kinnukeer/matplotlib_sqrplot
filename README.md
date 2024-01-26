# matplotlib_sqrplot
import matplotlib.pyplot as plt
x=[2,4,6,8,10]
y=[i**2 for i in x]
plt.plot(x,y,marker='o',markerfacecolor='red')
plt.xlabel('Number')
plt.ylabel('Square of the Number')
plt.title('Square plot')
plt.show()
