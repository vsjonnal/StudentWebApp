# StudentWebApp
 Student Web application built using EJB Session Beans, JPA (Persistence), Servlet & JSP
 Tested application using Oracle DB.
 Performs Insertion, Updation & Deletion of Record from Database.

build compile & install
 mvn clean compile install

Once we have .war file in the target directiory, deploy the file in Weblogic server and start the Server.

Prerequisite:
 - DataSource "JDBCTest" creation.

Application URL to test
    - http://<Server-ip-address>:<Port>/StudentWebApp/StudentServlet
