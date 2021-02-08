 Write a program to design Vending Machine using your 'favourite language' with all possible tests

1. Accepts coins of 1,5,10,25 Cents i.e. penny, nickel, dime, and quarter.
2. Allow user to select products Coke(25), Pepsi(35), Soda(45)
3. Allow user to take refund by cancelling the request.
4. Return selected product and remaining change if any.
5. Allow reset operation for vending machine supplier.

Project built with Maven built automation tool.
In the the POM.xml file, I used Junit and assertj as dependencies.
I have created a Product class declared product as enum in order to use them in the project.
Than created VendingMachine class for vending machine activities such as
1- acceptedCoins
2- insertCoin
3- getTotal
4- selectProduct
5- returnProduct
6- reset

At the end I created VendingMachineTest class to test wheether vending maching is running as described in requirement file.
I have tested following 6 scenarios
1- Don't Accept If they are not 1,5,10,25 Cents
2- Accepts coins of 1,5,10,25 Cents
3- Allow user to select products Coke(25), Pepsi(35), Soda(45)
4- Allow user to take refund by cancellation
5- Return selected product and remaining change if any
6- llow reset operation for vending machine supplier