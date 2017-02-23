# Crib Sheet
Everything I need to know

## Javascript
### this
`this` is a binding that is made when a function is invoked. What it references is determined by the call-site.

`this` is calculated in the following order of precedence:

#### new binding
```javascript
var objectInstance = new ConstructorFunction();
```
#### Hard binding

## Typescript Diagramming
### Static Structure Diagrams - Object Notation
#### Objects
**Object**

|ObjectName|
|---|
| property: type |
| method(argument: type) : returnType |

**Class object and Abstract class objects**

|CObjectName|
|---|
| +publicProperty: type |
| -privateProperty: type |
| #protectedProperty: type |
| +publicMethod(argument: type) : returnType |
| -privateMethod(argument: type) : returnType |
| #protectedMethod(argument: type) : returnType |

For Abstract Class object prefix ObjectName with 'AC'.

**Interface object**

|IObjectName|
|---|
| property: type |
| method(argument: type) : returnType |

**Function object**

| ObjectName(argument: type) : returnType |
|---|

###Inheritance
|BaseClass| 
|---|         
|+setProperty(arg: string)|

  ^  
  |
 
|SubClass|    
|---|
|+setProperty(arg: string)|
|+setAnotherProperty(arg: number)|

The SubClass extends the BaseClass
