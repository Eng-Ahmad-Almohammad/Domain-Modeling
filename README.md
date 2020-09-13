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
![code1](https://user-images.githubusercontent.com/70091044/93015364-878ed700-f5c1-11ea-834d-3595e0808566.PNG)
## Calculate daily Likes
### Popularity of a video is measured in Likes. And the formula for calculating Likes is the number of viewers times the percentage of viewers who'll Like a video. In other words, viewers times percentage. To calculate the number of viewers per day, generate a random number between 10 and 30 and then multiply it by the epic rating of that video.
![code2](https://user-images.githubusercontent.com/70091044/93015452-506cf580-f5c2-11ea-9af0-b742a759534c.PNG)


