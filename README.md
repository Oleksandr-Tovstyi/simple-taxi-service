# 🚖Simple-taxi-service
This simple application is for storing cars, drivers and manufacturers models with relations between them.
# 🎯 Features
<lu>
<li>Registration and authentication for drivers (log in, log out).</li>
<li>CRUD operations for three models (driver, car, manufacturer).</li>
<li>Possibility to add drivers to car.</li>
<li>Possibility to display all drivers for car and all cars for authenticated driver.</li>
</lu>

# 📖Structure
<lu>
<li>N-tier structure (DAO, Service, Controller).</li>
<li>Database with relations between tables one-to-one, one-to-many, many-to-many.</li>
</lu>
<img src="img.jpg">

# 🧬Technologies
<lu>
<li>Java</li>
<li>Java (javax.servlet)</li>
<li>MySQL</li>
<li>JDBC</li>
<li>Tomcat</li>
<li>Maven</li>
</lu>

# ⚙️How to launch the project
<lu>
<li>Fork and clone this project from repository to your laptop.</li>
<li>Set up MySQL and create necessary tables by using file resources/init_db.sql.</li>
<li>Edit file taxi/util/ConnectionUtil with your field (USERNAME, PASSWORD, CONNECTION_URL), and you can change URL if it is needed.</li>
<li>Install and add Tomcat 9.0.65 to configuration.</li>
<li>Run project.</li>
</lu>
