# Django Rest Framework



#### CRUD functionality with Django REST Framework

Four main API requests are GET, POST, PUT, DELETE.<br />
1. GET —This request is made when we wanna request some data from the server. Eg: Fetching weather forecast from the weather API.<br />
2. POST — This request is made when we wanna add data to the server. Eg: User Registration and Login.<br />
3. PUT — This request is for changing any Existing information in the server. Eg: Updating User Profile.<br />
4. DELETE — As the name indicates, this request is made where we wanna delete any existing information.<br />
Note: __str__() ->in every model you should define the standard Python class method __str__() to return a human-readable string for each object.<br />
<br />


### Assignment:

Create a Backend of Hospital Management system using DRF. App name should be patient<br />
1. Patient Data(Models) which needs to be stored
2. Patient registration number -> patient_reg_no (CharField) -> This should be Unique but should not be a primary key
3. Patient name -> patient_name (CharField) -> 
4. Patient Email -> patient_email (EmailField)
5. Patient Mobile Number -> patient_mobile (CharField)
6. admitted at -> DateTimeField (Text field)(default : current time)



