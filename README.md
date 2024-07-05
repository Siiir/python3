# 🌟 My Python3 Projects 🌟

Python2 was my first programming language to learn (~2018 AD). Around 2019/2020, I transitioned to Python 3.8 and started to create my own projects.

## 📚 Contents


<img style="float: right; width: 80px;" src="https://github.com/Siiir/Bernoulli/raw/master/Bernoulli_using_bernoulli.png"/>

### [🔢 Bernoulli](https://github.com/Siiir/Bernoulli)
My most **interesting** & **creative** calculator using **my own optimizations**. It performs **advanced math INCREDIBLY FAST** and is specialized in partial sums.


<img style="float: right; width: 80px;" src="https://github.com/Siiir/python3-drawing_algorithms/raw/stable/Dywan/Cover.png"/>
<img style="float: right; width: 80px;" src="https://github.com/Siiir/python3-drawing_algorithms/raw/stable/Mozaika/Cover.png"/>

### [🎨 Drawing Algorithms](https://github.com/Siiir/python3-drawing_algorithms)
Algorithms written for a competition in Computer Science. These solutions produce **complex geometrical shapes** using Python3's `turtle` library. The underlying procedures take different parameters to create various patterns.

### [🧮 Polynomials](https://github.com/Siiir/polynomials)
A library facilitating polynomial operations and display. The `polynomial` class inherits most properties of the `list` but is indexed differently. It also includes custom methods and overloads.

```
STATEMENTS:_______________________________________

Declaring polynomials.------------------
W= polynomial([9.64,9.6])
...declarations of Q, P...
R= polynomial()

Assigning & deleting--------------------
W[1]= 1; W[0]= 2
R.append(1)
R += [5,6]
R[::-1]= [4,5,6]
R.pop(1)
del R[0]
R.clear()

EXPRESSIONS:______________________________________
Expression          	Output

Q                   	2x³ +3x² +4x +5.0
W(10)               	12

-Q                  	-2x³ -3x² -4x -5.0
17.0 -P             	-x² -2x +16.0
Q -17.7             	2x³ +3x² +4x -12.7
Q -W                	2x³ +3x² +3x +3.0
Q*2.5               	5.0x³ +7.5x² +10.0x +12.5
Q*P                 	2x⁵ +7x⁴ +12x³ +16.0x² +14.0x +5.0
W/2.879             	0.3473428273706148x +0.6946856547412296
Q//3                	x² +x +1.0

Q.degree            	3
P.find_zero_places()	[-1.0]

P << 5              	x⁷ +2x⁶ +x⁵
[0,6] +P +[6,7,0]   	6x⁶ +x⁵ +2x⁴ +x³ +6x² +7x
[9] +Q              	9x⁴ +2x³ +3x² +4x +5.0
```