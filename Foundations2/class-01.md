## Template literals (Template strings) (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
<ul>
<li>template literals: template strings with expressions inside them.
<li>simpler way to concatenate strings and strings with variables or functions
<li>they start and end with back ticks and the variables or functions inside are enclosed-- `${variable or function}`
<li>to add a back tick inside the template literal, use \ then add the back tick
</ul>

## Getting Literal With ES6 Template Strings (https://developers.google.com/web/updates/2015/01/ES6-Template-Strings)

    //STRING
    // Simple string substitution
    let name = "Brooke Perkins";
    console.log(`Hello, ${name}!`);

    // Log: "Hello, Brooke Perkins!"

<ul>
<li>enclosed by backticks and can contain placeholders eg (${thisrighthere})
<li>expression in placeholder plus text between the backticks get passed to a function
<li>default function concatenates the parts into a SINGLE STRING
<li>with template literals you can have multi-line strings by using backticks which allows for more readable code
<li>string.raw to create raw strings
</ul>

<ul>
<li>can be done with math:</ul>
    let favNum1 = 13;
    let favNum2 = 6;
    console.log(`My two favorite numbers added together equals ${favNum1+favNum2}.`);

<ul>
<li>can be done with functions:</ul>
    function example() { return "Example example example"; }
    console.log(`HELLO ${example()} BYE-BYE`);
    //log: HELLO Example example example BYE-BYE

<ul>
<li>Can be done with methods:</ul> 
    let name = {myDog: 'Spot'};
    console.log(`My dog is ${name.favDog.toUpperCase()}.`);

    // log: "My dog is SPOT";

## Template Literals (https://css-tricks.com/template-literals/)
<ul>
<li>Template literals: can be multi-line by just entering down a line. 
<li>No need to type \n for a new line like with concatenation.

<li>eg:</ul>

    let exampleMultiString= `This will be
    on two lines!`;
<ul>
<li>COMPLEX OBJECTS too, look here:</ul>
    
    let person = {
        firstName: `Brooke`,
        lastName: `Perkins`,
        sayName() {
            return `Hi my name is ${this.firstName} ${this.lastName}`;
        }
    };
<ul>
<li>In the new Template Literal syntax we have EXPRESSIONS
<li>example:</ul> 
    let name = Ryan;
    console.log(Hi my name is ${name});
<ul>
<li>The ${} syntax allows us to put an EXPRESSION in it and it will produce the value </ul>

## ARRAY METHODS (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach) and (https://medium.com/@abustamam/for-loops-vs-foreach-in-javascript-7a977278a39e)
<ul>
<li>.forEach can replace the for loop
<li>can also take a callback</ul>

        //.forEach can replace for loops! See:
        const names = ['name1', 'name2', 'name3']
        const copyOfNames = []

        // With a for-loop:
        for (let i = 0; i < names.length; i++) {
            copyOfNames.push(names[i])
        }

        // with forEach:
        names.forEach(function(name){
        copyOfNames.push(name)
        })