# U6S3 - Constructors

* Part A - Foundations 7.3
* Part B - Foundations Practice
* 
## Part A

### Exercise 01

#### Step 01

In the package `partA.ex01` look at the file `PlayerTest` 

#### Step 02
* Investigate what happens when fields are accessed
before they’re assigned values
  * Instantiate a Player
  * Try printing the value of each field

#### Step 03
* Can fields be set more efficiently?
  * Add a setFields() method to the `Player` class
  * This method should take three arguments, which are used to
  set the values for every field
  * Replace code in the main method with calls to this method

#### Step 04
* Continue editing with the `PlayerTest` class
* Copy the constructor into the `Player` class
  * Run the program
  * Observe how the code in this method is executed when
  Player objects are instantiated

```
//Constructor
public Player(){
System.out.println("This is a constructor");
}//end constructor

```
#### Step 05
* Modify the Player constructor
  * Change the parameters of this method so that each
    parameter’s name matches the name of a field
  * Set each field’s value by using the this keyword

## Part B

### Exercise 01

#### Step 01

In the package `partB.ex01` look at the file `ConstructorExample` and write comments for each line of code. When complete review with instructor.

#### Step 02

In the package `partB.ex01` complete the `Constructor` per the following:

* Create a program with an empty string called name
* Create a constructor for the class that prints a line stating that the constructor is being called.
* Ensure that you are also re-assigning the name string to your own name within the constructor
* Inside of the main method, create an instance of the class that has the constructor
* Accessing the name variable inside of the newly created instance (. operator) print out the name

Your program is working correctly, if when run, the following is the output (Abe first name Lincoln last name):

```
The constructor is being called:
The name is Francis

```

> Use ConstructorExample for reference.

