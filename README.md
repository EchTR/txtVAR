# txtVAR
This module allows assigning variables for files with txt extension and reading existing variables.
<br>

## Wiki:

<br>

#### IMPORTANT:
 - You do not need to put the extensions of the text files: texts.txt => txtvar("texts") 
 - Simply variable definition: var1 > var1value (You have to leave a space before and after the '>' sign.)
 - The last line must be the '#' sign.


<br>
<br>


#### Functions:

| Function | Description | Usage |
| --- | --- | --- |
| variables() | Returns the variables in the file in dictionary type. | txtvar("texts").variables() |
| numofvars() | Returns the total number of variables in the file. | txtvar("texts").numofvars() |

<br>
<br>

#### Output:

texts.txt:
```
developer > echtr
hello
steam id > echtr
#
```

| Function | Output |
| --- | --- |
| variables() | {'developer':'echtr','steam id':'echtr'} |
| numofvars() | 2 |
