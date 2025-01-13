
# CSS Worksheet

## Problem 1
Explain the difference between these two selectors (make sure to mention the elements that each selector is targeting):
```css
ul li.selected{
	/*rules (property settings) go here*/
}


ul li .selected{
	/*rules (property settings) go here*/
}
```
### The first one is lis with the selected id tag.

### The second one is any element with the selected tag inside an li that is in a ul 



## Problem 2
What are **square brackets** used for in CSS selectors?
For example, what does the following selector target:
```css
input[type=text]{
	/*rules (property settings) go here*/
}
```
### to indicate specific tags that dont have any other way of identification.



## Problem 3
What is the **greater than** character used for in CSS selectors?
For example, what does the following selector target:
```css
div > p{
	/*rules (property settings) go here*/
}
```
### it has to be a direct decendint it cannot be within another element.



## Problem 4
What is the **tilde** used for in CSS selectors?
For example, what does the following selector target?
```css
h3 ~ p{
	/*rules (property settings) go here*/
}
```
### It has to be a direct relitive after said element.



## Problem 5
What is the **+** sign used for in CSS selectors?
For example, what does the following selector target:
```css
input[type=radio] + label{
	/*rules (property settings) go here*/
}
```
### It would have to immediatly fallow the first element



## Problem 6
Explain what a **psuedo selector** is in CSS.
And include a code sample that demonstrates a psuedo selector.
### they are used to select things that arent in the html alone for example

```css
li:hover
{
	/*rules (property settings) go here*/
}
```
### this only will do somthing if the element is hoverd over with the mouse.
