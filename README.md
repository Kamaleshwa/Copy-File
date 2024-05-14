# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.
### Step 2: 
 Print the number of contents to be displayed using df.head().
### Step 3: 
The number of rows returned is defined in Pandas option settings.
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: KAMALESHWAR KV
#Register Number: 212223240063
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("file1.txt","kml.txt")            
```
### OUTPUT:
![image](https://github.com/Kamaleshwa/Copy-File/assets/144980199/99f095fa-6008-4169-8e6a-a8557ad8950b)
![image](https://github.com/Kamaleshwa/Copy-File/assets/144980199/00706275-e1b6-417f-b3ea-cb70a4754175)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
