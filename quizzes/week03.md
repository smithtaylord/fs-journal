# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
  - Abstraction
  - Encapsulation
  - Inheritance
  - Polymorphism
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
```
staff.property
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is where you put your code within some parameters so other objects, functions, or the end user cannot access them. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S stands for Single Responsibility.  Basically that each class should only have one responsibility. 
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is basically a blueprint for creating an object and an instance of a class is the actual object. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is basically a middle man that stands between an original object and the code that it interacts with. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
It helps keep your code organized and on larger projects will help with debugging so you do not have to sift through thousands of lines of code all in one file. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes in the information from the user and directs that information to the service. It can also communicate with the "View" to throw errors, draw the page etc. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service handles the business logic for what ever function that the controller tells it to run. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model holds all the information and templates for the service and controllers to call on. 
```
