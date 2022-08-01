# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation: "everyone should mind their own business"
Inheritance: "yes we're like our parents, but much more special"
Polymorphism:"to my mom, I'm a saint. To my spouse, I'm a nuisance. To my friends, I'm the Dungeon Master."
source(https://www.techelevator.com/the-3-pillars-of-object-oriented-programming-oop-brought-down-to-earth/)
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```js

staff[property]

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the bundling of data and the methods that act on that data such that access to that data is restricted from outside the bundle, or as Alan Kay describes it, “local retention and protection and hiding of state-process.” In OOP, that means that an object stores its state privately, and only the object’s methods have access to change it.

You can think of it in terms of maintaining proper scope, by managing access to code from sources which should or should not access that data you protect the data from unauthorized access, and you have a cleaner easier to debug interaction between your files.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single-responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a class is like a blueprint which is used to build objects with the same construction parameters. a single instance of a class is an object which matches those same criteria.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxies are Middleware for Javascript Objects.
Proxies allow you to provide custom functionality to basic operations that can be performed on an Object. From what I can gather, these open up a lot of customization for responding to access and edit requests on specified objects. It not only allows for denying access to certain objects, but it also allows customized handlers when allowing such access.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC organizes the increasing complexity of our app by assigning specific files to specific tasks, this makes it easier to read and edit code, it also provides layering to the controls of our app allowing more security and consistency with use
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller is where most functions are described and where the public functions are located to provide user access. the controller also stores the functions and listeners which we ant to run on pageload these go into the constructor
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
the service acts as an intermediary between the controller and the AppState through the Proxy. this provides a layer of security.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model describes the structure of a particular class of objects and stores information like the html that belongs to that class of objects
```
