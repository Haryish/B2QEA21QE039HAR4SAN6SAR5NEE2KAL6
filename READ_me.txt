TOPIC:  Be Cognizant Header Page 


CONTENTS OF THE FILE
---------------------
1. Team Members
2. Introduction
3. Project Description
4. Pre-requisites
5. Tools Used
6. Procedure for accessing


Team Members:
--------------
2073038       - Neena Thresy Joy
2072913       - Saranya R Menon
2072861       - Sangeetha M    
2072822       - Haryish E
2072867       - Kalanithi S


Introduction:
-------------
The main objective of the project is to implement testing procedures to get the submenu titles and verifying it's count as expected or not. It requires implementation of data provider concept and POM testing design pattern.


Project Description:
--------------------
We are using the header section of Be Cognizant website. We need to test the functionality of dropdown, get the count of each data under each submenus under each dropdown and test the count the name as expected. The possible scenario of this project is described as below.

1. Login to the Be cognizant page and enter your work mail Id and password and verify the authentications process as directed (either through otp generationa and phone to a verified number). And check if the user is same as your login credencials through printing it.
2. On Be cognizant header page, open each and every dropdown on top (cultural, practice and marketting, Corporate functions, Associate Resources) and get the count and submenus of each drop downs.
3. On search in workspace textbox, type randomly the relevent keywords deriving from excel sheet and check if the relevant data is printed and count should be verified.



Pre-requisites:
----------------
-URL for https://be.cognizant.com/

Note: Due to memory limitations in Tekstac Platform, We have removed webdriver executable files. We Request you to paste the web drivers of chrome and firefox in belwo mentioned path
Path: IdentifyCourses/driver/


Frameworks & Tools Used:
------------------------
- Selenium Web Driver 
- TestNG 
- Java
- POM 
- HTML Extend Report


Procedure for accessing:
------------------------
1.Login to Be.cognizant page with help of your cognizant's login credentials (work email-id,password, and otp/call)
2.Verify the user and print the user on console.
3.Verify the header part availability
4.Click all the dropdowns available on header page and print the values
5.Check if the count displayed on each submenu is same as we expected
6.On search for workspace page, type relevant and random word and check if relevant results come up.
7.Get the count and the  submenus of each dropdown and verify if it is same as expected as per test data.
8.Check if 0 is printed on the header, for the submenus having empty texts and test if that too verified with as expected(that is 0).


To Run the Project:
-------------------
 Run the testng.xml file using TestNG suite


Report:
--------
To access the Report generated, reach the Report Folder: \IdenitifyCourses\test-output\index.html

