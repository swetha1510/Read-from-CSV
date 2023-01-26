# Read-from-CSV

## AIM:
To write a python programming to read the content from a CSV file.

## ALGORITHM:
### Step 1:

Import the library Pandas

### Step 2:

Upload the CSV file and copy path of it.Read the CSV file using pd.read_filename.

### Step 3:

Print the content in the file from start and from bottom.

### Step 4:

Print the rows and columns from the file.

### Step 5:

End the program.

## PROGRAM:
```
# Read-from-CSV
Devloped By: SWETHA P
RegisterNumber: 22008542

import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
``` 

## OUTPUT:

![csv](https://user-images.githubusercontent.com/120623583/214827190-7a2e4e16-2cfa-4ad7-888a-0b602f92b081.png)


## RESULT:

Thus the program is written to read the content in a CSV file.
