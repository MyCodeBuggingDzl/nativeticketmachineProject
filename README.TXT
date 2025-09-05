Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

Anwsers of Part 2:

2: The balance is 0 atfer the ticket machine has printed a ticket.
3: Whenever I add too much cents or when I didn't put enough, the balance shows 0 and when I print the ticket, it thinks i put the right amount. Also, you do not recieve any refund. 
5: The price of the ticket changed.
6: public class Student
{

}
   public class LabClass
{

}
7: When we write "public class TicketMachine" there's no errors, however if we write "class public TicketMachine" the source code will be full of errors.
8: It's possible to leave out the word "public" from the outer wrapper.
9: Removing the word "class" brings out errors.
10: Field: private int price;
           private int balance;
           private int total;
   Constructors: public TicketMachine(int cost)
   method: public int getPrice()
           public int getBalance()
           public void insertMoney(int amount)
           public void printTicket()
11: Initialize an object and have the same name as thier class.
12: - int
    - Student
    - Server
13: - alive
    - tutor
    - game
14: - Person
    - Student
    - Server
    - Game
15: The order of the words matter, otherwise it will be an error
16: Yes, because a semi colon indicate the end of the statement.
17: private int status
18: Student
19: It has 2 parameters and it's string type.
20: Yes
21: public Pet(StringpetsName)
    {
       name=petsName;
    }
22: public Date(int day, int month, int year)
23: The method name and the return statement are different.
24: How much money does it have?
25: It doesn't have to be the same.
26:/**
     *  Return the value of the total field
     */
    public int getBalance()
    {
        return balance;
    }
27: I get the ';' expected error.
28: printTicket is a type void while getPrice is a type int.
29: No, because they're type void.
31: /** 
    * Increase score by the given number of points.
    */ 
     public void increaseScore(int points)
   { 
       score = score + points; 
       // TODO: Increase score by the value in points. 
   }
32: Yes, it changes the value of an object. For exemple, we add 3 credits to a student who has 0 credit.
Credits before: 0
Credits after: 3
33:/** 
   * Reduce price by the given amount. 
   */ 
     public void discount(int amount) 
{
    price = price - amount;
 // TODO: Subtract amount from price.
}
34: public void setAge(int currentAge)
    {
      age = currentAge;
    }
35: public class boolean Alive()
    {
      private int boolean setAlive;
    }
36: When i click on int getPrice it shows 0 and when i add a certain amount of money to the ticket machine and printed out the ticket, the ticket shows 0 cents
37: My cat has green eyes.
38: Added the prompt method.
39: It will print out "# price cents."
40: It also printed out "# price cents."
41: Added showPrice
42: When I call the showPrice method the price of both ticket machine are different. The method, showPrice, is used to create an output of the desire ticket machine.
43: No, the statement isn't the same as before. This time it only shows the price and the cents. %d means to insert the next argument as a int value and %n means end of line.
44. You have to pay 1000 cents for a ticket. If I create the ticket machine and put 7 cents for a ticket. The 1000 cents will overwrite the 7 cents.
45: It shows both specified price and the default price.
46: No, it doesn't need any parameters, the balance will always be 0.

