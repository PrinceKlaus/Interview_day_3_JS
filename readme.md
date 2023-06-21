## What are promises and why do we need them?
    - Promise are use to handle async operation in JS. easy to handle callback hell, also use to handle the error.
    - basically in promise there are Three stage
        1. Pending
        2. Resolve - (then method)
        3. reject - (catch mentod)
    - initial stage of any promise is always pending.
## Q - We have three promise, and we want to combine all then and catch method by using Promise.all.
## What is promise chaining?
    - its a technique to chain multiple asynchronous operation together using promises.
    - Promise chaining is a technique in JavaScript to execute multiple asynchronous operations in a specific order by chaining promises together using the then method
    - Multiple .then method.
## DOM - Document Object Model
    - Document object model. basically it is javascript mechanism by which we can change the document structure, style, and content.
    - DOM is the data representation of the objects that comprise the structure and content of a document on the web.
    - Different method in DOM
      - Id - getElementById - return unique value
      - querySelector -       return unique value
      - Class - getElementsByClassName
      - tag Name - getElementsByTagName
      - querySelectorAll
    - addEventListener - (event, callback function)
## Closure -
    - A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment).
    - Closure is the combination of two function (min).
    - inner function is able to excess the outer function variable but vise-varsa not possible.
    - outer func and inner func is going to create a Lexical environment.
## How many operators do we have in JS ?
    1. Arithemic operator
       1. Add, Sub, Multi, Div(/), Module (%), Expontial (**), increment ++, decrement--
    2. Assignment Operator
       1. Assign (=), Add Assign (+=), Sub Assign (-=), (*=), (/=), (%=)
    3. Bitwise Operator
       1. Bitwise OR (|), Bitwise AND (&), Bitwise NOT (~), Left shift (<<), right shift(>>)
    4. Comparision Operator
       1. equal (==), strict equal (===), Not equal (!=), Strict Not equal (!==), greate than, less than, greate than equal, less than equal
    5. Logical Operator
       1. AND (&&)
       2. OR (||)
       3. Not (!)
    6. Ternary Operator
       1. (Condition) ? "Execute True Condition" : "Execute False Condition"
    7. typeof Operator
       1. return datatype
## What are objects in javascript?
    - Non-premitive data type
    - store date in the form of Key-Value pair saparated by colon.
    - Key - Properties : Value