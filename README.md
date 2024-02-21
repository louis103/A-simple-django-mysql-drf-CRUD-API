## A Simple Django and Mysql CRUD(Create,Read,Update,Delete) Rest API

### Installation - start by running the following commands

```plain
git clone https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API.git
cd A-simple-django-mysql-drf-CRUD-API
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
### Screenshots of the API working
### We produce the following database tables as viewed from Jetbrains DataGrip software;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/db_table_view.png"/>

### CREATE; Adding first student via Postman;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/post1.png" />

### CREATE; Adding second student via Postman;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/post2.png" />

### READ; Get all the added students from the database;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/get_req2.png" />

### UPDATE; Update student details in the database using unique ID;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/update_req.png" />

### DELETE; Delete a student from the database using unique ID;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/delete_req.png" />

### Final Database table view from Jetbrains DataGrip Software;
<img align="center" src="https://github.com/louis103/A-simple-django-mysql-drf-CRUD-API/blob/main/outputs/final_dv_view_after_del.png" />

