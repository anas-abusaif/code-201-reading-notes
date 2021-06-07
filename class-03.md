# HTML Lists, Control Flow with JS, and the CSS Box Model

<font size="5">HTML lists</font>

HTML lists allow web developers to group a set of related items in lists.

+ <font size="4"> ordered lists.</font>

```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
output:
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

+ <font size="4">unordered lists.</font>

```
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

```
output:
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<hr>


<font size="5">css boxes</font>

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:



![box model](https://codinglead.github.io/images/box-model.png)

<hr>

<font size="5">javascript decisions and Loops</font>

+ <font size="4">decisions</font>

if else statement.
```
if (condition)
{
  code to be executed if condition is true
}
else
{
  code to be executed if condition is false
} 
```
else if statement.
```
if (condition)
{
  code to be executed if condition is true
}
else if (condition)
{
  code to be executed if condition is true;
}
else
{
  code to be executed if condition is false
}
```
switch statement.
```
switch (value)
{
case value1:
  code to be executed if value = value1;
  break;  

case value2:
  code to be executed if value = value2;
  break;

default:
  code to be executed
  if value is different 
  from both value1 and value2;
}
```
+ <font size="4">loops</font>

for loop.
```
for (initialization; condition; increment)
{
  code to be executed;
}
```
while loop.
```
while (condition)
{
    code to be executed;
}
```
