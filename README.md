# Optaplanner Hello 5 #

This project as written to be the exact mimimum necessary to get OptaPlanner up and running.

### Tight Coupling Makes Learning OptaPlanner Challenging, At Least To Slightly Dense Developers Like Me ###

Sometimes when a new technology comes along, it can be such a head scratcher, that a "See Dick Run" level of code is the easiest way to learn it. Something with just the basic semantics to just see how some technology works. The slightest extra details throw us off and confuse us, such as for example, extra UI, persistence, misc infrastructure.

The examples that come with OptaPlanner are brilliant, helpful, and necessary to understand what the possibilities of this technology can and does address. The code is excellent and helpful. But it is also so tightly coupled with the persistence and UI layers that it's really hard to figure out where OptaPlanner starts and the UI and persistence layers stop.

### OptaPlanner ###

* OptaPlanner is a unique project with many unusual paradigms
* The excellent example projects include so many moving parts it's hard to figure out the basic pieces of OptaPlanner
* [Learn OptaPlanner](https://bitbucket.org/tutorials/markdowndemo)

### What is this project? ###

* The exact minimum amount of code necessary to demonstrate how OptaPlanner code works
* Written in Java
* Uses a drools file for the OptaPlanner rules
* Has no persistence, UI, or related infrastructure to confuse you
* Does not even have tests - one main() method
* Excercises a single PlanningVariable, in a single PlanningEntity

### How To Use This Project ###

* Download code
* Run Maven
* Run HelloApp.main()

### What does this planner do? ###

* Sets the single PlanningVariable to 5
* Gives you a place to experiment with the drools file
* Gives you a place to start your own project without a UI or database

### Requirements ###

* Java
* Maven

### Extras ###

* This project will import directly as an Eclipse (Luna) project