### A) List the contents of the current directory

Hint: Use the command **ls**

```
ls
```{{execute}}

Try out few parameters of the *ls* command, passing the following arguments:
	- **-F** (append an indicator of the file type)
	- **-l** (output detailed information on the directory)
	- **-S** (sort the results by name)
	- **-t** (sort the results by modification)
	- **-R** (display a recursive listing)

Hint: you can combine two or more argument.

```
ls -lR
```{{execute}}


### B) List the contents of the directory /usr/local/lib/python3.6/dist-packages/sklearn/datasets, sorted by name.

Hint: This task can be solved passing the required directory as argument to the command **ls**

```
ls -S datasets/
```{{execute}}
