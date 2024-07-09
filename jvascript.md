### **Q-1** What is JavaScript How to use it?

**Ans.**   

    The JavaScript is a scripting or programming language that allows you to implement complex features on web pages.
    ==> Open your favorite browser (here we will use Google Chrome).
    ==> Open the developer tools by right clicking on an empty area and select Inspect.
    ==> On the developer tools, go to the console tab. Then, write JavaScript code and press enter to run the code. 

### **Q-2** How many types of variable in javaScript?

**ANS.**   

    There are three types of variables in JavaScript :let, var and const. 

    => let: A let variable can not be used a second time.
    but value can be changed.
    Example:- a = 30;
            let a = 30;
            a = 40;

    => var: var variable can be used repeatedly.
    Example:- b = 20;
            var b = 20;
            var b = 30;

    => const: const variable second time can not be used and not can the value be changed.
    Example:- c = 10;
            const c = 10;

    There are some rules while declaring a JavaScript variable. Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.

### **Q-3** Define a Data Types in js?

**ANS.**   

    The Data types are (Number, String, Boolean, Null and Undefined)

    => Number:- Represents numeric data, including integers and floating-point numbers.
    Example :- 10
            10.10
            101010

    => String :- Represents textual data, enclosed in single or double quotes.
    Example :- `jayesh`

    => Boolean :- Represents a logical entity, either 'true' or 'false'.
    Example :- true;
            false;

    => Null :- Represents any value equal of any object value and any value is right side to equal to left side.
    Example :- b = null;

    => Undefined :- undefined value is 'null' value equal (=). undefind present value is equal.
    Example :- c = undefined;

### **Q-4** Write a mul Function Which will Work Properly When invoked With Following Syntax.

**ANS.** 

    let mul = function (num1, num2) {
            return num1 * num2
        }
        console.log(mul(10, 10));
         
        Output = 100

### **Q-5** What the deference between undefined and undeclare in JavaScript?

**ANS.**   

    => Undefined :- A variable is "undefined" when it has been declared but has not been assigned a value.
    Example :- let x;
                console.log(x);

                Output = Undefined
    =>  Undeclared :- An "undeclared" variable is one that has been used without being declared using `var`, `let`, and `const`. Using an Undeclared variable will typically result in a `ReferenceError`.
    Example :-  console.log(y);

                Output =`ReferenceError` y is not defined



### **Q-18**    What is a Loop and Switch Case in JavaScript define that ? 

**ANS**

       ==> A switch is used to used in place of multiple if else statements and is time and memory saving. A loop is a repetitive statement which meets a set of defined conditions by the programmer.

        let loop;

        for (let i = 0; i < 16; i++) {
            console.log(i);
        };

          let day;
        switch (new Date().getDay()) {
            case 0:
                day = "Sunday";
                break;
            case 1:
                day = "Monday";
                break;
            case 2:
                day = "Tuesday";
                break;
            case 3:
                day = "Wednesday";
                break;
            case 4:
                day = "Thursday";
                break;
            case 5:
                day = "Friday";
                break;
            case 6:
                day = "Saturday";
        };

        console.log(day); -->


 ### **Q-19**    What is the use of is Nan function?

**ANS**

    => In JavaScript, the isNaN() function is used to determine whether a value is NaN.
    => This behavior is because NaN is not a valid number, and thus cannot be compared to any other value.

    let x = null;
    let y;

    console.log(x == y); Output = true

    console.log(x === y); Output = false 


    console.log(NaN == null); Output = false

    console.log(NaN == undefined); Output = false

    console.log(NaN == false); Output = false

    console.log(NaN == true); Output = false

    console.log(isNaN(NaN)); Output = true

    console.log(isNaN("hello")); Output = true 

    console.log(Number.isNaN(NaN)); Output = true

    console.log(Number.isNaN("hello")); Output = false  

    console.log(0 == false); Output = true

    console.log(0 === false); Output = false        


### **Q-20**    What is the difference between && and || in JavaScript?

**ANS**

    In JavaScript, && and || are logical operators used for boolean operations. 

    '&&' Logical AND 
    a=20, b=10, c=a, d=10

    console.log(a=c && a=b && b=d); False
    console.log(b=d && c=a && d=b); True

    (returns true if all true)

    '||' Logical OR

    console.log(a=c || a=b || d=b); True
    console.log(b=d || c=a || a=c); True

    (returns true if any true ) -->


 ### **Q-21**    What is the use of Void (0)? 

**ANS**

    In JavaScript, void is a unary operator that takes an operand and returns undefined. The expression void(0) or void 0 is commonly used to obtain undefined in situations where undefined might be redefined.


    var undefined = "this is not undefined";

    console.log(undefined); 
    "this is not undefined"

    console.log(void(0));  
    "undefined"



