- 👋 Hi, I’m Anh Linh Tran
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
altt1/altt1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
from sklearn.pipeline import Pipeline
from sklearn.preprocessing import StandardScaler,PolynomialFeatures
from sklearn.linear_model import LinearRegression
matplotlib inline

#Module 1
df=pd.DataFrame(data)
df.head(5)
df.dtypes()

#Module 2

x_data=df.drop([“id”],[“unnamed: 0”], axis=1)
df.describe(x_data)


#Module 3
Val=df.value_counts(“floor”)
Val.to_frame()







