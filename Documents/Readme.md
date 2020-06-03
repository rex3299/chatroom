### Requirements

1. Netbeans ( correctly configured ).
2. MySQL Database ( correctly configured and running ).
3. Java 

The MySQL Database consists of following configurations as per the code :

Database Name : tempProfile1

Tables Schemas :

Table : info
id varchar(30)
password varchar(30)

Table : persongroup
groupname varchar(30)
person varchar(30)
admin int

Table : requests
id varchar(30)
groupname varchar(30)

### Steps to Run

1. Open `JavaLibrary1/src/lib1/Javaconnect.java` and edit the following parameters to connect to the MySQL database.
    * Connection String
    * Username
    * Password

2. Import all the project into the NetBeans application. ( Namely : `ChatGUI`, `JavaLibrary1`, `RMIMainServer`, `RMIServer1` ).

3. Run the following projects in the given below manner to execute the program:

    * **RMIServer1:** Run File `RMIServer1.java`	(Distributed_ChatRoom\RMIServer1\src\rmiserver1\RMIServer1.java)
    * **RMIServer2:** Run File `RMIServer2.java`	(Distributed_ChatRoom\RMIServer1\src\rmiserver1\RMIServer2.java)
    * **RMIServer3:** Run File `RMIServer3.java`	(Distributed_ChatRoom\RMIServer1\src\rmiserver1\RMIServer3.java)
    * **RMIMainServer:** Run File `RMIMainServer.java`.	(Distributed_ChatRoom\RMIMainServer\src\rmimainserver\RMIMainServer.java)
    * **ChatGUI:** Run File `ChatGUI.java`.		(Distributed_ChatRoom\ChatGUI\src\chatgui\ChatGUI.java)
    
    

###### Note: The only hardcoded part in the project lies at *RMIMainServer.java - Line 97* to set the **Server IP String**.
