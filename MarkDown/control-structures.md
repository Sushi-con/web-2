# Control Structures
In Web 1 you learned about the following **control structures**:
1. IF Statements (and all of their variations)
1. While Loops
1. For Loops

Now you will explore the control structures that are listed below. 
For each one, write a brief paragraph that describes the control
structure and the situations when you would use it.
Also, include a fun and imaginative code sample that demonstrates 
the control structure.

## Switch/Case Statement
an alternative to if else statments but it cant have multiple peramiters

```js
const flavor = prompt("whats your favorit flavor");
switch(flavor)
{
  case("vanila"):
    alert("somthing about vanila")
    break;
  default:
    alert("could you try again i think there was an internet issue maybe an id 3 t error")
}
```

## For/In Loop
a for loop that loops through an object

```js
const object {name:"jerry", bread:"dog"}
    for(let key in object)
    {
      console.log(key);
      console.log(object[key]);
    }
```

## Conditional Operator (aka Ternary Operator)
conditional operator is an alternitive to an if else statment

```js
const age = 21;
alert(age>=21?"Your can drink!":"You can not drink")
```

