# PolymorphismCompositionQuiz

Polymorphism
What does the word 'polymorphism' mean?

 		Many Forms 
    
What does it mean when we apply polymorphism to OO design? Give a simple Java example. 

		We can treat an instance of a class as if it is also another class/type at the same time.  So a Bedroom is a Bedroom but is also a Room as it inherits from the Room superclass.   
    
What can we use to implement polymorphism in Java?

		Using abstract classes and interfaces.  Interfaces allow us to treat a class as being of another type.  When a class implements an interface it gains the type of the interface.

How many 'forms' can an object take when using polymorphism?

		Many 
    
Give an example of when you could use polymorphism.

		When you use an array list and it can take in any type.  Eg. In the hotel model.  The hotel will have at least one diningRoom and at least one conferenceRoom and a number of bedrooms.  Rather than creating a seperate ArrayList for each we could just create one ArrayList of type Room since diningRoom, conferenceRoom and bedrooms all extend from Room superclass. This is called Parametric Polymorphism.  

	 

Composition

What do we mean by 'composition' in reference to object-oriented programming?

		An object being made up of/composed of other objects. 
    
When would you use composition? Provide a simple example in Java.

		To establish relationships between classes.
		eg.  In the Hotel homework we had a number of classes.  Hotel, Room, Bedroom, DiningRoom, ConferenceRoom
	⁃	Hotel has a Room
	⁃	You couldn’t say a Room has a Hotel
	⁃	So since we can know the hotel has a room , then room will be a property of the Hotel class.

What is/are the advantage(s) of using composition?

		Allows a class to use behaviours from a group of other classes. 
    
What happens to the behaviours when the object composed of them is destroyed?

		They are destroyed also
