# Objects, Classes, Variables, and Functions

This lesson will cover making objects and classes

# Review
## 📝 Questions
*Please handwrite out your answers to these questions. Answer to the best of your ability*
*Make sure to handwrite your answers, you'll learn it faster I promise*
1. What is an object?
2. What is a class?
3. What is a function?
4. What is a variable?
5. How do you initialize a variable in java?
6. In `public static void main(String[] args)` what does each word mean?
7. What is the difference between a static and non-static variable?
8. What is the difference between a static and non-static function?
9. What is a constructor?
10. Explain Inheritance
11. What does `Super` mean?

## 📖 Intro to Objects?


# Coding
## 🤖 Make an Object!

1. In BlueJ, open the `Intro-To-CS-Study-Guide/1` project
2. create a class called [your name] (make sure the first letter is capitalized)
3. write 3 functions in this class:
```java
    public String getName(){} // this function will return your name.
    public void printName(){} // prints your name
    public String introduce(String otherPersonName){} // returns "Hi [other person's name], I'm [your name]"
```
4. fill in these functions, so that they do the stuff
5. make a java object by right clicking your class<br>

	![make object picture](./images/make_object.png)<br>
give it a name<br>
	![name object picture](./images/name_object.png)<br>
run your functions on the object!<br>
	![object picture](./images/object.png)<br>

6. now make a `Person` class. This class should have one field called name, and a constructor that sets the name
7. Add in all the functions from the [Your Name] class. Rewrite them to work with the `this.name` field
8. Add another `introduce` function, this time it should take the argument `otherPerson` which will have a type of `Person`. This function should introduce `this` person to the other person
<br>Example in the BlueJ codepad:
 ```
>Person adam = new Person("Adam Alan Smith"); <br>
>Person lucas = new Person("Lucas");<br>
>adam.introduce(Lucas);<br>
Hi Lucas, I'm Adam Alan Smith <br>
```
<br>Example with objects:
> Create a Person object, with a name of instance as adam, and give it the name "Adam"
> Create a Person object, call it lucas, and give it the name "Lucas"
> right click on adam, and run the introduce function
> you should get a terminal pop up that says "Hi Lucas, I'm Adam"

9. Now you're going to make a third class called `SuperHero` which will extend Person
Think of extend like it's saying: "SuperHero is a type of person, who can do everything a person can, and more." 

10. SuperHero will have a field called heroName, which is their super hero alias. create this field.
11. Now you're going to make the constructor. This will take two arguments `(String name, String heroName)`. Fill in the constructor. <br>
> note: you should not have the line `this.name=name` in this constructor. Because SuperHero inherits from Person, you should figure out how to use `super()` to initialize name.
12. Override the introduce functions to print the hero's HeroName, not their person name. Make sure to add `@Override` above the functions to denote that you are changing what the function typically does.
13. Testing: make a SuperHero object for Spiderman.
what happens when you run `getName()` even though you never wrote a getName function?
make a person object. Can you introduce a person to a hero? what about a hero to a person.<br><br>
14. Try writing a `public string getRealName()` function that prints the SuperHero's real name without using `super.getName()`


## 🤖 Math 2: The squeakuel
Java has a class called math that is automatically imported into every project you make. To learn the difference between static and non-static variables and functions, we're going to make our own.

