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
import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[2018,2019,2020,2021,2022]

y=[15000, 20000, 25000, 30000, 35000]

plt.plot(x,y,'g*', linestyle="dashed", linewidth=2,markersize=12)

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.title('2D Diagram')

plt.show()


<img width="818" height="584" alt="499708875-0e621948-eaff-4cd6-802d-3b72c5c75fed" src="https://github.com/user-attachments/assets/1ffc0d6a-f607-4337-b848-ba844caff973" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[2018,2019,2020,2021,2022]

y=[15000, 20000, 25000, 30000, 35000]

plt.subplot(2,2,1)

plt.plot(x,y)

plt.subplot(2,2,2)

plt.plot(x,y,'g')

plt.subplot(2,2,3)

plt.plot(x,y,'bo')

plt.subplot(2,2,4)

plt.plot(x,y,'ga')

plt.show()


<img width="824" height="592" alt="499709096-ddbed7ea-ce01-4ca8-8092-b78dcfb021c8" src="https://github.com/user-attachments/assets/2bc1ce7c-f104-4ad8-9e63-bdcaca0d8e3a" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=np.arange(0,4*np.pi,0.1)

y=np.sin(x)

plt.title("sine waveform")

plt.plot(x,y)

plt.show()


<img width="765" height="558" alt="499709239-0d327915-9023-494f-937d-cbd5da7b350b" src="https://github.com/user-attachments/assets/92ba7e97-72b6-4a0c-9986-4f6c18d99a60" />


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[2,8,10]

y=[11,16,9]

x1=[3,9,11]

y1=[6,15,7]

plt.bar(x,y,color='r')

plt.bar(x1,y1,color='g')

plt.title("Bar graph")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show()

<img width="792" height="581" alt="499709379-c5aadea2-1d6d-4648-b387-119254e51f56" src="https://github.com/user-attachments/assets/669a4aba-b086-4a71-abab-bcdb9a630c56" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[1,2,3]

y=[7,3,9]

plt.plot(x,y,color='g')

plt.title("line graph")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show()


<img width="769" height="576" alt="499709586-89d6f8cd-ea88-4801-8d7b-b50ff6d107d3" src="https://github.com/user-attachments/assets/ec6751f4-a88a-45e9-bb76-12ac80ca8f73" />


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x1=[1,2,3]

y1=[2,4,1]

plt.plot(x1,y1, label='line1')

x2=[1,2,3]

y2=[4,1,3]

plt.plot(x2,y2, label='line2')

plt.title("multiline graph")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.legend()

plt.show()


<img width="786" height="580" alt="499709768-af845d59-e411-4859-b713-64a20e8a09d1" src="https://github.com/user-attachments/assets/be208805-14ff-40c8-96f4-52340eabb71f" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[1,2,3,4,5,6]

y=[2,4,1,5,2,6]

plt.plot(x,y,color="green", linestyle="dashed", linewidth=3, marker='o', markerfacecolor="red", markersize=12, label='spices')

plt.ylim(1,8)

plt.xlim(1,8)

plt.title("line graph")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.legend()

plt.show()


<img width="811" height="562" alt="499709968-8d84fd06-af5f-45d8-9a41-d6835231f91b" src="https://github.com/user-attachments/assets/fc76f70b-5374-4a5e-b5a2-546bd6823b4f" />


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]

plt.plot(yield_apples, linestyle="dashed", linewidth=3, marker='s', markersize=12,color='g')

plt.show()


<img width="819" height="552" alt="499710177-7a52bb80-78b7-4959-95e5-eeb90f608f35" src="https://github.com/user-attachments/assets/ddfd5b5e-799f-48de-ac63-69cd92c3537a" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

oranges=[2,4,6,7,8,12,45]

apples=[2,4,5,6,8,23,37]

years=[2019,2020,2021,2022, 2023, 2024, 2025]

plt.plot(years, apples, marker='o', label='apples')

