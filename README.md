# carLot_A2B
<h3> Console application - Collections, Objects, Inheritance</h3>

Task: Hold information about Car inventory using a collection of Car objects, including a UsedCar subclass.

## What will the application do?:
<li>Display a set of at least 6 cars (at least 3 new and 3 used) along with Add and Quit options</li>
<li>Let the user select one of the cars.</li>
<li>Ask if they want to buy the car. If they enter yes, remove it from the list.</li>
<li>If they want to add another car to the list, get the details, instantiate a new car of the appropriate class (Car class for new cars, or UsedCar), and add it to your data collection.</li>
<li>Keep looping until they choose to quit.</li>
 

## Build Specifications:
<h3>1. Create a class named Car to store the data about a car. This class should contain:</h3>
<li>Data members for car details: </li>

<ul>
  <li>A string for the make</li>
  <li>A string for the model</li>
  <li>An int for the year</li>
  <li>A decimal for the price</li>
</ul>

<li>A no-arguments constructor that sets data members to default values (blanks or your choice)</li>
<li>A constructor with four arguments matching the order above</li>
<li>Properties for all data members</li>
<li>An override to the ToString() method returning a formatted string with the car details.</li>

<h3>2. Create a subclass of Car named UsedCar.  UsedCar has additional members:</h3>
<li>Data member: A double for mileage.</li>
<li>Constructor: Takes five arguments (same order as constructor from last lab with the mileage last).</li>
<li>ToString: overrides Car’s ToString() to include (Used) and the mileage.</li>

<h3>3. Discuss with your partner how a CarLot class could contain a member that stores the information. In what cases would each of these make more sense?</h3>
<li>A member that’s a two-dimensional array of cars</li>
<li>A member that’s a List<Car></li>
<li>A Dictionary <?, Car></li>
<li>Any other option?</li>
<li>However you store information inside the class, this class should include methods to:</li>

<ul>
  <li>Add a car</li>
  <li>List all cars to the console</li>
  <li>Remove a car</li>
</ul>

