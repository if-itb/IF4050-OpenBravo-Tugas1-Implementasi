Mochammad Dikra Prasetya	13511030
Evan Budianto			13511041
Muhammad Nassirudin		13511044
Renusa Andra Prayogo		13511063


=== DESCRIPTION ===

We created a new webservice which returns all sales orders for a certain product.We were focus on reading information and not updating the database. As the information is needed to be returned in xml format, we will show how objects read from the database can be converted to it.

The webservice shall return all the sales orders for a certain product. Here is the workflow of the service:
- Receive the http request which contains the product ID as a parameter
- Read all sales orders which have this product in any of the order lines
- Convert the sales order(s) to an xml
- Return the xml to the client browser sending the request 


=== INSTALLATION ===

Merge folder Module in project to folder Module in OpenBravo's project.