plt.plot(years, oranges, marker='o', label='oranges')

plt.title("crop yields in kanto")

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

plt.legend()

plt.show()


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

oranges=[2,4,6,7,8,12,45]

apples=[2,4,5,6,8,23,37]

years=[2019,2020,2021,2022, 2023, 2024, 2025]

plt.plot(years, apples, marker='o', label='apples')

plt.plot(years, oranges, marker='o', label='oranges')

plt.title("crop yields in kanto")

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

plt.legend()

plt.show()

<img width="804" height="581" alt="499710350-2ecb06ef-f1e7-4b44-bebb-e182db24fb1f" src="https://github.com/user-attachments/assets/cdac00f6-39bd-496d-8403-bcf267b35f59" />


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

oranges=[2,4,6,7,8,12]

apples=[2,4,5,6,8,23]

years=[2019,2020,2021,2022, 2023, 2024]

plt.bar(oranges, apples)

plt.plot(years, apples, label='apples', marker='s')

plt.plot(years, oranges, label='oranges', marker='o')

plt.title("Fruit sales")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.legend()

plt.show()


<img width="772" height="570" alt="499710634-e9a852bc-26f3-4bbb-9ca2-55d14cca6082" src="https://github.com/user-attachments/assets/810f9e7a-4ea2-4c39-857b-63bc35ff85f6" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

years=[2019,2020,2021,2022, 2023, 2024]

oranges=[2,4,6,7,8,12]

plt.figure(figsize=(12,6))

plt.plot(years, oranges, marker='o', label='oranges')

plt.title("Yield of oranges (tons per hectare)")

plt.legend()

plt.show()

<img width="1245" height="665" alt="499710877-ac01d551-f7cf-4563-9d90-0266c55c48b8" src="https://github.com/user-attachments/assets/f8a3d2c6-4110-4926-abce-b1198d2fc6b1" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

print("scatter plot is:")

x=[1,2,3,4,5,6,7,8,9,10]

y=[2,4,5,7,6,8,9,11,12,12]

plt.scatter(x,y, label='star', color='green', marker='*', s=30)

plt.title("my scatterplot")

plt.xlabel("x-axis")

plt.ylabel('y-axis')

plt.legend()

plt.show()

<img width="792" height="618" alt="499711114-5da64194-ea2a-42b7-acd1-8e68a0b03c38" src="https://github.com/user-attachments/assets/cd30e3c9-4554-48ab-aaaa-9032b8808026" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[1,2,3,4,5]

y1=[10,12,14,16,18]

y2=[5,7,9,11,13]

y3=[2,4,6,8,10]

plt.fill_between(x,y1, color='green', label='y1')

plt.fill_between(x,y2, color='blue', label='y2')

plt.fill_between(x,y3, color='red', label='y3')

plt.title("fill between is")

plt.legend()

plt.show()

<img width="736" height="559" alt="499711353-b50ceb68-7f2a-4056-8f16-8d6b3bbf5baa" src="https://github.com/user-attachments/assets/d5f71135-04fa-489f-bae5-5da045e27bf0" />


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[1,2,3,4,5]

y1=[10,12,14,16,18]

y2=[5,7,9,11,13]

y3=[2,4,6,8,10]

plt.stackplot(x,y1, y2,y3, labels=['line1', 'line2', 'line3'])

plt.legend(loc='upper left')

plt.title("Stacked line chart")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show()

<img width="805" height="573" alt="499711572-2e62a5f9-b5d7-464f-9ba8-39bc28331679" src="https://github.com/user-attachments/assets/d54ba77c-21bd-4016-995e-cab193a7aa3c" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

from scipy.interpolate import make_interp_spline

x=np.array([1,2,3,4,5,6,7,8,9,10])

y=np.array([2,4,5,7,8,9,10,11,12,13])

spl=make_interp_spline(x,y)

