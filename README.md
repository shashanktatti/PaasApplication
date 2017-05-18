Pass with Auto-scaling and loadbalancing 

This project implements "Bookcart.com" , An online book store provided as a Pass. 

This also provides Lbaas and auto-scaling.

Loadbalancer is written in Nodejs and uses round robin Algorithm to perform loadbalancing among the instances.

To implement auto-scaling , Docker is used along with Nodejs to create new comtainers and spawn new servers when load increases above a treshhold.

The application provides all the CRUD operations on the books:
*Add a book
*Delete a book
*Update book details
*Get book details
