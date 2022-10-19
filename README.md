# Assignment-2--CompSci303

Shavelle Shaw
Assignment 2- COMPSCI 303 – Read me file
	ERROR EXCEPTIONS AND CLASSES
1)	assgn1.h is a header file that contains the function declarations required for assignment one.
assgn2.h is a header file that contains the classes definitions and declarations for the assignment two.
The numerical.txt is the file of 100 integers that is needed for the array in assignment one.
 
![image](https://user-images.githubusercontent.com/114273966/196570891-da9269cb-d828-4556-b2c7-6b0002957c6e.png)



2)	After pressing run the code displays the array size and carries out the search function. This function asks for an integer being searched for and returns its position; both are displayed on the screen. The code then prompts the user for the value they desire to modify and the index position they would like the modification to be done. 
The try and catch code is then implemented for the modification function. If the user enters a position that is out of the scopes or bounds of the array, then an out-of-range error is thrown. After this error is caught, the code is aborted.
Displayed below, the user enters 122 which is greater than the array’s size and as such an error is thrown.

 
![image](https://user-images.githubusercontent.com/114273966/196570916-6dbf752e-bdbb-4bf4-8ccd-88e7c57e39ef.png)
![image](https://user-images.githubusercontent.com/114273966/196570939-ff1edf43-0830-4b2a-a3a6-603956837fe7.png)


 

3)	The code then displays the old and new value. The user is prompted to enter the number he or she would like to add to the array. The code expects an integer to be entered, if not the try and catch is implemented for the addition function. 
Display below, the user enters a string “fifteen” and because this is not an integer, the try and catch logic error is thrown and the code is aborted. The error message “Error! Incorrect type” is displayed.
 
![image](https://user-images.githubusercontent.com/114273966/196570961-fc56cebc-35a5-46b3-bd97-75ae110feacd.png)

 ![image](https://user-images.githubusercontent.com/114273966/196570976-24d34436-a4ca-42ff-a0de-6ca09beb83d2.png)


4)	The code then executes the delete function and removes the integer the user wants to delete. 

5)	The user is prompted to enter the status of the Employees: professional or nonprofessional. Professional is signified with a 1 and nonprofessional with a 0. 
When 0 is entered the user is asked for the name of the nonprofessional employee and the hours are entered.

![image](https://user-images.githubusercontent.com/114273966/196570992-2dc0ba7b-a9b4-4d34-87b8-0c29498e6047.png)

 

The user enters 80 hours and John (the name of the employee) and the weekly salary, payrate, health contribution and vacation days are calculated and displayed. 

The rates:
![image](https://user-images.githubusercontent.com/114273966/196570996-771cbeaa-6e9f-4711-adf4-64a90494fa43.png)

 

Calculations for vacation days and weekly salary:

![image](https://user-images.githubusercontent.com/114273966/196571011-5db16292-b6b4-4121-8c07-af5594171aa1.png)

 
pay= 80 * 25.6
      = 2048

vdays = 80 * 0.0125
            = 1


Health contribution calculation for nonprofessional employees:

 ![image](https://user-images.githubusercontent.com/114273966/196571032-467a6cd7-11f8-45d4-940f-35e2c016ea91.png)


Contribution = 0.025 * 2048
	         = 51.2

The final output:

 
![image](https://user-images.githubusercontent.com/114273966/196571047-465290f3-aafc-4177-931b-9a6efe1e8a19.png)


 ![image](https://user-images.githubusercontent.com/114273966/196571072-f43ea784-d8ef-4df1-9ac9-9b10c75bab91.png)



When 1 is entered the user is asked for the name of the professional employee and the hours are entered. 
Displayed below, the employee’s name is Amy and her hours are 115.

 ![image](https://user-images.githubusercontent.com/114273966/196571093-519045c7-fa48-4175-926b-ed34aca648a3.png)


The calculations are performed with the rates previously listed.

Vacation days and weekly salary calculations:

pay= 115 * 46.7
      = 5370.5

vdays = 115 * 0.0125
            = 1.4 or 1 day



Health contributions for professional employees:
 ![image](https://user-images.githubusercontent.com/114273966/196571105-702be126-05c3-4a05-b4b5-a08f6b140338.png)


contribution= 0.075* 5370.5
	        = 2.787

![image](https://user-images.githubusercontent.com/114273966/196571133-0adfb56d-a303-4c49-a3c1-ea27c2a9e698.png)


 

The final output:

![image](https://user-images.githubusercontent.com/114273966/196571146-9b722c10-f79f-4d6c-ae63-5d65726f05ae.png)

 
6)	Employee abstract class


 ![image](https://user-images.githubusercontent.com/114273966/196571161-d8402f3b-215d-42df-bb0e-40123632d7aa.png)

![image](https://user-images.githubusercontent.com/114273966/196571175-fb8fa0b6-e4d8-4a6e-827a-72a3e6e86be4.png)



7)Derived classes:
Nonprofessional
 
 ![image](https://user-images.githubusercontent.com/114273966/196571190-188169cd-10d8-480a-9af5-67a8055492fc.png)


Professional
 ![image](https://user-images.githubusercontent.com/114273966/196571198-a9668db7-bc03-418c-93e8-ed77b04566c6.png)

