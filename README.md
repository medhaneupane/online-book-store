# online-book-store

Online book store is a web application to allow users to select books through internet and get them delivered to their doorsteps.

**It allows registered users to do the following:**
* Login
* Borwser and query books based on price, title, and category
* Add books to shopping cart.
* Update quantity in shopping cart
* Remove books from shopping cart
* Finalize order for books in shopping cart
* See the status of orders placed in the past - orders history.
* Cancel an order, if status of the order is new.

**The following table lists operations and associated objects and files.**
Operation | Files | Associated Objects
------------ | ------------- | -------------
Content from cell 1 | Content from cell 2 | Content from cell 3
Content in the first column | Content in the second column | Content in the second column

**The following are the steps to related to be taken to run the existing part of the application:**
1. Download obs.zip and unzip it into webapps directory of Tomcat installation directory.
2. Make sure you include Oracle driver classes in the classpath of Tomcat - use setClassPath.Bat file for this.
3. Create account OBS with password OBS in Oracle.
4. Create required tables in Oracle using TABLES.SQL file.
5. Make sure Oracle and Tomcat are running.
6. Build the ejb in Order directory of OBS directory.
7. Copy order_client.jar from CLIENTCLASSES directory into LIB directory of WEB-INF of OBS.
8. Run the application using the following url: http://localhost:8080/obs
9. You should see login page of the application. 
