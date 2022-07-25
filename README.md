
==============================================
# PROJECT TOPIC : Stock Price and Apps & Tools 
created by- Suman Purkait
==============================================
# PROBLEM STATEMENT :
1) Open the link of be.cognizant portal
2) Log in with your credentials
3) Redirect to Apps and Tools page
4) Redirect to Office 356 Apps
5) Print all the names of Apps/Tools and Stock Price(CTSH) along with the name of the account

==============================================
#TECHNOLOGY USED :
1)Java programming language
2)Selenium
3) Maven
4)TestNG
5)Extent Report

================================================

# PROJECT STRUCTURE :
1) The project structure is followed by Maven.
2)Java has been used as the programming language,TestNG framework has been used to generate test suites,Selenium has been used as an automation tool.
3)Chrome driver has been installed to run the site.
4)All the dependencies has been written in pom.xml.
5)The test report is in report.html.


==================================================================================

# STEPS :

1) As the project is following Maven structure , there are Three main folders :
                    i)SRC/main/ java ii) SRC/main/resources and ii)SRC/test/java

2)Under SRC/main/java 3 packages are made : i) Base ii) Pages and iii) Utils along with configuration

3)Under the Base package we have created the required Base.java class. In this class we have written the code for opening the webdriver and calling the required functions.

4)Under the Pages package we have created the class All apps and Tools for redirecting to the correct login page-->Locate the positions of entering data ---> Enter required details -->Click the Sign in button -->Redirecting to BE.Cognizant.CMS-->Print the output as per conditions


5) In the pom.xml file we have written the dependencies of this project.

6)In the configuration file we have mentioned the configurations of the project.

7)In the Report.html file the report has been shown of all test cases.

8)We have printed the output in the console.

===================================================================================================



# OUTPUT:
All the test cases are passed successfully and the result is displayed in the console as well as in Extent Report.
