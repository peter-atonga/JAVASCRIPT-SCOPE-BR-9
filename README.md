 ### What is scope in JavaScript, and why is it important?
            scope =refers to the context or the environment in which variables are declared and can be accessed
                    -dectates lifetime of avariable and its visibility
                    -determines where in your code a particular variable is valid and accessible
                    - It helps in writting error free code

### Can you explain the difference between global scope and local scope?
                    - globa - refers to accessibilty of variable declared outside  of a localscope anywhere in the code
                    -local scope -refes to accessability of variable declared inside a function  or and block

 ### How does JavaScript handle scope in functions compared to block-level scope?
                    - When a variable is declared inside a function, it is only accessible within that function and cannot be used outside that function  while
                        a variable declared inside the  BLOCK (if or switch conditions or inside for or while loops), are accessible within that particular condition or loop.

 ### What are the implications of declaring a variable without any keyword (i.e., no var, let, or const)?

                    -It creates global variable -which makes code harder to understand and maintain or makes codes more difficult to read and debug


 ### What is the scope chain, and how does JavaScript use it to resolve variable access?

                    -scope chain refers to mechanism that javasScript uses to resolve variable reference 

                                        SCOPE CHAIN  PROCEDURES TO RESOLVE VARIABLE ACCESS IN JAVASCRIPT
                    Start with the Current Scope: The engine first looks for the variable in the current scope (the function or block where the variable is being accessed).

                    Move Up the Scope Chain: If the variable is not found in the current scope, the engine moves up to the outer scope and looks for the variable there.

                    Continue Up to the Global Scope: This process continues until the global scope is reached. If the variable is not found in any of the scopes along the way, a ReferenceError is thrown.


 ### What are some differences between lexical scope and dynamic scope? Which one does JavaScript use?

                    lexical scope

                    Its easy to find the scope by reading the code
                    It depends on code is written
                    Structure of program defines which variable is referred to

                    dynamic scope

                    The programmer has to anticipate all possible contexts
                    It depends on how code is excuted
                    Runtime state of programme stack determines the variables

            .JAVASCRIPT USES LEXICAL SCOPE.


 ### What is a closure, and how does it relate to scope in JavaScript?

                    -Is a function that retains access to the variables of a scope even when the fuction is excuted outside that scope
            
            .Javascript closures only comes into picture when the functions are nestled.