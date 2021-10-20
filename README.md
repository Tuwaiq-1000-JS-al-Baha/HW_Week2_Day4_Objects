# HW_Week2_Day4_Objects

### Exercice 1: Modeling a Run Tracker

Create an object `person` that has methods that helps
him prepare for running a 5k.

And the `person` can perform some calculations:

- total distance run of all runs
- longest run distance 
- average speed of all runs

Each day that a person runs, they create a
record of their run which contains:

- the date and time of the run
- the distance covered, in meters
- the time taken, in seconds

The `person` object also stores information about the person
- person name 
- person email
- person address


### Hints:
* The person has runs.
* He can do calculations based on **his** runs.
* We will use the program like this:
```js
const person = {
  ...
}
person.longestRunDistance() // outputs the longest run based on his runs **property**
person.totalDistance() // outputs the total distance covered based on his runs **property**
person.averageSpeed() // outputs the average speed based on his runs **property**
```
