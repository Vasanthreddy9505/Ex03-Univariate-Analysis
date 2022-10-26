                   Ex no-3 Univariate Analysis


AIM:
              To Perform  Univariate Analysis on the given data
           
 Algorithm
 
    1. Read the given data 
    2.Get information from the data 
    3.Perform the Univariate Analysis
    4.Save the clean data to file
    



PROGRAM:
df.isnull().sum()

![image](https://user-images.githubusercontent.com/113016781/191760857-efabd7bf-72eb-430a-875f-d0d28f951c70.png)

 df.info()
 
![image](https://user-images.githubusercontent.com/113016781/191761104-3ffe8bc3-fab6-4c38-85dc-7f166cb93a14.png)

df.dtypes
![image](https://user-images.githubusercontent.com/113016781/191761320-2a5867e7-19f3-4f14-ae21-1c0809e67029.png)

df.dtypes
![image](https://user-images.githubusercontent.com/113016781/191761401-4ef58417-14dd-42c8-a977-6380a5e92dda.png)

BOX PLOT:
PROGRAM :

import pandas as pd

import seaborn as sns

sns.boxplot(x='Sales',data=df)

![image](https://user-images.githubusercontent.com/113016781/191761492-12952ef2-909c-4f41-865e-6207e030a383.png)


COUNTPLOT:
PROGRAM
import pandas as pd

import seaborn as sns

sns.countplot(x='Postal Code',data=df)

![image](https://user-images.githubusercontent.com/113016781/191761827-292ee9c5-b690-4049-a140-b2669eb02810.png)


DISPLOT:
PROGRAM:
import pandas as pd

import seaborn as sns

sns.displot(df["Postal Code"])

![image](https://user-images.githubusercontent.com/113016781/191761963-5056b29c-a0e6-4bc0-98a3-6b255857a67d.png)

histplot :
PROGRAM:


import pandas as pd

import seaborn as sns

sns.histplot(x="Postal Code",data=df)

![image](https://user-images.githubusercontent.com/113016781/191762186-e2e92c52-ce52-4ec8-8ad4-a1a39538553f.png)


Skew:
import pandas as pd

import seaborn as sns

df=pd.read_csv("/content/SuperStore.csv")

df.skew()

![image](https://user-images.githubusercontent.com/113016781/191762425-c264f88f-4b4b-4674-8259-f50e6430b029.png)

Hisplot:
import pandas as pd

import seaborn as sns

sns.histplot(x='Sales',data=df)

![image](https://user-images.githubusercontent.com/113016781/191762527-0c412e77-c7a6-4bec-89ce-5ecd0844822b.png)

import pandas as pd

import seaborn as sns

sns.displot(x='Sales',data=df)

![image](https://user-images.githubusercontent.com/113016781/191762647-2c7a4db7-6ceb-4195-acd8-bd86da79d916.png)



Result
     
     Univariate Analysis is performed on given data and saved










