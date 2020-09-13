# Domain Modeling
### Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an *object-oriented* model.
## Define a constructor and initialize properties
### To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.
|Property|Data|Type|
|--------|----|-----|
|epicRating|1 to 10|Number|
|hasAnimals|true or false|Boolean|
### Here's an implementation of the EpicFailVideo constructor function.
![code](https://user-images.githubusercontent.com/70091044/93015271-c83a2080-f5c0-11ea-8358-5dcd103825b8.PNG)
### This is object-oriented programming in JavaScript at its most fundamental level.
#### 1- The *new* keyword instantiates (i.e. creates) an object.
#### 2- The constructor function initializes properties inside that object using the *this* variable.
#### 3- The object is stored in a variable for later use.
## Generate random numbers
### To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a Math.random() function for just this sort of occasion.
### The function uses both Math.floor and Math.random to calculate and return a random integer between min and max.

