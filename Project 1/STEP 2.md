# STEP 2 - Installing MySQL
1. Use apt to aquire and install msql sotware:

    $ sudo apt install mysql-server

![img](imgaes/install_mysql.jpeg)

2. Log into my MySQ:
    $ sudo mysql 

![img](imgaes/mysql.jpeg)

3. Set root user password using:

    ALTER USER'root'@'localhost' IDENTIFIED WITH mysql_native_password BY'PassWord.1';

NB:  Deault password set:PassWord.1 
(Password should be strong and unique conatining upper and lowercase letters and special characters) .Press y for subsequent prompts

4. Start the interactive script by running:
    $ sudo mysql_secure_installation 

![img](imgaes/mysql_secure.jpeg)

5. Exist MySQL shell with:
    exit

8. Test for accessibility to MySQL console by typing:
    $ sudo mysql -p 
![img](imgaes/mysql_p.jpeg)


9. To exit MySQL console type:
    exit