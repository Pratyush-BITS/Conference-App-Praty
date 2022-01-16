# Conference-App Pluralsight Spring Boot Application

Create the database in and tables in MySQL by following the MySQL_Setup file.  
In the application.properties make the following changes:  
**(It's better to edit configuration and set environment variables for accessing datasource url, username and password)**  
1> spring.datasource.username=root #Replace with your MySQL User  
2> spring.datasource.password=1234 #Reaplce with your MySQL Password  
3> spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect #Only if you're using MySQL Version 8  

Test the Database connection and set Conference_app as the default database for this project.
