# TheQuestioner
TheQuestioner is a surveying software built using Java Swing framework and MySQL RDBMS.

## Prerequisites

Install and configure [MySQL 5.7 server](https://dev.mysql.com/downloads/mysql/5.7.html) on your local machine. Also create an empty database named "the_questioner_db" & take a note of your MySQL username, password & database name.

Install [Netbeans 8.2](https://netbeans.org/downloads/old/8.2/) and JAVA SE 8.
You can download [JRE 1.8](https://www.oracle.com/java/technologies/javase-jre8-downloads.html) & [JDK 1.8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) here.

## Development setup

Download the code as zip file and save it in your preferred location.
Launch NetBeans and go to *File->Import Project->From ZIP* and choose the downloaded zip file.

Go to the TheQuestioner project folder in NetBeans Project directory(usually in *C:\user\documents\NetBeansProjects*) and open & edit the configuration file(see [below](#Configuration)).

In NetBeans, Clean and build project(Shift+F11), and then run the software(F6).

In the initial run, there will be a pop-up: "Everything initialized successfully", indicating that all the tables in the database have been created and a few sample values of questions, responses & upvotes are added, and the MySQL backend is ready to use. 

Note that this pop-up will only be displayed when the software is run the first time. 

Follow the on-screen instructions to Sign-up and then log in to use the software.

The user credentials, and other data like, questions, responses, upvotes, etc will be stored in the local MySQL database. 

Note: If you wish to re-initialize the MySQL back-end, delete all contents of the database "the_questioner_db", and go to "TheQuestioner" NetBeans project folder and edit "db_initialised.properties" file and set the "db_initialised" to false. And then re-start TheQuestioner Java software.

Also, you can check out the Screenshots folder to have a look at the User Interface of this software.

## Configuration

Open conf.properties file and enter the MySQL credentials & database name.
Also enter the SMTP Server Credentials, if you wish to use Email OTP verification functionality of this software.


## License
Code released under [MIT License.](https://choosealicense.com/licenses/mit/)

