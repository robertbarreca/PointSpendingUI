Fetch Rewards Take Home Test

This project reads transaction data from a .csv file. The user can then submit an integer requesting the number of points they want to spend through the command line. Then from the transactional data read in from the csv file, the user will first spend points from the oldest transactional data first to the newest transaction. After the all the transactions have been completed, the program will then print out to the user the current number of points each company has remaining.  

Languages Used: Java

Java is the language I picked for the entirety of this project. I decided to go with Java because even though at times the syntax might be a bit lengthy, it is an object-oriented language. As a result of this it makes it extremely easy for any user to visualize how all the data from the csv file and more is stored. 

How to Run:
To run this program, we must first compile it. There are three files to compile: User.java, Transaction.java, Tester.java, and Main.java. In order to compile these files call the following:

javac Transaction.java
javac User.java
javac Main.java
javac Tester.java

After we've compiled the files, we can them run them using them to our specification following command where points requested is an integer and fileName is a csv file:

java Main pointsRequested fileName

Testing:
In order to test my code I ran various methods focusing those in the User class based on multiple csv files. Since I can only create small csv files, there are probably bugs that would be better found using a larger csv file.
To run the Tester class call the following:
java Tester
