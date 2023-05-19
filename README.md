# Stock

:house:**Stock**

### ***Framework***
---------
- spring boot

-------------

### ***Project management tool***
-------
- Maven


-----------------
### ***DataBase***
****************
- H2DataBase
****************

### **use of dependency**
-----
-
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-web</artifactId>
     </dependency>

- <dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-devtools</artifactId>
	<scope>runtime</scope>
	<optional>true</optional>
	</dependency>

- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-test</artifactId>
     <scope>test</scope>
     </dependency>






--------


-------------


### **Run tests**

------

⭕ postman 

:globe_with_meridians: chrome browser

********

### **Data structure And programming language**

-----

 - core java
 
 --------

  :point_down: **Summary**
*****
Model:

The Stock class represents a stock entity and includes fields such as stockId, stockName, stockPrice, stockOwnerCount, stockType, stockMarketCap, and stockBirthTimeStamp.
The StockType enum defines the possible types of stocks: FMCG, IT, and HEALTH.
Controller:

The StockController class handles the REST API endpoints for managing stocks.
It includes methods for retrieving stocks by type, retrieving stocks based on price and date, retrieving stocks above a certain market cap, adding stocks, updating stock market cap, updating stock type, updating stock by ID, and deleting stocks by owner count.
Repository:

The IStockRepository interface extends the CrudRepository interface and provides methods for basic CRUD operations on the Stock entity.
It also includes custom query methods for retrieving stocks based on price and date, retrieving stocks above a market cap, updating market cap, deleting stocks based on owner count, modifying stock type, and updating stock by ID.
Service:

The StockService class implements business logic for managing stocks.
It interacts with the repository to perform CRUD operations and custom queries.
The service methods include getting stocks by type, adding stocks, retrieving stocks above price and lower date, retrieving stocks above market cap, updating market cap, deleting stocks by owner count, updating stock type by ID, and updating stock by ID.
This code follows the Spring Data JPA approach, using annotations and interfaces to define the repository and service layers. It demonstrates basic CRUD operations, custom queries, and transaction management in a Spring Boot application.
*****

### **Show your Support** 
****
:star: Thankyou 

****
