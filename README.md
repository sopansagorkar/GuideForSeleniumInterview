# GuideForSeleniumInterview
Automation Testing Interview Guide 

### 1)Why String is Immutable in Java?
```sh
Because java uses the concept of string literal.Suppose there are 5 reference variables,all referes to one object "sachin".
If one reference variable changes the value of the object, it will be affected to all the reference variables. 
That is why string objects are immutable in java
```
### 2)What is static in java?
```sh
static is a non-access modifier in Java which is applicable for the following:

1 .blocks
2variables
*methods
*nested classes
To create a static member(block,variable,method,nested class), precede its declaration with the keyword static.
When a member is declared static, it can be accessed before any objects of its class are created, 
and without reference to any object. For example, in below java program, we are accessing static method m1() without creating any object of Test class
```
