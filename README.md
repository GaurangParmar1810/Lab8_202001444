# Lab8_202001444

## Name: Gaurang Parmar

## Student ID: 202001444

## Lab No: 8

## Date : 21-04-2023

## Topic : Unit testing with JUnit


1. I created a new Java project in eclipse with name <b>Lab8</b> and created a package inside it with name <b>mypackage</b>

![1](https://user-images.githubusercontent.com/97961910/233603008-da83e3c5-e9b6-4577-8c8b-464abab2b7e6.png)


2.I then created a class with name <b>Boa</b> and then added the given code inside it.
![2](https://user-images.githubusercontent.com/97961910/233603065-8dd5e76a-631a-4ea8-819d-6596431ce0d9.png)

3.Then I created a JUnit test file for the Boa Class with name <b>BoaTest</b>
![3](https://user-images.githubusercontent.com/97961910/233603100-1679e5b8-9c68-47bb-968e-05b7a603b063.png)

4.Then I modified the setUp method to initialize the variables.

5.Then I also implemented tests for the given two functions <b>testIsHealthy()</b> and <b>testFitsInCage()</b>.
![4](https://user-images.githubusercontent.com/97961910/233603174-21741b1f-b956-408f-bf8f-352dbc8380a9.png)

It is not necessary to develop tests for both ken and jen objects in order to test the fitsInCage() method because the function is the same for both, and the results of test cases depend only on whether the specified length is greater than, less than, or equal to the actual length of the object.In both situations, the behaviour will be comparable.

6.Then I ran the Junit test file and all the tests are passed.There are no red bars in the output.
![5](https://user-images.githubusercontent.com/97961910/233603241-bbc6258a-3a47-45a1-aebb-3338772386fd.png)

It can be seen that 2 out of 2 test cases have been passed. 

7.Then I added a new method to the Boa class with name <b>lenghtInInches()</b> to get the length in inches.
![6](https://user-images.githubusercontent.com/97961910/233603424-433857d4-bd53-4b3d-b027-b529fca1f886.png)
The Boa's length is specified in feet, so I multiplied length by 12 to convert it to inches and then returned the result.

8.Then I wrote another test case for this new method and ran the 3 test cases together. 
![7](https://user-images.githubusercontent.com/97961910/233603487-6c89dab8-8529-414f-a499-89b2fa7a7eb6.png)
As a result, test cases have been created for the specified Boa class, and the necessary Junit test cases have been used to test all three methods.
