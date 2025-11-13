# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
## Name: Sree Govind SA
## Reg No: 212224240159
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

     import pandas as pd
     import numpy as np
     import seaborn as sns
     import matplotlib.pyplot as plt 
     marks=[13,45,63,78]
     student=['ABC','QOR','EFB','TOB']
     plt.plot(marks,student)
     plt.xlabel('Marks')
     plt.ylabel('Student name')
     plt.show()

     

<img width="502" height="150" alt="image" src="https://github.com/user-attachments/assets/d5a8991f-a580-468c-8fed-f94f33f82edc" />

     marks=[13,45,63,78]
     student=['ABC','QOR','EFB','TOB']
     plt.plot(marks,student)
     plt.xlabel('Marks')
     plt.ylabel('Student name')
     plt.show()    

 <img width="740" height="544" alt="image" src="https://github.com/user-attachments/assets/b1806547-ab05-4a35-8090-576f3dd115f8" />
    
     x=[10,20,30,40,50]
     y=[100,200,300,400,500]
     plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
     plt.show()
     x=np.arange(0,15)
     y=np.arange(0,15)
     x
     y
     plt.scatter(x,y,c='r')
     plt.xlabel('X axis')
     plt.ylabel('y axis')
     plt.title('Scatter plot')
     plt.show()

 <img width="730" height="497" alt="image" src="https://github.com/user-attachments/assets/74e2011e-eef6-44fd-81b9-326f6099d2c1" />

 <img width="756" height="579" alt="image" src="https://github.com/user-attachments/assets/9360924e-698c-49aa-a1c7-bbf8cbde88a3" />

     act=['eat','sleep','work','play']
     slices=[3,7,8,6]
     color=['r','y','g','b']
     plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
     plt.legend()
     plt.show()

<img width="807" height="509" alt="image" src="https://github.com/user-attachments/assets/e9a2f6f8-37c4-493f-b6d9-4d0840de6de7" />

    feedback=['Good','excellent','Perfect','Ok']
    slices=[4,10,3,8]
    color=['y','r','b','g']
    plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
    plt.legend()
    plt.show()
    
<img width="631" height="477" alt="image" src="https://github.com/user-attachments/assets/2528fc57-78b9-48c6-9200-30076ffb47a7" />

     x = [1, 2, 3, 4, 5]
     y1 = [10, 12, 14, 16, 18]
     y2 = [5, 7, 9, 11, 13]
     y3 = [2, 4, 6, 8, 10]
     plt.fill_between(x, y1, color='blue')
     plt.fill_between(x, y2, color='green')
     plt.plot(x, y1, color='red')
     plt.plot(x, y2, color='black')
     plt.legend(['y1','y2'])
     plt.show()

 <img width="724" height="499" alt="image" src="https://github.com/user-attachments/assets/d202c626-2de9-4852-b9c9-8e64516d8e5f" />
    
     height = [10, 24, 36, 40, 5]
     names = ['one', 'two', 'three', 'four', 'five']
     c1=['red', 'green'] 
     c2=['b', 'g']
     plt.bar (names, height, width=0.8, color=c1)
     plt.xlabel('x - axis')
     plt.ylabel('y - axis')
     plt.title('My bar chart!')
     plt.show()  

<img width="816" height="563" alt="image" src="https://github.com/user-attachments/assets/8e886bba-4b54-4dfa-b6d0-6371ec7250a6" />

     x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
     plt.hist(x, bins = 10, color='blue', alpha=0.5)
     plt.show()

<img width="721" height="537" alt="image" src="https://github.com/user-attachments/assets/e0ec40a7-1976-4bbb-b841-a70de00bf284" />

     np.random.seed(0)
     data=np.random.normal(loc=0, scale=1, size=100)
     data

<img width="801" height="452" alt="image" src="https://github.com/user-attachments/assets/766972e2-4769-405a-87b7-e6dd294c88fe" />

     fig, ax= plt.subplots()
     ax.boxplot(data)
     ax.set_xlabel('Data')
     ax.set_ylabel('Values')
     ax.set_title('Box Plot')
     
<img width="754" height="603" alt="image" src="https://github.com/user-attachments/assets/0196630d-e0f2-4d93-b089-7b271fa73c16" />
     
     

    
# Result:
  The code were executed successfully.