x_smooth=np.linspace(x.min(),x.max(),100)

y_smooth=spl(x_smooth)

plt.plot(x,y,'o', label='data')

plt.plot(x_smooth,y_smooth, label="spline")

plt.legend()

plt.show()

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

from scipy.interpolate import make_interp_spline

x=np.array([1,2,3,4,5,6,7,8,9,10])

y=np.array([2,4,5,7,8,9,10,11,12,13])

spl=make_interp_spline(x,y)

x_smooth=np.linspace(x.min(),x.max(),100)

y_smooth=spl(x_smooth)

plt.plot(x,y,'o', label='data')

plt.plot(x_smooth,y_smooth, label="spline")

plt.legend()

plt.show()

<img width="730" height="551" alt="499711797-19c4a977-414b-4e3e-bffd-569935aff28f" src="https://github.com/user-attachments/assets/e9c3a78c-32ca-43b6-a924-ece2780c25db" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

values=[5,6,7,3,2]

names=['A', 'B', 'C', 'D', 'E']

plt.bar(names, values, color='green')

plt.show()

<img width="703" height="532" alt="499712030-4f1208fe-ee6b-4858-9230-f2cfda8fdad2" src="https://github.com/user-attachments/assets/a6b30dc7-5658-4920-9d9f-08c1bd835108" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

ages=[2,5,70,40,45,50,43,40,44,60,7,13,57,18,90, 77, 32,21,20,40]

range1=(0,100)

bins=10

plt.hist(ages, bins, range1, color='green', histtype='bar', rwidth=0.8)

plt.xlabel('ages')

plt.ylabel('no. of people')

plt.title('my histogram')

plt.show()

<img width="838" height="598" alt="499725907-9f62ce34-36ae-4b5e-ab69-6708bae93ab9" src="https://github.com/user-attachments/assets/2721c95b-c7a1-4085-a2e6-50df60bee961" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[2,1,6,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x,bins=10, color='pink', alpha=0.5)

plt.show()

<img width="709" height="528" alt="499726338-0cd5b41b-69f4-43ec-8c77-947481f5c6aa" src="https://github.com/user-attachments/assets/749ac756-79e1-49c1-9b41-ffb514088b26" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

np.random.seed(0)

data=np.random.normal(loc=0, scale=1, size=100)

fig,ax=plt.subplots()

ax.boxplot(data)

ax.set_xlabel('x-axis')

ax.set_ylabel('y-axis')

ax.set_title('box plot')

ax.text(0.5, 1.6, 'box plot')

plt.show()

<img width="766" height="568" alt="499726623-ad327d52-aba2-4224-a63f-42cf0629febd" src="https://github.com/user-attachments/assets/5c6209bd-2b76-401f-91ca-46b34236829a" />

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

activities=['eat', 'sleep', 'work', 'play']

slices=[3,8,8,6]

colors=['r', 'y', 'g', 'b']

plt.pie(slices, labels=activities, colors=colors, startangle=90, shadow=True, explode=(0,0,0,0), radius=1.2, autopct='%1.1f%%')

plt.legend()

plt.show()

<img width="605" height="518" alt="499726869-a4074d10-f99d-4ab4-b722-6d455b445775" src="https://github.com/user-attachments/assets/4fcc8e69-c2bc-47bd-97f3-0be115c40eda" />


import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

labels=['python', 'c++', 'ruby', 'java']

sizes=[215, 130, 245, 210]

colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']

explode=(0.1,0,0.1,0)

plt.pie(sizes, explode=explode, colors=colors, labels=labels, autopct='%1.1f%%', shadow=True)

plt.axis('equal')

plt.show()

<img width="661" height="503" alt="499727056-276bc055-bc03-4570-a7dd-acbb2bed521f" src="https://github.com/user-attachments/assets/b7d4cacb-ea37-4afa-9fc4-35e518f9ae87" />




# Result:
 Include your result here
