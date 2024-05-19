# Read-from-CSV

## AIM:

## ALGORITHM:
Step 1:
Import the pandas library, which is essential for data manipulation and analysis.

Step 2:
Use the pd.read_csv() function to read the contents of the "NBA.csv" file into a DataFrame object called df.

Step 3:
Utilize the head() method of the DataFrame to print the first 10 rows.

Step 4:
Use the tail() method to print the last 5 rows of the DataFrame.

Step 5:
Access the axes attribute of the DataFrame to determine and print the number of rows and columns

## PROGRAM:
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail(),"\n")
print("No. of rows",len(df.axes[0]))
print("No.of columns",len(df.axes[1]))
```
## OUTPUT:
![331646122-74ca30a5-4d34-44bf-95b7-0fb0710c9989](https://github.com/MohanramGunasekar/Read-from-CSV/assets/139841812/e00eb23c-e9bd-474d-bbf5-3fc59e845d7e)
![331646262-69d7595a-c037-4163-8edd-e167a4537f50](https://github.com/MohanramGunasekar/Read-from-CSV/assets/139841812/ba961655-6891-4bc7-879d-ba2362fcd7cd)

## RESULT:
Thus, the given aim was acheived and printed.
