# Bookpedeal

This is a book aggregator for shopping books online.

Her we consider 5 wesite books. So this an example of web scripping from differnt website and to insert this data in mysql.

Guide to run this project

install packages from Anaconda Navigator Environments:
1. django
2. mysqlclient
3. plotly


install xampp
open xampp control panel, 
1. start apache
2. start mysql

go to xampp directory and open php>php.ini configuration file and make below changes:
max_input_time = 500000
max_execution_time = 500000
post_max_size=750M
upload_max_filesize=750M

To create the database in your system:
1. open in your browser: "http://localhost/phpmyadmin/"
2. create a database - 'booksweb' manually
3. Go to import tab in 'booksweb' db and select the file 'booksweb.sql' from 'PYTHON PROJECT' folder.
4. Ensure two tables are imported - 'book_book_data' & 'book_notify_me' with 2L and 5 rows respectively.


to run the app:
1. open XAMPP Control Panel and start Apache and MySQL
2. open prompt and go to 'BookWeb' directory on your harddisk eg- "D:\Aegis\Python\PYTHON PROJECT\BookWeb>"
3. run - "python manage.py runserver"
4. after execution you will get url such as - "http://127.0.0.1:8000/", copy that and paste in your browser, add "book/" to url before running it.

