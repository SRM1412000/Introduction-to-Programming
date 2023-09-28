# Introduction-to-Programming-Project

* Project by: Valeria Ferreira Nocua [@valeferreiraan](https://github.com/valeferreiraan), Germán David Plazas Cayachoa [@DavPlazas](https://github.com/DavPlazas), Santiago Rodríguez Morales [@SRM1412000](https://github.com/SRM1412000)

## Index
- [Introduction](#introduction)
  - [Summary](#summary)
  - [Functionality of the Computational Solution](#funcionalidad)
- [Uso](#uso)
  - [Subsección 3](#subsección-3)
  - [Subsección 4](#subsección-4)


## Introduction
### Summary <a name="summary"></a>
A company gets a daily summary of its accounts (income, debts and money owned by its business). The single chart of accounts is a system with a universal notation, where codes (numbers) of two to four digits are used. Each code represents a type of transaction that must be taken into account by the company. However, is it necessary for an accountant to be with a calculator all the time? For this, we have created a program in which a user can upload a file with each code and value to declare, or if you wish, the program helps you to create this file. This file contains all the data that the user wants to add to his account. Every day, the user has the possibility to update his account and add up his Assets, Liabilities and Equity thanks to the functionality of the program (Every account is balanced if Assets = Liabilities + Equity). This account summary can be viewed in a text file created by the program. In addition, in case the equation is not balanced, the program suggests where to check to balance the account. All this is possible because the program knows how to translate each code. For example, if the code entered is 1110, the program knows that it refers to a bank account and performs the relevant procedures.


### Functionality of the Computational Solution <a name="funcionalidad"></a>
1.	The program asks the user if he/she wants to create a new account or if he/she wants to continue an already active account. 

2.	In case it asks to create a new account, the program gives the user the choice of whether to upload a file with the information or if he/she wants the program's support to create it.

2.1 If the user is asked to upload a file, the program asks for the name of the file (it must be entered with the extension .txt). It is important that if the user wants to upload a file, it must comply with the following format (without leaving a line break at the end):

![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/dc016a8d-3a8b-4e1e-b5a6-7f8e493b1463)

2.1.1 In this file, the codes entered by the user are searched, a variable is assigned to them and the value recorded in the file is added to them. Then, the program proceeds to create a file called "Obri.txt", where it records the information in a table. The program verifies if the equation Assets = Liabilities + Equity is fulfilled. In case the equation is not fulfilled, the program writes in the file which are the possible problems that make the equation not balanced so that they can be analyzed by the user.

2.2 In case the user asks to create a file, the program asks for the number of transactions to declare and asks the user for the date of the day to count (in the format day-month-year). Then, the program asks for the code to declare and its respective value. When this is finished, the program creates a file with the name of the registered date. Then, the same procedure of numeral 2.1.1 is performed with the file newly created by the user with the help of the program.

3.	In case the user chooses to continue with an already created account, the program gives the user the choice whether to upload a file with the information or to get the program's support in creating it.

3.1 If a file is requested to be uploaded, the program asks for its name (it must be entered with the extension .txt). It is important that the file created by the user complies with the format specified in numeral 2.1.
The program proceeds to search in the "Obri.txt" file (where the summary of the accounts is kept) for the values that were already contained in the codes during updates of the account being developed.  Thus, the value of each code is retrieved to add the new value that the user registers in the update. Then, the same procedure of numeral 2.1.1 is performed with the file entered by the user.
3.2 In case the user asks to create a file, the program asks for the number of transactions to declare and asks the user for the date of the day to count (in day-month-year format). Then, the program asks for the code to declare and its respective value. When this is finished, the program creates a file with the name of the registered date.
The program proceeds to search in the file "Obri.txt" (where the summary of the accounts is kept) for the values that were already contained in the codes during updates of the account being developed.  Thus, the value of each code is retrieved to add the new value that the user registers in the update. Then, the same procedure of numeral 2.1.1 is performed with the file newly created by the user with the help of the program.

4.	The account summary is now visible in the file "Obri.txt".

## Uso
### Subsección 3 <a name="subsección-3"></a>
Contenido de la Subsección 3...

### Subsección 4 <a name="subsección-4"></a>
Contenido de la Subsección 4...

