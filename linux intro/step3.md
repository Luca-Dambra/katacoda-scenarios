### A) Create a folder called "myfolder" in the current directory.

Hint: Use the **mkdir** command

```
mkdir myfolder
```{{execute}}

You should see the new folder as the first output of the command **ls -t**


### B) Create a copy of the file "naive_bayes.py" inside "myfolder", and name it "naive_bayes_copy.py".

Hint: Use the **cp** command specifying:
	- path of the file to copy
	- path and name of the new file

```
cp naive_bayes.py myfolder/naive_bayes_copy.py
```{{execute}}

### C) Move the file called "multiclass.py" inside the directory "myfolder".

```
mv multiclass.py myfolder/
```{{execute}}

### D) Check that the directory "myfolder" contains the required files.

```
ls myfolder/
```{{execute}}

### E) Check that the directory "myfolder" contains the required files.

```
ls myfolder/
```{{execute}}

### F) Remove the directory "myfolder".

1) First way:
- Remove manually the files inside "myfolder":
```
rm myfolder/naive_bayes_copy.py
```{{execute}}

```
rm myfolder/multiclass.py
```{{execute}}

- Remove the folder using the **rmdir** command (works only on empty folder:

```
rmdir myfolder/
```{{execute}}

2) Second way:
- Recursively remove the folder "myfolder" and all the files inside:
```
rm -R myfolder
```{{execute}}



