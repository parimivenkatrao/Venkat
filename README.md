 Perform testing for each CRUD operation (create, read, update, delete) Using Python ,Django, MySQL, HTML, CSS, 
#1. hashtag#Setting Up Django Project and MySQL Database
Install Django and MySQL client libraries:
Use pip to install Django and the MySQL client library (mysqlclient).
Create Django Project and App:
Initialize a new Django project.
Create a new Django app within the project.
Configure MySQL Database in Django Settings:
Update the DATABASES setting in settings.py
 to use MySQL, including database name, user, password, host, and port.
#2. hashtag#Creating hashtag#the hashtag#Node hashtag#Model

Create a model in models.py
 to represent the Node entity, including fields for name and description.
hashtag#Apply hashtag#Database hashtag#Migrations:
Run Django management commands to create and apply migrations, which will create the necessary tables in the MySQL database.
#3. hashtag#Creating hashtag#Views hashtag#for hashtag#CRUD hashtag#Operations
hashtag#Create hashtag#View:
Define a view to handle creating a new node, including processing form data and saving the node to the database.
hashtag#Read hashtag#View:
Define a view to list all nodes, retrieving data from the database and passing it to a template for rendering.
hashtag#Update hashtag#View:
Define a view to handle updating an existing node, including loading existing data, processing form data, and saving changes.
hashtag#Delete hashtag#View:
Define a view to handle deleting a node, including confirming the deletion and removing the node from the database.
#4. hashtag#Creating hashtag#Forms

Create a form class to represent the input fields for creating and updating nodes, including validation logic.
#5. hashtag#Creating hashtag#Templates
Create Template for Node List:
Define an HTML template to display a list of nodes, including styling with CSS.
Create Template for Node Form:
Define an HTML template to display the form for creating and updating nodes, including styling with CSS.
Create Template for Node Deletion Confirmation:
Define an HTML template to confirm node deletion, including styling with CSS.
#6. hashtag#Routing or hashtag#Define hashtag#URL hashtag#Patterns:

Create URL patterns in urls.py
 to map URLs to the corresponding views for create, read, update, and delete operations.
#7. hashtag#Testing hashtag#and hashtag#Debugging
Run the Development Server:
Use Django’s development server to run the application locally for testing.