### **Q-66**    Find the length of a string without using libraryFunction?


**ANS**

        let myString = "Web Development Engineer";
        let length = myString.split('').length;
        console.log(length);

        Output = 24

### **Q-66-1**  What is JavaScript?

**ANS**

    JavaScript is a scripting language used to create and control dynamic website content.JavaScript is a Client Side Scripting and Programming language



### **Q-66-2**  What is the use of isNaN function?

**ANS**

    console.log(isNaN(123));     Output = false

    console.log(isNaN('hello')); Output = true


### **Q-66-3**  What is negative Infinity?

**ANS**

    In JavaScript, Infinity is a numeric value that represents positive infinity. It is a special value that is greater than any other number.

    On the other hand, -Infinity (negative infinity) is a numeric value that represents negative infinity. It is a special value that is less than any other number, including negative numbers.

    console.log(Infinity);    Output = Infinity
    console.log(-Infinity);   Output = -Infinity

    console.log(10 / 0);      Output = Infinity
    console.log(-10 / 0);     Output = -Infinity


### **Q-66-4**  Which company developed JavaScript?

**ANS**

    JavaScript was developed by Netscape Communications Corporation, specifically by Brendan Eich in 1995. Initially, it was called Mocha, but later it was renamed to LiveScript and then to JavaScript.


### **Q-66-5**  What are undeclared and undefined variables?

**ANS**

    =>  Undeclared and undefined variables are both related to variables in JavaScript, but they refer to different situations

    =>  Undeclared Variables:-
    An undeclared variable is a variable that has been used in code without being declared using the var, let, or const keyword. This is considered bad practice and can lead to unexpected behavior. When you try to use an undeclared variable, JavaScript will either create a global variable or throw a ReferenceError.

    Example =>
    => Undeclared variable
    Var = 10; 
    console.log(Var);
    Output= 10

    =>  Undefined Variables:-
    An undefined variable is a variable that has been declared but has not been assigned a value. When you try to access an undefined variable, its value will be undefined.

    Example =>
    let myVar;
    console.log(myVar);
    Output= undifined


### **Q-66-6**  Write the code for adding new elements dynamically?

**ANS**

    <!DOCTYPE html>
    <html>
    <head>
        <title>Add Element Dynamically</title>
    </head>
    <body>
        <ul id="myList">
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
        <button onclick="addElement()">Add Element</button>

        <script>
            function addElement() {
                let newItem = document.createElement('li');
            
                newItem.textContent = 'New Item';
                
                let list = document.getElementById('myList');
                
                list.appendChild(newItem);
            };
        </script>
    </body>
    </html>


### **Q-66-7**  What is the difference between ViewState and SessionState?

**ANS**

    ViweState =>
    =>  Is sent back and forth between the server and client, taking up bandwidth
    =>  Has no expiration date
    =>  Is useful in a Web Farm / Web Garden

    SessinState =>
    =>  Can be persisted in memory, which makes it a fast solution. Which means state cannot be shared in the Web Farm / Web Garden.
    =>  Can be persisted in a Database, useful for Web Farm / Web Gardens
    =>  Is Cleared when the session dies - usually after 20 min of inactivity.


### **Q-66-8**  What is === operator?

**ANS**

    => In javaScript the === operator is called the "strict equality operator" It compares two values for equality without performing any type conversion. it returns 'true' if the operands are equal and of the same type. Otherwise, it returns 'false'.

    Example :-
    a=20;
    b=10;
    c=a;
    d='10';

    ---Assignment Operator----
    console.log(c);     20

    ---equality Operator----
    console.log(a == b);    false
    console.log(b == d);    true

    ---strict equality operato----
    console.log(a === c);   true
    console.log(a === b);   false

    ---Typeof operator----
    console.log(typeof a); Number
    console.log(typeof d); string

    ----Arithmetic Operator----
    console.log(a + b);     30
    console.log(b - a);     -10



### **Q-66-9**  How can the style/class of an element be changed?

**ANS**

        You can change the style or class of an HTML element using JavaScript

        EXAMPLE:-
        document.getElementById("myElement").style.backgroundColor = "red";
        .classChange {
        background-color: yellow;
        }
        document.getElementById("myElement").classList.add("classChange");
        document.getElementById("myElement").classList.remove("classChange");
        document.getElementById("myElement").classList.toggle("classChange");


### **Q-66-10** How to read and write a file using JavaScript?

**ANS**

    The fs.readFile() and rs.writeFile() methods are used to read and write of a file using javascript. The file is read using the fs.readFile() function, which is an inbuilt method.

    Example :-
    fs.readFile( file_name, encoding, callback_function );

    The fs.writeFile() function is used to write data to a file in an asynchronous manner. If the file already exists, it will be replaced.

    Example:-
    fs.writeFile( file_name, data, options, callback );


