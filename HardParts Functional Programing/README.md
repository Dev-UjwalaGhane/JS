## Function scope

```
Scope determines the accessibility of these veriables.
- Local function scope
- Global function scope

## Local Scope
- Variables declared within a js function.become a local to the function .
- cant accessible from outside the function.

## Automatically global
- if u assign a value to a variable that has not been declared .it will automatically become a GLOBAL variable.

```
myFunct();
function myFunc(){
    name = 'sandip ghane';
}

// name become a global variable automatically and can accessebile outside the myFunct function.