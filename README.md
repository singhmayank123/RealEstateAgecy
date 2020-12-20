

A Real Estate Agency needs Management System that records the details about their offers: houses and apartments
In this project, you will be using object-oriented programming concepts and design in total four classes:

you will implement the following classes Residence, House, and Apartment. 

The following diagram shows the relationships between these classes you are required to implement.

 




Create a new java project, and add the following classes


Abstract Residence Class
A.	Implementation details of Abstract class: Residence 
Add and implement a class named Residence according the instruction in the UML diagram
-	Data fields: bedrooms, bathrooms, price, squareFeet, yearBuilt and address.
-	Constructors:
	A no-arg constructor that creates a default Residence.
	A constructor that creates a Residence with the specified bedrooms, bathrooms, price, squareFeet, yearBuilt and address.

-	Getters and setters for all the class fields.
-	calculateCommission() that returns the commission amount. The commission rate is set up at 2%.
-	toString() that returns the information about the current object( bedrooms, bathrooms, etc.).

Apartment Class
Add and implement a class named Apartment, a subclass of Residence class with the information in the UML class diagram:
-	Data fields: unit, floor and lot.  lot indicates the parking lot number
-	Constructors
-	Getters and setters methods
-	toString() that returns the information about the current object
-	Override calculateCommission() method. The commission rate for an apartment is set up at 3%.

House Class
Add and implement a class named House, a subclass of Residence class with the information in the UML class diagram:
-	Data fields: garage, stories, basement, and backyard.  basement and backyard are Boolean type, indicating whether the house has basement and backyard respectively.
-	Constructors
-	Getters and setters.
-	toString() that returns the information about the apartment.
-	Override calculateCommission() method. The commission rate for a house is set up at 3.5%.


A test program 

1.	In main method, create two lists:
List<House> houses = new ArrayList<House>();
List<Apartment> apartments = new ArrayList< Apartment >();

2.	Implement a method named menu() with no argument. This method should create the menu below and returns an integer indicating the user choice. 

 

3.	In main method, Invoke menu() method and store the retuned value in a new variable named choice
4.	Repeatedly do the following (use while):
Check the value of choice:
a.	If choice is 1, then:
-	Prompt the user to enter all necessary data about the house 
-	Create a house object. All data fields should be initialized.
-	Add this object to the list “houses” 
-	Display the menu by calling again menu() method.

b.	If choice is 2, then:
-	 Prompt the user to enter all necessary data about the apartment
-	Create an Apartment object. All data fields should be initialized.
-	Add the object to the list “apartments”
-	Display again the menu by calling menu() method

c.	If choice is 3, the loop ends and display “Thank you!” Message


  
