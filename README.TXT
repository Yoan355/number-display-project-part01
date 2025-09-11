Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.
 



//////////////////AWNSERS TO QUESTIONS///////////////////////


1: Class diagrams are shown 
as blueprints of classes and their relationships,they are persistent,they
are saved
while object diagrams are shown as little pictures of the object on the object
 bench.They are not saved.
Class diagrams focus on the structure of classes such as attributes or methods
 while object diagrams focus on object values.For example LabClass has a method that it can call named
enrollStudent (class diagram) and lab1 enrolls student1, student2, student3 (object diagram)



2: In real life applications, a class diagram can change when you create classes,
when fixing bugs during 
testing, or when stakeholders communicate with developers ordering
them to modify their structure to their liking.



3: An object diagram can change after we run our system,they can be destroyed
and when we change relationships and create new objects.



4: private Instructor tutor;




6: When calling increment on minutes, I should be counting every time I click
increment until I get to 60,then I will know the numbers have rolled over to
to 0 and then I should call increment on the hours object to make the clock
advance by 1 hour.



8: After setting the value to a number less than the limit
for example 2,it's getValue call returns 2.After we setValue
to a number greater than the limit for example 11,
calling it's getValue still returns 2.Since it was greater
than the original limit of 2, the method ignored the input
and kept the original value.It's an abstraction.



10: Error: non-static method getValue() cannot be referenced from a static context


  
11: Error: '.class' expected. We need to identify the class to
be able to call the method setValue. 




13: The only valid parameter is 0 because it does work for 0>=0
but noy for 0 > 0.



14: Changing && (AND) to || (OR) makes our conditions much looser.We do not 
have a small  amount of choices for our replacementValue anymore 
(replacementValue>= and replacement value < limit) we are basically saying 
as long as both aren't negative and really big numbers over the limit it 
will be set the field.



15: 2 & 5.



16: (a && b) || (!a && !b)


17: a ^ b



18: When I called the setValue method with the value 100,then called
getDisplayValue,it showed me 100 too.No it was not a two digit
string.





19: There is no difference in the result of writing.




20: Yes they did suprise me,I thought both would give the same
awnser except for the placement of the word cat.Java reads expressions left to right and as soon as it sees a string,
 it switches to string mode.So in expression 1 we see that math happens first, then string.
 In Expression 2, string happens first so everything gets glued together as text.







