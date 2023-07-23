<div align = "center">
  <h1> Doctor App</h1>
 </div>



## Framework and Language
* Java 
* SpringBoot

## Dependencies
  * SpringWeb
  * Lombok
  * JPA
  * Validation
  * SQL database
  * Swagger
    
    
## Database Used 
  * SQL Database
    
## Data flow
  **The project has four main packages which are following** 
  
* Controller - Controller package has all the api and Crud operations.
* Services - Service class has all the business logic and it will return the result of that method which is called by controller class . 
* Repository - Respository has all the datasource in it i used SQL Database
* Model - Model has all the classes which has entity like admin , patient and may more.
> The flow of data is from controller has all the api and logics of that api has in service class and
service class is using the repository class which has all the data it keeps data source.The api called by user call the controller method
return the logic which is written in service class so service class object is called and service class use data source of repo class.

## Project Summary 
  This is Docto App we can do many more operations in this project like
  * SignUp Patient
  * SignIn Patient
  * SignOut Patient
  * Adding doctor
  * Schedule Appointment
  * Cancel Appointment and many more
  Schedue Appointment
