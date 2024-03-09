Duck Simulator
This repository contains a simple Java program to simulate different types of ducks and their behaviors using object-oriented design principles.
The Duck Simulator program demonstrates the concept of polymorphism and encapsulation in Java. It features various types of ducks, each with different behaviors for flying, quacking, and swimming.

The program consists of the following classes and interfaces:

Duck: An abstract class representing a generic duck with fly, quack, and swim behaviors.
RedHeadDuck, RubberDuck, and MalardDuck: Concrete classes representing specific types of ducks with their respective behaviors.
FlyBehaviour, QuackBehaviour, and SwimBehaviour: Interfaces defining behaviors for flying, quacking, and swimming, respectively.
FlyWithWings, FlyNoWay, Quack, Squeak, Float, and Drown: Classes implementing different fly, quack, and swim behaviors.
Structure
The structure of the repository is as follows:

Main.java: The main class containing the main method to instantiate and test different types of ducks.
Duck.java: An abstract class defining the common properties and methods of all ducks.
RedHeadDuck.java, RubberDuck.java, and MalardDuck.java: Concrete classes implementing specific duck types.
FlyBehaviour.java, QuackBehaviour.java, and SwimBehaviour.java: Interfaces defining different behaviors.
Classes implementing various behaviors:
FlyWithWings.java, FlyNoWay.java: Classes for flying behavior.
Quack.java, Squeak.java: Classes for quacking behavior.
Float.java, Drown.java: Classes for swimming behavior.
