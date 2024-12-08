<h1>
  <span class="headline">Java Inheritance and Abstraction Lab</span>
  <span class="subhead">Exercise</span>
</h1>

## Exercise

Requirements

- Create an abstract class called `Vehicle` with the following properties:

  - `make` (string)
  - `model` (string)
  - `year` (number)
  - `color` (string)
  - `mileage` (number)
  - `price` (number)
  - `isRunning` (boolean)

- Create interfaces called `Maintenance` with the following methods:

  - `repair()`
  - `oilChange()`

- Create a subclass called `Car` that extends `Vehicle` and implements `Maintenance` with the following properties:

  - `numDoors` (number)
  - `numWheels` (number)
  - `numSeats` (number)
  - `isConvertible` (boolean)

- Create a subclass called `Truck` that extends `Vehicle` and implements `Maintenance` with the following properties:

  - `numDoors` (number)
  - `numWheels` (number)
  - `numSeats` (number)
  - `hasTruckBed` (boolean)

- Create a subclass called `Motorcycle` that extends `Vehicle` and implements `Maintenance` with the following properties:

  - `numWheels` (number)
  - `numSeats` (number)
  - `hasSideCar` (boolean)
