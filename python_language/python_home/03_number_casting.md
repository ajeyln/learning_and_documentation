<h1 align="center">Python Number and Casting</h1>

* There are 3 numeric types in Python - int, float & complex <br />
+ *Int* - Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length. <br />
			*Eg*:  	`x = 100` <br />
					`y = -15242` <br />
					`z = -852643`

+ *Float* - Float, or "floating point number" is a number, positive or negative, containing one or scientific numbers with an "e" to indicate the power of 10. <br />
			*Eg*:  	```w = 0.205``` <br />
					```x  = -1524.526``` <br />
					```y  =  125e2``` <br />
					```z  = 125.256e25``` 

+ *Complex* - complex numbers with an imaginary part "j" <br />
			*Eg*:   `x = 256.3+2j` <br />
					`y = 152j` <br />
					`z = -489j`

<ins>**Type conversion**</ins> :

* If we want to convert one data type to another data type <br />
	*Eg*:	
```python
        a = 1 
        b = 25.6
        x = float(a) //float() - to covert integer to float 
        y = int(b)  //int() - to covert float to integer 
        z = complex(b) //complex() - to convert integer/float values to complex
        print(type(x)) //output - <class 'float'> 
        print(type(y)) //output - <class 'integer'> 
        print(type(z)) //output - <class 'complex'>
```
*Please note we cant convert complex values to integer or float.*

* If we want to select random number in the range of numbers <br />
	*Eg*:	
```python
			import random <br />
			print(random.randrange(1, 1000) //displays random numbers between 1 to 1000
```

*Casting* : If we want to change the data type the variable, we can use the constructor function. <br />
	
 + *int()*, this function will change the data type from float to integer, we can not change the string value to integer. <br />
		*Eg*: 	
```python
			x = int(10.05)
			print(x) //which display the value as 10
```
+ *float()*, this function will change the data type from integer to float, we can not change the string value to float. <br />
	*Eg*: 	
```python
			y= float(15)
			print(y)//which display the value as 15.0
```

+ *str()*, this function will change the value to string values, Integer literals or float literals <br />
		*Eg*:   
```python
			x= str(10) 
			y=str(16.3) 
			print(x)  //which display as "10" and which is not integer. 
			print(y)  //which display as "16.3" and which is not float value
```