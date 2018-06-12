# DISC Personality Assessment
The DISC is a behavior assessment tool based on the DISC theory of psychologist William Moulton Marston, which centers on four different behavioral traits: dominance, inducement, submission, and compliance. This theory was then developed into a behavioral assessment tool by industrial psychologist Walter Vernon Clarke.

The DISC is used by top MBA programs including Harvard and Stanford as well as fortune 500 companies. The goal is to improve self-awareness, which is essential to cultivate positive growth and success. The DISC also helps identify the barriers to success and helps leaders learn how to align the different aspects of their personality to meet their overarching goals.

## Technical Information
This implementation of the DISC Personality Test is built using PHP language and MySQL/MariaDB database server.

## Installation
1. download 'disc_master.zip' file
2. extract and copy all files to document root folder on your webserver (or other folder that you want)
3. create new database named 'test'
4. import 'db/disc.sql' to the 'test' database
5. change database configuration on 'index.php' and 'result.php' file 
   - default value is $dbhost='localhost;$dbuser='root';$dbpass='';dbname='test';
6. try accesing to http://localhost

## Technology
+ PHP (http://www.php.net/), 
+ MySQL (http://www.mysql.com/), 
