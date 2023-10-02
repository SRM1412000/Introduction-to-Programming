# Introduction-to-Programming-Project
<justify>


* Project by: Valeria Ferreira Nocua [@valeferreiraan](https://github.com/valeferreiraan), Germán David Plazas Cayachoa [@DavPlazas](https://github.com/DavPlazas), Santiago Rodríguez Morales [@SRM1412000](https://github.com/SRM1412000)

## Index
- [Introduction.](#introduction)
  - [Summary.](#summary)
  - [Functionality of the Computational Solution.](#funcionalidad)

- [Description of program.](#description)
- [How to use.](#use)


## Introduction
### Summary <a name="summary"></a>
A company gets a daily summary of its accounts (income, debts and money owned by its business). The single chart of accounts is a system with a universal notation, where codes (numbers) of two to four digits are used. Each code represents a type of transaction that must be taken into account by the company. However, is it necessary for an accountant to be with a calculator all the time? For this, we have created a program in which a user can upload a file with each code and value to declare, or if you wish, the program helps you to create this file. This file contains all the data that the user wants to add to his account. Every day, the user has the possibility to update his account and add up his Assets, Liabilities and Equity thanks to the functionality of the program (Every account is balanced if Assets = Liabilities + Equity). This account summary can be viewed in a text file created by the program. In addition, in case the equation is not balanced, the program suggests where to check to balance the account. All this is possible because the program knows how to translate each code. For example, if the code entered is 1110, the program knows that it refers to a bank account and performs the relevant procedures.


### Functionality of the Computational Solution <a name="funcionalidad"></a>


1. The program asks the user if he/she wants to create a new account or if he/she wants to continue an already active account. 
2. In case it asks to create a new account, the program gives the user the choice of whether to upload a file with the information or if he/she wants the program's support to create it.
   
   2.1 If the user is asked to upload a file, the program asks for the name of the file (it must be entered with the extension .txt). It is important that if the user wants to upload a file, it must comply with the following format (without leaving a line break at the end):
   
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/dc016a8d-3a8b-4e1e-b5a6-7f8e493b1463)
   
      2.1.1 In this file, the codes entered by the user are searched, a variable is assigned to them and the value recorded in the file is added to them. Then, the program proceeds to create a file called "Obri.txt", where it records the information in a table. The program verifies if the equation Assets = Liabilities + Equity is fulfilled. In case the equation is not fulfilled, the program writes in the file which are the possible problems that make the equation not balanced so that they can be analyzed by the user.
    
   2.2 In case the user asks to create a file, the program asks for the number of transactions to declare and asks the user for the date of the day to count (in the format day-month-year). Then, the program asks for the code to declare and its respective value. When this is finished, the program creates a file with the name of the registered date. Then, the same procedure of numeral 2.1.1 is performed with the file newly created by the user with the help of the program.

4. In case the user chooses to continue with an already created account, the program gives the user the choice whether to upload a file with the information or to get the program's support in creating it.

   3.1 If a file is requested to be uploaded, the program asks for its name (it must be entered with the extension .txt). It is important that the file created by the user complies with the format specified in numeral 2.1.
The program proceeds to search in the "Obri.txt" file (where the summary of the accounts is kept) for the values that were already contained in the codes during updates of the account being developed.  Thus, the value of each code is retrieved to add the new value that the user registers in the update. Then, the same procedure of numeral 2.1.1 is performed with the file entered by the user.

   3.2 In case the user asks to create a file, the program asks for the number of transactions to declare and asks the user for the date of the day to count (in day-month-year format). Then, the program asks for the code to declare and its respective value. When this is finished, the program creates a file with the name of the registered date.
The program proceeds to search in the file "Obri.txt" (where the summary of the accounts is kept) for the values that were already contained in the codes during updates of the account being developed.  Thus, the value of each code is retrieved to add the new value that the user registers in the update. Then, the same procedure of numeral 2.1.1 is performed with the file newly created by the user with the help of the program.

5.	The account summary is now visible in the file "Obri.txt".

## Description of program <a name="description"></a>

1. File names: Main program: ProjectVFF.py. Attached files to check the correct functioning of the program: 23.txt, 24.txt, 25.txt, 26.txt, 27.txt and Word file "User's guide for the use of the project.
2. File to run: VFF.py project.
3. Functions: The project does not define functions for its operation, it does the same procedure according to the user's indications.
4. Order of the project:
   * The program asks how you want to use the program, if you want to create or upload a file. In case you want to create a file, it creates it (Lines 1 to 19 of ProjectVFF.py).
   * The program initializes variables or collects information from the account summary (Lines 21 to 172 of ProyectoVFF.py).
  
   * The program proceeds to add and adjust changes in the variables (Lines 177 to 461 of ProyectoVFF.py).
  
   * The program writes in the file the collected information in the form of a table (Lines 465 to 775 of ProyectoVFF.py).
  
   * The program writes in the project the value owned in Assets, Liabilities and Equity (Lines 777 to 779 of ProyectoVFF.py).
  
   * The program checks if the equation is balanced. If not, it suggests the steps to review to balance your account (Lines 781 to 915 of ProyectoVFF.py).
  
   * The program indicates where the summary information is (Lines 921 and 922 of ProyectoVFF.py).
                         
5. As previously stated, the program does not define functions or classes for its execution. Basically, in each call it iterates over the readings and looks for the values.

## Hot to use <a name="use"></a>
1. Save the file ProjectVFF.py in a folder. 
2. Save the files 23.txt, 24.txt, 25.txt, 26.txt and 27.txt in the same folder as ProjectVFF.py.
3. Run the program by clicking on the green arrow.
   
   ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/45a3137e-1eef-4927-8336-53420208cac7)

4. The following message will be displayed in the console:

    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/39956efa-6286-4d3c-95e8-d5cdbeca6471)

    Type in the console the number 0, without spaces.
    
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/23860149-3169-4d0e-ad53-82b7bead0a50)!

    When you press enter, the following message will be displayed in the console:
    
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/e470a72d-0ead-46fc-b67b-756b4c83ad3a)

    Type 1 without leaving any spaces:
           
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/0dcbb94a-7d56-4329-9144-7b109f50a716)

    When you press enter, the following message will be displayed on the console:
    
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/b1a8f245-bba1-476b-8fd8-6087a1a7c744)

    
    Type 23.txt
   
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/09185df4-b943-4a35-ac8b-b7ef1ce0ffae)

    When you press enter, the following message will be printed to the console:
    ![image](https://github.com/SRM1412000/Introduction-to-Programming-Project/assets/146349622/6e0d9a27-10d5-44ba-94cd-e0f39fea7315)

     
    Go to the same folder where you saved ProyectoVFF.py , there you will find the file "Obri.txt" (In the case of checking with 23.txt you will notice how the program identifies two codes and accounts for a balanced equation).
    
    IMPORTANT: Do not delete the file "Obri.txt" at any time.

</justify>
