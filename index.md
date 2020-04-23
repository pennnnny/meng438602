

# Midterm 2 MENG602/438
Date: April 30th 2020
Time: 5:45pm - 11:45pm

## Student's information
 
<form id="percentageBiz" method="post">
<input type="text" id="name" placeholder = "Name">
<input type="text" id="nyitid" placeholder = "NYIT ID">
<input type="submit" onclick="return getp()" value="Generate Parameters"><br>
</form>
<br>
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
    display6.innerHTML=1+parseInt(b,10)/10;
    display7.innerHTML=1+parseInt(b,10)/10;
    
    return false;
}
</script>

## Problem 1 
A set of simultaneous linear algebraic equations results: **A** x **c** = **b**<br>

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

![alt text](Images/eq1.png "eq1")

Use Newton-Raphson method and employ initial guesses of <br>
_x<sub>1</sub>_ = 
<div id="display4" style="height: 50px; width: 100%;"></div>
test<p id="display4"></p>test
_x<sub>2</sub>_ = 
<div id="display5" style="height: 50px; width: 100%;"></div>

(i) Write and calculate Jacobian matrix. <br>
(ii) Calculate x and y after first iteration and calculate f1 and f2 with updated x1, x2.<br>
(iii) Calcualte error of approximation, ea (error). <br>

## Problem 3
Application of Eigenvales and Eigenvectors
![alt text](Images/floor1.png "fr1")
Consider the mass spring model to gain insight into the dynamics of structures under the influence of disturbances such as earthquakes.
Above figure shows such a model for a two-stroy building. Each floor mass is represented by m<sub>i</sub>, and each floor stiffness is represented by k<sub>i</sub>, for i = 1 and 2. The frequencies for the mass vibrations can be determined by solving for the eigenvalues and by applying M_x<sup>"</sup>_ + _kx_ = 0, which yields

![alt text](Images/mx1.png "mx1")
Applying the guess x = x<sub>0</sub>e<sup>iω<sub>n</sub>t</sup> as a solution, we get the following matrix:
![alt text](Images/mx2.png "mx2")

where xi represent horizontal floor displacement, and ωn is the natural, or resonant, frequency (radians/s).

Let **_m<sub>1</sub>_** = **_m<sub>2</sub>_** = 
<div id="display6" style="height: 50px; width: 100%;"></div> (Kg)
and k = 
<div id="display7" style="height: 50px; width: 100%;"></div> (N/m)

(i) Use eigenvalues to solve for freqencies.
(ii) If mass of floors is unknown, based on the observation, the frequency is 1, what is possiblm m1 mass.

<input type="submit" onclick="return printpdf()" value="Print">
## Submission
Use above print bottom to save your exam sheet to pdf and upload with your solution to **Midterm2 Submission Box** in class's blackboard. Please submit your solution before 11:45pm April 30th 2020. 
<br>

<input type="text" id="pw1" placeholder="aceess code">
<input type="submit" onclick="return runsol()" value="Generate Solution">

<br>

