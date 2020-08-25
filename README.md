# _Address Book_

#### _A web application that will take take in user input and save the data in objects. Created 8.25.20_

#### By _**Chloe Hellberg and Garrett Brown**_

## Description: Behavior Driven Development/Spec

* This application is used to practice objects. User will be able to enter contacts into an "address book". Once they are added to the address book you can then click on each contact and see more information about that contact.


## Setup/Installation Requirements

* _Clone the application to your desktop_
* _Open index.html in your preferred web browser_
* _Add input to the form and see data saved to the address book on the page_

_Please note: This requires a desktop and a web browser to run._

## Known Bugs

_There are no known bugs at this time._

## Support and contact details

_If you run into issues, please email chloe.hellberg@gmail.com with questions or concerns. Feel free to contribute to this code._

## Technologies Used

_This application utilizes HTML/CSS, Bootstrap, JavaScript and jQuery._

### License

*MIT License*

Copyright (c) 2020 **_Chloe Hellberg and Garrett Brown_**




-Add functionality to record and display a contact's email address
-Add functionality to record and display a contact's physical address
-

-What is a contructor? What is a prototype?
  
  -A constructor is a function that can be invoked using the "new" keyword
  to create new objects
  -Good practice to name constructor functions with an upper-case first letter
  -A constructor is a blueprint that specifies how to create an object
    -i.e. let testGreeting2 = new String("Hello!);
    -i.e. function Dog(name,colors,age) {
              this.name = name;
              this.colors = colors;
              this.age = age;
               }
        Then to create a new dog, we can do the following:
            let myPuppy = new Dog("Ernie", ["brown", "black"], 3);
  
  -A prototype is just an object from which other objects inherit methods
    -i.e. String.prototype.addExcitement = function() { return this + !!!!" };
  -All JavaScript objects inherit properties and methods from a prototype


-When would you use a Constructor, and when would you use a Prototype?
  -You will use a constructor when you want to create a "blueprint" for an object you want to create
  -You will use a prototype when you want to create a method and call it on your objects. Or, I guess
    it is an object and you are creating (that has a function) and can be called on your other objects if you want to do something with them.


-The this keyword
  -The things called this is the object that "owns" the code
  -The value of this, when used in an object, is the object itself
  -In a constructor function this does not have a value. It is a substitute for the new object. The value of this will become the new object when a new object is created