### **Q-66-11** What are all the looping structures in JavaScript?

**ANS**

    The loops are types
    =>  for loop
    =>  while loop
    =>  do...while loop
    =>  for-in loop
    =>  for-of loop

    => for loop
    let result = 0;
        for (count = 1; count < 101; count++){
            result=result + count;
        };

        console.log(result);

        Output= 5050

    => while loop
    let result = 0;
        count = 0;
        while (count <= 100 ){
            result = result + count;
            count++;
        };
            console.log(result);

            Output= 5050

    => do....while loop
    let result = 0;
        let count = 0;
        do{
            result = result + count;
            count++;
        } while(count <= 100);

        console.log(result);

        Output= 5050

    => for-in loop
    numbers = [10,11,12,13,14,15];
        let result = 0;
        for (item in numbers);
        result = result + item;

        console.log(result);

        Output= 0012345


        numbers = [10,11,12,13,14,15];
            let result = 0
            for (item of numbers)
            result = result + item;

            console.log(result);

            output= 75

### **Q-66-12** How can you convert the string of any base to an integer in JavaScript?

**ANS**

    In JavaScript converting a string to an integer means transforming a string that represents a numeric value into an actual integer data type. This is useful when you need to perform arithmetic operations or comparisons on numeric values stored as strings.

    =>  parseInt( Value, radix )

    let a = "100";

    console.log("Type of a before conversion: " + typeof a);
    console.log("Type of a after conversion: " + typeof parseInt(a));

    Output= Type of a before conversion: string
    Output= Type of a after conversion: number

    Number( value )

    let age = "23";
    let name = "Dhiraj";

    console.log(
        "Type of name and age before conversion: ", 
        typeof age, typeof name
    );

    console.log(
        "Type of name and age after conversion: ", 
        typeof Number(age), typeof Number(name)
    );

    Output= Type of name and age before conversion:  string string
    Output= Type of name and age after conversion:  number number

### **Q-66-13** What is the function of the delete operator?

**ANS**

        const person = { name: 'Jayesh', age: 28 };
        delete person.age;
        console.log(person);

        Output= age deleted and name: 'jayesh' present

        // 2.Deleting Array Elements
        const numbers = [1, 2, 3, 4, 5];
        delete numbers[1];
        console.log(numbers);

        Output = [1,empty,3,4,5]


### **Q-66-14** What are all the types of Pop up boxes available in JavaScript?

**ANS**

    JavaScript has three kind of popup boxes:-
    => Alert box
    => Confirm box
    => Prompt box

    <!DOCTYPE html>
    <html>
    <head>
        <title></title>
    </head>
    <body>
            <button onclick="Alert('This is jayesh')">
                Show alert dialog
            </button>
            <button onclick="confirm('Are you sure')">
                Show confirm dialog
            </button>
            <button onclick="prompt('Enter your name')">
                Show prompt dialog
            </button>
            
            <script>
                alert('this is jayesh');
                confirm('enter Your name');
                prompt('enter your age');
            </script>
        </center> 
    </body>
    </html>


### **Q-66-15** What is the use of Void (0)?

**ANS**

    JavaScript void 0 means returning undefined (void) as a primitive value. You might come across the term “JavaScript:void(0)” while going through HTML documents. It is used to prevent any side effects caused while inserting an expression in a web page.

    <!DOCTYPE html>
    <html>
    <head>
    <title></title>
    </head>
    <body align="center">

        <h2>This is without using JavaScript:void(0)</h2>

    <a href="#" ondblclick="alert('Task completed!')">Double Click Me</a>

    </body>
    </html>


### **Q-66-16** How can a page be forced to load another page in JavaScript?

**ANS**

    In JavaScript, we can use window. location object to force a page to load another page. We can use the location object to set the URL of a new page.

    <button onclick="forceLoad()">Load</button>
    <script>
        function forceLoad() {
            window.location.href = "https://www.google.co.in";
        };

        function forceLoad() {
            window.location.replace("https://www.google.co.in");
        };

        function forceLoad() {
            location.assign("https://www.google.co.in");
        };
    </script>

        <li>Using window.location.href="link";</li>
        <li>window.location.assign("link")</li>
        <li>window.location.replace("");</li>


### **Q-66-17** What are the disadvantages of using innerHTML in JavaScript?

**ANS**

    It is very slow because as inner HTML already parses the content even we have to parse the content again so that's why it takes time. When we have used the event handlers then the event handlers are not automatically attached to the new elements created by innerHTML.

    <script>
        function Change()
        {
            let p = document.getElementById('demo');
            p.innerHTML = '<span>Hello World</span>';
        };
    </script>







