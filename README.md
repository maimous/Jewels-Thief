# Jewels Thief
[Head First C#](http://www.headfirstlabs.com/books//hfcsharp/)

&nbsp;
## 00 Start the project
* In VS, create a Windows Forms Application project.

&nbsp;
## 01 Add the classes and the main method
* Now the thief is returning the jewels since it hides the Locksmith's inherited method ReturnContents.

&nbsp;
## 02 Use the `new` keyword for intended hiding
* Add the `new` keyword in the JewelThief's class ReturnContents declaration so that the warning stops. The program has the same output as before, the hiding remains.

&nbsp;
## 03 Use the `virtual` and `override` keywords 
* In order to have the Locksmith's ReturnContents method overriden for the thief, the `virtual` keyword has to be used in the Locksmith's class, as well as the `override` keyword in the JewelThief's class.
