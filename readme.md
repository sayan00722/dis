**Prerequisites**

1. Install XAMPP web server.
2. Any Editor (Preferably VS Code or Sublime Text).
3. Any web browser with latest version.
4. Install Python.
5. Install Anaconda.

**Languages and Technologies used**

1. HTML5/CSS3
2. JavaScript
3. Bootstrap
4. XAMPP
5. Python, Django
6. MySQL

**Steps to run the project in your machine**

1. Download and install XAMPP in your machine.
2. Download and install VS code in your machine.
3. Download and install Python in your machine.
4. Download and install Anaconda in your machine.
5. Open the source code folder and open health care folder in VS code.
6. Start the Apache and Mysql in your XAMPP control panel.
7. Open your web browser and type 'localhost/phpmyadmin'.
8. In phpmyadmin page, create a new database from the left panel and name it as 'healthcare_db'.
9. Import the file 'healthcare_db.sql' inside your newly created database and click ok.
10. Create "ML Disease Prediction - Smart Doctor" and "Drug Recommendation" to create trained model after creating a folder model.
11. the overall structure will be     Directory: D:\healthcare


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        09-03-2024     02:24                core

d-----        09-03-2024     02:24                healthcare

d-----        16-03-2024     03:29                model (here the trained model will be stored)

d-----        09-03-2024     02:24                myEnv

-a----        09-03-2024     03:18          28173 Drug Recommendation.ipynb

-a----        11-05-2023     11:20         296332 Drug.csv

-a----        11-05-2023     10:50            666 manage.py

-a----        09-03-2024     02:03          73533 ML Disease Prediction - Smart Doctor.ipynb

-a----        16-03-2024     03:14           1187 readme.md

-a----        11-05-2023     11:20        1370414 Training.csv

10. Open VS code and write a command in terminal which is 'python manage.py runserver'.
