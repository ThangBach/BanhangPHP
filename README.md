1.	Defining-Classes (Optional)
Define a class that holds information about a mobile phone device: model, manufacturer, price, owner, battery characteristics (model, hours idle and hours talk) and display characteristics (size and number of colors). Define 3 separate classes (class GSM holding instances of the classes Battery and Display).
Define several constructors for the defined classes that take different sets of arguments (the full information for the class or part of it). Assume that model and manufacturer are mandatory (the others are optional). All unknown data fill with null.
Add an enumeration BatteryType (Li-Ion, NiMH, NiCd, …) and use it as a new field for the batteries
Add a method in the GSM class for displaying all information about it. Try to override ToString().
Use properties to encapsulate the data fields inside the GSM, Battery and Display classes. Ensure all fields hold correct data at any given time.
Add a static field and a property IPhone4S in the GSM class to hold the information about iPhone 4S.
Write a class GSMTest to test the GSM class: 
Create an array of few instances of the GSM class.
Display the information about the GSMs in the array.
Display the information about the static property IPhone4S.
Create a class Call to hold a call performed through a GSM. It should contain date, time, dialed phone number and duration (in seconds).
Add a property CallHistory in the GSM class to hold a list of the performed calls. Try to use the system class List. 10.Add methods in the GSM class for adding and deleting calls from the calls history. Add a method to clear the call history. 11.Add a method that calculates the total price of the calls in the call history. Assume the price per minute is fixed and is provided as a parameter. 12.Write a class GSMCallHistoryTest to test the call history functionality of the GSM class. 
Create an instance of the GSM class.
Add few calls.
Display the information about the calls.
Assuming that the price per minute is 0.37 calculate and print the total price of the calls in the history.
Remove the longest call from the history and calculate the total price again.
Finally clear the call history and print it.

2. School management
We are given a school. In the school there are classes of students. Each class has a set of teachers. Each teacher teaches a set of disciplines. Students have name and unique class number. Classes have unique text identifier. Teachers have name. Disciplines have name, number of lectures and number of exercises. Both teachers and students are people. Students, classes, teachers and disciplines could have optional comments (free text block).
	Your task is to identify the classes (in terms of  OOP) and their attributes and operations, encapsulate their fields, define the class hierarchy and create a class diagram with Visual Studio.

3.HR management
 Define abstract class Human with first name and last name. Define new class Student which is derived from Human and has new field – grade. Define class Worker derived from Human with new property WeekSalary and WorkHoursPerDay and method MoneyPerHour() that returns money earned by hour by the worker. Define the proper constructors and properties for this hierarchy. Initialize a list of 10 students and sort them by grade in ascending order. Initialize a list of 10 workers and sort them by money per hour in descending order. Merge the lists and sort them by first name and last name.

4. Animal
Create a hierarchy Dog, Frog, Cat, Kitten, Tomcat and define useful constructors and methods. Dogs, frogs and cats are Animals. All animals can produce sound (specified by the ISound interface). Kittens and tomcats are cats. All animals are described by age, name and sex. Kittens can be only female and tomcats can be only male. Each animal produces a specific sound. Create arrays of different kinds of animals and calculate the average age of each kind of animal using a static method 

