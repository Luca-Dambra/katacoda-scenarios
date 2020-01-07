### A) Download and install the python's library "sklearn" using pip. 

The download can take few minutes depending on the internet connection.

```
pip install sklearn
```{{execute}}

### B) Find inside tha folder "/usr" the path to the folder named "sklearn".

Hint: use the **find** command specifing:
- the directory of interest
- the argument **-name** as argument (means that it will search files and folder a specific name)
- the name of folder you are looking for

```
find /usr -name sklearn
```{{execute}}

### C) Move inside the folder named "sklearn". 

Hint: use the command **cd**

```
cd /usr/local/lib/python3.6/dist-packages/sklearn
```{{execute}}

### D) Check that you are inside the right folder.

Hint: compare the output of the command **pwd** with the required folder

```
pwd
```{{execute}}

