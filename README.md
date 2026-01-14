# Coffee Shop Management System

**Project Overview**

A comprehensive coffee shop management system built with Java, featuring order management, inventory tracking, and reporting capabilities.

**Group Members:**
1. Ishfaq, Junaid
2. Mahenge, Ima
3. Kazi, Adil
4. Alshehri, Aedh
5. Mane, Shreyash

**Project Tools**

Project Tools used for the development. To work with the project, ensure you have  
**Java: JDK21**
  
To Import a Project in Eclipse:
1. Download the Project files  
	1.1. Stage 1 -> CoffeeShopGroup20Codes_Stage_1.zip
	1.2. Stage 2 -> Code_Stage_2.zip
2. **Click Import -> General ->Existing Project into Workspace -> Select archive file ->Finish**  

**Project Structure**  
The project is four important directories
1. *src/main/java* - It contain all java classes to run the application.
2. *src/main/resources* - It contains all application resources.
3. *src/test/java* - It contains all test classes for our application
4. *data* - This contains all the files that application uses to run. It maintains users, orders, menu items and completed orders.
5. *logs* - This is the log file. Every day new log file will be created.

**Project Packages**  
Root Package: **uk.ac.hw.group20**  
Modular Packages:  
1. uk.ac.hw.group20.admin - *Package to handle identity management module*
2. uk.ac.hw.group20.errorhandler - *Package to handle custom exceptions*
3. uk.ac.hw.group20.main - *Package to handle the main application and home GUI*
4. uk.ac.hw.group20.order - *Package to handle orders*
5. uk.ac.hw.group20.order.bill - *Package to handle order bills*
6. uk.ac.hw.group20.report - *Package to handle reporting*
7. uk.ac.hw.group20.utils - *Package for common utilities*
8. uk.ac.hw.group20.logger - *Package for Logger implementation*
10.	uk.ac.hw.group20.order.controller – *Package for the order controller*
11.	uk.ac.hw.group20.test.order – *Package for Junit test classes*

**Installation Steps**   
Step 0: Download a file from  
	- Stage 1 Runnable_Jar_Stage_1.zip
	- Stage 2 Runnable_Jar_Stage_2.zip
Step 1: Extract the file in the desired folder.  
Step 2: Check whether the extracted folder contain the .jar file, data and logs folder.  
Step 3: Double click on the .jar file.  
Step 4: Enter username: IMA and password: IMA - Note: Username and password is case sensitive  
Step 5: Follow the on screen menus to perform the following:-  

**Stage 1: Make an Order**  
1. *Make order: Click on the Category Beverage, Food Items or Other Items.*  
2. *Select the Item you want to order.*  
3. *Change the quantity if required.*  
4. *Click on add Item to add the item to Shopping Cart.*  
5. *Repeat the steps 1-4 until your order is as per your requirement.*  
6. *You can try adding items to already existing item, System will update the shopping cart.*  
7. *Click Complete and Pay button to place an order.*  
	
**Stage 1: Processing Order**  
1. *Click on the Orders then Process menu on menu bar.*
2. *Menu will be loaded in the Information Panel*
3. *Click on the Process Order button to view the order to process. The first item in the queue will be picked.*
4. *Check the details and prepare the order before saving.*
5. *Click Yes to process or No to cancel processing the bill.*
6. *Once Yes is selected the order will be removed from the queue and be added to order archive folder.*

**Stage 1: Report**
1. *Click on the Report then Orders from the menu bar.*
2. *The report of all orders will be displayed in the information panel.*
3. *Check the aggregation of quantity and sales for all orders.*

**Stage 2: Automated Threads**
1. *Login in the system by providing the password below*
2. *Observe the Orders being added to queue. The maximum queue size can be adjusted by changing the value of int maxQueueSize = 3 in the OrderController class package uk.ac.hw.group20.order.controller*
3. *You can change the timers of the threads by adjusting the values in the GUI at Runtime Controls.*
4. *The default values can be changed by updating the values in the constructor of the ThreadTimerDto in package uk.ac.hw.group20.order.dto.*
5. *Consumer threads are adjusted based on the number of the orders pending in the queue*

**Stage 2: Order Adding**
1. *Make order: Click on the Category Beverage, Food Items or Other Items.*  
2. *Select the Item you want to order.*  
3. *Change the quantity if required.*  
4. *Click on add Item to add the item to Shopping Cart.*  
5. *Repeat the steps 1-4 until your order is as per your requirement.*  
6. *You can try adding items to already existing item, System will update the shopping cart.*  
7. *Click Complete and Pay button to place an order.* 
8. *If processing in not completed orders will be added in the processing queue otherwise they will be added to the for next time the application runs*

**Stage 2: Logs**
1. *You can view the application logs in the console or file named coffee-shop-log-yyyy-MM-dd.log in logs folder.*  
2. *The logs includes information about the event date, log level, thread name and event message*

**Stage 2: Report**
1. *Once application complete processing the orders will display the summary report.*  
2. *Also the detailed report can be produced by Clicking on the Report then Orders from the menu bar*  
2. *The report of all orders will be displayed*  
3. *Check the aggregation of quantity and sales for all orders.*  

**Users per role - Case Sensitive**
1. Customers  
	-*Username*: IMA  
	-*Password*: IMA  
2. Employee  
	-*Username*: admin,  
	-*Password*: password
	
**Version Control and Collaboration**  
This project uses Git for version control and collaboration.  
Main Branch: master  
Other Branches: ima, junaid, adil, shreyash, aedh
