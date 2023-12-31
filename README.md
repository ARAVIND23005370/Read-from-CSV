# Read-from-CSV

## AIM:
TO Read CSV file
## ALGORITHM:
### Step 1:
Import the pandas library as "pd".

### Step 2:
Read the CSV file "cars.csv" using read_csv() method and assign it to the variable "df".

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.

### Step 5:
Print the output and end the program.
## PROGRAM:
```PYTHON
#Program to read contents from a csv file
#Developed by : ARAVIND R
#Register nuumber:212223230019
import pandas as pd
df=pd.read_csv("C:\Users\admin\Downloads\nba.csv")
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```
## OUTPUT:
![Screenshot 2023-12-31 202852](https://github.com/ARAVIND23005370/Read-from-CSV/assets/148514836/b92bce69-7429-4d7a-959f-b51c671c0005)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
