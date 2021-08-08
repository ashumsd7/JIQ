# JIQ
## 🎯My Interview Prepration🎯
JIQ stands for JavaScript interview questions. Here I cover some topics and I update some question after searching from some sources that can help us to prepare for the war named JavaScript Interview. Happy Leraning

## 📌Day 11
### 📝Topics:Recursion and stackRest parameters and spread syntax Variable scope, closure


#### Q111: What is recursion?
#### Q112: What is meaning of execution context or call stack?
#### Q113: Why do we use Object.assign?
#### Q114: How many ways you can copy from one Object to another?
#### Q115: How many ways you can copy from one array to another?
#### Q116: What are closures?
#### Q117:Give me an example of closure? or just explain closure with this example
    function x(){
        var a = 7;
        function y() {
        console.log(a);
        }
     y()
    }
    x();
#### Q118:Tell me some real usage of closures? 
#### Q119: What is lexical environment?
#### Q120: Can you show me how closures are created in 

## 📌Day 10
### 📝Topics: Object.keys, values, entries Destructuring assignment Date and time JSON methods, toJSON


#### Q91: I want to use an iterable method of an array like map/reduce with an Object . How is it possible?
#### Q92: What do you mean my Array Destructuring?
#### Q93: what will be the output?
        let [user1, user2, , user3] = ['sam', 'ram', 'dam', 'cam']
        console.log(user1,user2,user3);
#### Q94:Swap two values using Destructuring!
#### Q95: How will you set default values in Destructuring?
#### Q96: Calculate date 5 days before of today.
#### Q97:Why JSON is used? tell me full form of it?
#### Q98: what are some restrictions on JSON?
#### Q99: what are receier in JSON.parse() method.
#### Q100: Do you know about JSON5?
## 📌Day 9A
### 📝Topics: Arrays Array methods   IterablesMap and Set WeakMap and WeakSet

#### Q90A: revserse this string 'javascript' 
#### Q90B: When sort() fails in order to sort array elements?
#### Q90C: Find average of all elements using best array method?
#### Q90D: Can you name of some Iterables?
#### Q90E: What is use of Symbol.itearor() ?
#### Q90F: What will be the output?
    let map = new Map();
    console.log(map.get('village'));
#### Q90G: does Map allows duplicate keys?
    1)yes    2) no    
#### Q90H:does Set allows duplicate keys?
    1)yes    2) no    
#### Q90I:What will be the output? 
    let set = new Set();
    set.add('ashu')
    set.add("loves");
    set.add('ashu')

    console.log(set.size);

console.log(set.size);
#### Q90J: Can you give me any use case of WeakSet and WeakMap?

## 📌Day 9
### 📝Topics: Arrays Array methods   IterablesMap and Set WeakMap and WeakSet





#### Q81: Which method works more push() or unshift(); which is more fast?
#### Q82: What are array like objects? Any examples?
#### Q83: what will happed if you do!
    let arr = [1, 2, 3, 4, 5];
    arr.length=2;
    console.log(arr);
#### Q84: What is difference between for in and for of loop?
#### Q85: What will be the output of 
    let arr =[1,2,3,4,5,6];
    arr.splice(0)
    console.log(arr)
#### Q86: What fill find() method return if element is not found?
#### Q87: Can you specify when to use filter() and find()?
#### Q88: When will you use slice method?
#### Q89:Which array method is called all-rouder method, which does deletion, insertion both.
#### Q90: Just tell me use of spilit() and join() !
#### Q90A: revserse this string 'javascript' 
#### Q90B: When sort() fails in order to sort array elements?
#### Q90C: Find average of all elements using best array method?
#### Q90D:

## 📌Day 8
### 📝Topics:Methods of primitives Numbers Strings Arrays Array methods


#### Q71: How mnany primitive data types are in javascript. Name ?
#### Q73: if strings are primitive types in javascript not an object, then as we know there are many methods available for strings , how that possible? are strings internally objects?
#### Q74: typeof new Number(0) ?  
    a) boolean b) number   c) object
#### Q75: What are wrapper objects in javascript?
#### Q76: prove that primitive types have some methods to execute but they are not objects i javascript!
#### Q77: Output of alert(parseInt("abc"));  ?
    a) ASCII value of abc  ) error   c)NaN    d)parseInt("abc")  will show in alert
#### Q78:How will u store multiple lines string in a string variable?
#### Q79: I want to show string in multiple lines but I also want to use " double quotes to store a string. Is it possible?
#### Q80: what is meaning of "Strings are immutable" in javascript?


## 📌Day 7
### 📝Topics:Constructor, operator "new" Optional chaining '?.' Symbol type Object to primitive conversion

