<H1>🚕 Taxi Service 🚕 </H1>

<h2>📙 Project description</h2>
A simple web-app application that supports authentication, registration and other CRUD operations.

<h2>🌿 Quickstart </h2>
<h5>You can test various functionalities and features of web-app via Amazon Web Service Elastic Beans vis this link ⬇️ </br> <a asign = "centr" href="http://app-1-env.eba-pzmnb4tc.eu-north-1.elasticbeanstalk.com"> Taxi Service </a></h5>

<h2>🎯 Features </h2>
⚪ Registration like driver <br/>
⚪ Authentication like driver <br/>
⚪ Logout <br/>
⚪ Create/Update/Remove driver <br/>
⚪ Create/Update/Remove manufacturer <br/>
⚪ Create/Update/Remove car <br/>
⚪ Display list of all manufacturers <br/>
⚪ Display list of all drivers <br/>
⚪ Display list of all cars <br/>
⚪ Dispay current cars of logged driver <br/>
⚪ Add driver to car <br/>
⚪ Remove driver from car <br/>

<h2>📄 Entity-Relationship diagram </h2>
⬇️ Visualization of relationships between entities in db ⬇️
<img src="https://github.com/vgladkyi/taxi-service/blob/main/src/main/resources/ER%20diagram.png" width="700" title="ER diagram">
<h2>🌐👨🏻‍💻 Technologies </h2>
⚪ Java 11 </br>
⚪ Maven </br>
⚪ Apache Tomcat 9 </br>
⚪ JSP </br>
⚪ Java Servlet </br>
⚪ SQL </br>
⚪ AWS Elastic Beanstalk </br>

<h2> 🛠️ Setting up </h2>
Step 1: Create database. Create a schema and copy everything from the `..resources/init_db.sql` file, then execute query in your DB.
Step 2: Setting up correct unique variables. In the class "ConnectionUtil" you need to replace green text with your credentials. 
<img src="https://github.com/vgladkyi/taxi-service/blob/main/src/main/resources/variables.png" width="500" title="variables">
Step 3: You need to configure Tomcat 9. Then you will need to fix your config. Press "fix"->"war exploded". In the application context string you need to keep only "/"
<img src="https://github.com/vgladkyi/taxi-service/blob/main/src/main/resources/1.png" width="600" title="1">
<img src="https://github.com/vgladkyi/taxi-service/blob/main/src/main/resources/2.png" width="600" title="2">
<img src="https://github.com/vgladkyi/taxi-service/blob/main/src/main/resources/3.png" width="600" title="3">
Step 4: To get login credentials you need to register. To enter main menu you need to sign in. 
