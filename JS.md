# JavaScript Algorithms and Data Structures

## Basic JavaScript
**>JS comments syntax:**
```
// This is a single line comment
/* This is a multi-line comment */
```
**> 8 datatypes in JS - string, object, number, boolean, null, undefined, bigint, symbol**
```
Any variable without a value defined or assigned is undefined and null is the assignable value used to assign to variables with no value.
Typeof undefined is undefined but type of null is object even though null is a datatype/primitive type.
undefined == null is true
undefined === null is false
Operations on undefined gives NaN (Not a Number) and concatenating a string to undefined gives a string with undefined concatenated to it.
Objects are mutable, const variable are immutable. (strings?)
```
**> Var vs Let**
```
var doesn't throw an error when you redeclare the same variable or you can say that var allows you to overwrite the variable declarations and this can cause errors or bugs in your codebase when you may unintentionally override a variable. Let doesn't allow you to redeclare the same variable.
```
