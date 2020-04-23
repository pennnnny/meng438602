

# Midterm2 MENG602/438

## Student's information

$-b \pm \sqrt{b^2 - 4ac} \over 2a$
 
<form id="percentageBiz" method="post">
<input type="text" id="name" placeholder = "Name">
<input type="text" id="nyitid" placeholder = "NYIT ID">
<input type="submit" onclick="return getp()" value="Generate Parameters"><br>
</form>

The question is for student: 
<div id="display" style="height: 50px; width: 100%;"></div>
<br>

<script>
function getp(){
    var a = document.forms["percentageBiz"]["name"].value;
    var b = document.forms["percentageBiz"]["nyitid"].value;
    //alert(a+b)
    var display=document.getElementById("display")
    display.innerHTML=a;
    display2.innerHTML=parseInt(b,10);
    display3.innerHTML=parseInt(b,10)*10;
    display4.innerHTML=1+parseInt(b,10)/1e8;
    display5.innerHTML=1+parseInt(b,10)/1e8;
    
    return false;
}
</script>
<script>
function show(){
 document.write("00");
 }
</script>

<script>
 document.write(a);
</script>


## Problem 1 
A set of simultaneous linear algebraic equations results: Ac=b<br>

**A** = 
<div id="display2" style="height: 50px; width: 100%;"></div>
<br>
**b** = 
<div id="display3" style="height: 50px; width: 100%;"></div>
<br>

(i)	Use the matrix inverse to solve for the **c**.<br>
(ii)	Find Euclidean norm of **A** and **A<sup>-1</sup>**<br>
(iii)	Calculate matrix condition number using Euclidean norms, and aslo determine how many suspect digits would be needed by solving this system with accuracy.<br>

## Problem 2 
Determine the solution of the simultaneous nonlinear equations<br>

![](images/table eq1.png, "eq1_0")
![](images/table eq1.png?raw=true)
![alt text](https://github.com/pennnnny/meng438602/blob/master/eq1.png "eq1")


Use Newton-Raphson method and employ initial guesses of <br>
_x<sub>1</sub>_ = 
<div id="display4" style="height: 50px; width: 100%;"></div>
_x<sub>2</sub>_ = 
<div id="display5" style="height: 50px; width: 100%;"></div>

<br>
(i) Write and calculate Jacobian matrix. <br>
(ii) Calculate x and y after first iteration and calculate ea (error). <br>


<input type="submit" onclick="return printpdf()" value="Print">
## Submission
Use above print bottom to save your exam sheet to pdf and upload with your solution to **Midterm2 Submission Box** in class's blackboard. Please submit your solution before 11:45pm April 30th 2020. 
<br>

<input type="text" id="pw1" placeholder="aceess code">
<input type="submit" onclick="return runsol()" value="Generate Solution">

<br>


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

``markdown
Syntax highlighted code block

# Header 1 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pennnnny/meng438602/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
