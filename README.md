# Javascript_Questions
---

## Q.1 Difference between "==" and "===" operator
These two operators are comparison operators which will basically return the boolean values. If the condition matches then they return true, else they return false.
### In case of  == 
  It will only check the values of the two variables.
### In case of  ===
  It will check the  values as well as the data type of both the variables.
  
If we want to find out the data type of any variable then we use typeof operator.

---
## Q.2 What is spread operator?
Spread operator looks like this …

It is used to destructure the iterable elements like objects and arrays.
So for example if you want to create and object whose value should be exactly same 

Let obj1 = {id:1, name: “Deepak”}

Let obj2 = {country: “India”, …obj1}

console.log(obj2)      //{country: “India”, id:1, name:”Deepak”}


---
## Q.3 Difference between var , let, const ?
These are three different ways of creating  or declaring the variables in the JS.
Out of these three var used to be a part of ES6 or ECMAScript2014 and let and const are the part of latest release of JS version i.e ES6.

Differences are :  

Var is the global scope variable

Let and const are local scope variable

At the time of memory allocation they will get their memory also at different location means var will be in global and let & const will be in script scope according to browser resulting in that if you will try to access var keyword variable.

---