#### Q61: What is main advantage of using Object Constructors in javaScript?
#### Q62: Generally Constructor function doesn't has return statement. What will happen If we place return statement inside Constructor?
#### Q63: WHat is Object chaining?
#### Q64: Can we user a boolean as a key of an Object?
#### Q65: 
#### Q66: 
#### Q67: 
#### Q68:
#### Q69:
#### Q70: 
----------------------------------------------------
----------------------------------------------------
## 📌Day 6
### 📝Topics:Objects Object references and copying Garbage collection Object methods, "this"




#### Q51: 
    let  person = {
    'full name' :  "Twitter Kumar",
             age: 20,
        }
    // totally valid syntax
     but now, how can we access full name propertyRed question mark ornament
      console.log(person.full name)   //gives error 
#### Q52: 
    let obj={
    name:"ashu",
     age:20,
    return :0
    }

As we have used return keyword as key of Object obj  which is reserved by javascript 
any error?
#### Q53: What is meaning of objects are stored and copied “by reference"?
#### Q54: What is use of Object.assign?
#### Q55: We are changing the property of a constant Object! what will be the output?  and why? if error ? tell the reason.
#### Q56: is it possible to prevent Garbage collector to collect unreachable code in javascript? if yes How?
#### Q57: 
#### Q58:
#### Q59:
#### Q60: 
----------------------------------------------------
## 📌Day 5
### 📝Topics: Debugging in the browser Coding Style Comments Ninja code Automated testing with Mocha Polyfills and transpilers



#### Q41: What is Debugging?
#### Q42: Have you heard about Prettier ? What is it? 
#### Q43: What are Transpilers? Tell me in brief?
#### Q44: Tell me name of any Transpilers?
#### Q45: Difference between Polyfills and Transpilers?
#### Q46:
#### Q47: 
#### Q48:
#### Q49:
#### Q50: 
----------------------------------------------------
## 📌Day 4
### 📝Topics: Functions Function expressions Arrow functions, the basics JavaScript specials


#### Q31: difference between functions and methods?
#### Q32: What is variable shadowing?
#### Q33: what will be the value if I stroing returned value from a function and that function is has only return;  
#### Q34: What are callback functions?
#### Q35: What is main difference function declaration and function expressions?
#### Q36: Write an arrow function expect two values and return sum. and try to write less statement? 
#### Q37: 
#### Q38:
#### Q39:
#### Q40: 

## 📌Day 3
### 📝Topics: Basic operators, maths Comparisons Conditional branching: if, '?'Logical operatorsNullish coalescing operator '??'Loops: while and forThe "switch" statement

#### Q21: NaN == NaN
#### Q22: undefined == null

#### Q23: What is the way to convert a non boolean value to a boolean value?
#### Q24: || OR operator and ?? operator Nullish act as almost same, what is the main difference?
#### Q25: Main difference between while and do while?
#### Q26: What will happe If I place default; of switch statement in between cases not at the end?
#### Q27: 
#### Q28:
#### Q29:
#### Q30: 

----------------------------------------------------
## 📌Day 2
### 📝Topics: Hello World, Code structure, strict mode, varibales, alert prompt, type conversion
#### Q11: What will be the output?
    <script src="file.js">
       alert(1); 
    </script>
#### Q12: What wil be the output? Tell thereason too!
    alert(3 +
    1
    + 2);

    a) Error  b)  312 c)6

#### Q13:  output with reason?

alert("Hello")

[1, 2].forEach(alert);

#### Q14:Can we cancel 'strict mode' in run time?
#### Q15: Which case is preferred  while writing  JavaScript code?
#### Q16: output?
    num = 5; 
    alert(num);
#### Q17: What is difffernce between premitive and refrenced type in JavaScript?
#### Q18: Symbol is premitive or refrenced type , data type in JavaScript?
#### Q19:Do you know about typeof operator?
What will be the output of typeof null;
#### Q20:difffernce between implicit and explicit type conversion?  
-------------------------------------------------------

## 📌Day 1
### 📝Topics: Intro to JavaScript , Code Editors, Manuals and specifications and  , Developer console

#### Q0️⃣ Who developed JavaScript ❓
#### Q1️⃣ Is there any alternative of JavaScript ❓
#### Q2️⃣  List some disadvantages of JavaScript ❓
#### Q3️⃣  What is role of JavaScript Engine ❓
#### Q4️⃣  List out some points JavaScript can't do while running in web browser ❓
#### Q5️⃣  What is the latest version of JavaScript? ❓
#### Q6️⃣  What is an IDE? Can you name some IDEs, which you use and why ❓
#### Q7️⃣  What is Developer tools ❓
#### Q8️⃣  What is first name of JavaScript ❓
#### Q9️⃣  What is full form of ECMA ❓

