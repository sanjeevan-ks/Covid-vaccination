# Covid-vaccination
→ We have to start an application from Covid-vaccination/sample_reg.html.

→ We have to use the xampp server for creating the database and need to connect the connect the database with the corresponding php files .

→ We have to create a database name database123 and table name as entry_details for login credentials.

→ And also, We have to create a database named database1234 and table name as admin_entry_details for storing the admin username and password for those who can only asscess the admin features like add vaccination centre , remove vaccination centre and details of the dosage and location.

→ Lets create a database in xampp server and create a phpmyadmin and click create database and table and fields inside the table and datatype of the fields.

→ Lets start with creating a form using the html and css for get the input from the user to create an login account and we have to use post method for transfering the data in encrytped format in the address bar of the browser.

→ With the help of using the post method we can able to get the information that user has entered in the form and store it in the database123 inside the table entry_details.

→ In php file we have get the name of the button and get the information and store it in the another variable. after that we have store it in the database using the queries

→ In the login from using the php (Validation.php) we have to get two input username and password from the user to enter it correctly when the user enters correct details we have to check all the data of username and corresponding password if we found the match we have enter into the search the vaccination centre page else we have echo or return "Login unsuccessful"

→ This is a project through which you can find Covid-19 Vaccination Centers near you via your pincode.

→ This is project shows you all the Vaccination centers available near you in your area.

→ This project search's for vaccination centers via the pincode you provide

→ If vaccination centers are not available or are not registered with government the web app will show you respective alerts currently I too did't found pincode's of south india registered with the api, so when you will be using it rather if your pincode is right you can also get an error as no data found.

→ Again Back to Register page, We can able to find click here for admin user.(validation2.php)

→ In that only admin can enter where the database1234 and admin_entry_details table contain only admin username and password (We can able to add the more admin using the queries in the database1234)  using the login credentials only admin can enter into the admin page

→ Inside the admin page we can able to add , remove Vaccincation centre and descripte the details of the dosage of the vaccine.
