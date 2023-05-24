# If and Else statements
This lesson will cover if and else statments

# Review
## 📝 Questions
*Please handwrite out your answers to these questions. Answer to the best of your ability*
*Make sure to handwrite your answers, you'll learn it faster I promise*
1. What is an if statement?
2. What does the else statement do?
3. What is the purpose of an else-if statement?
4. Describe a case where and else-if statement might be useful

## 📖 Notes on if statements
An if statement is a programming statement that allows your code to execute a certain line of code only if a condition is true.

For example:
```
if(condition){
  // code to execute
}
```

## 📖 Notes on else statements
The else statement allows your code to execute a certain line of code when the condition of the if statement is false.

For example: 
```
if(condition){
  // code to execute if true 
} else {
  // code to execute if false
} 
``` 

## 📖 Notes on else-if statements 
An else-if statement is used when we want to check multiple conditions and run different pieces of code depending on which condition is true. 

For example: 
``` 
if(condition1){ 
  // code to execute if condition1 is true 
} else if (condition2){ 
  // code to execute if condition2 is true, but condition1 is not
} else {  
  // code to execute if all conditions are false 
}  
```

## 💬 Answers
1. An if statement is a programming statement that allows your code to execute a certain line of code only if a condition is true.
2. The else statement allows your code to execute a certain line of code when the condition of the if statement is false.
3. An else-if statement is used when we want to check multiple conditions and run different pieces of code depending on which condition is true. 
4. An else-if statement could be useful for a program that needs to sort items into different categories depending on its size. For example, we could use an if statement to see if an item is small, an else-if statement to check if it is medium, and finally another else statement for items that are large.

# Coding
## 🤖isEven

Create a program that checks if a number is divisible by 2. 

If it is, print "The number is even", otherwise print "The number is odd" 

write a `test.java` class to check if your answer is correct

## 🤖Starbucks size translator

I am constantly forgetting what starbucks sizes mean. I'll order a *tall* thinking I'm getting a large drink, and end up with the smallest sized drink. I need help. In this example, you're going to write a program to help me figure out the proper size to order.

fill in the following function:
```java
public static String translateStarbucks(String sbuxName){
    ...
}
``` 
This function will take a string of a starbucks size (in lower case) and output what that size actually means


```
size chart
________________________
short ==> extra small
tall ==> small
grande ==> medium
venti ==> large
trenta ==> extra large
```


