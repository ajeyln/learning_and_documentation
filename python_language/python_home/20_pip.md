<h1 align="center">Python Packages (PIP) - Introduction</h1>

Python Package index is package manger for python packages or modules.

* *Package* :  a package contains all the files needed  for a modules <br />
* to check PIP is installed or not `- pip  --version` <br />

* Using a Package -  once package got installed, we need to import the package 
	*Eg*:	
```python
			import camelcase 
			c = camelcase.CamelCase() 
			txt = "hello world" 
			print(c.hump(txt)) //This method capitalizes the first letter of each word.
```

* Remove a package -  to uninstall the package, 
		`pip uninstall (package name)`

* List Packages - to list the installed package in system, 
		`pip list`
