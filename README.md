# APSSDC_Django_Project
Django_internship_project

Daily a lot of people go to library to read books which is an important part of all educational instituions like schools and colleges. Huge number of people go to library to explore and gain knowledge by reading and checking out books. So keeping the track of all these transactions is nearly impossible for a human. As there are a lot of books and people to keep track of. To the rescue comes this software, which is designed to assist the librarian and other management people to do all these in a much better and efficient way.
This Project is about *Library management system.*

We can perform the following tasks in this project:
a) Book Search
b) Check-out Books
c) Check-In Books
d) Add Borrowers
e) Pay Fines

Prerequisites:
1)	Web browser
2)	Python language
3)	MySQL 5.7 ñ All Packages (Server, Client)
4)	Pymysql (pip install pymysql)
5)	Mysqlclient (pip install mysqlclient)
6)	Pandas (pip install pandas)
7)	Django - framework (pip install Django)

Instructions to use the project
- Initially make sure that MySQL service is running by checking it in command line tool.
- If it is not working go to start->run and type 'services.msc' and locate mysql server and start it.
- After fulfilling all requirements, extract the zip file.
- After extracting, open console and go to location of extracted folder.
- Run python createTables.py to create database.
- Run python initializeTables.py to populate the database.
- After that type go to Library Management System folder where manage.py file is there.
- Type, python manage.py makemigrations
- Type, python manage.py migrate
- Type, python manage.py createsuperuser, to create a superuser. Enter user name and password.
- To run server, type, python manage.py runserver
- After that go to web browser and type 127.0.0.1:8000 and start using the app and make sure you are connected to internet.


Note: The idea submitted in the abstract has been modified as per the practical requirements like the addition of fines feature and some more changes.
