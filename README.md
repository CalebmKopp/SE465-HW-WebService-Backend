# SE465-HW-WebService-Backend

### Assignment description
> ...This group assignment requires you to design and implement a small prototype in order to show case the successful use of web services in order to solve a specific domain.

- This repository contains data ViewModels that were created in accordance with Entity Framework.

	- EF makes creating data models and connecting them to the outside world very understandable through code-first database schema definition

	- This allows for more scalability by having a RESTful layer be easily defined between clients and the data-store itself

	- REST endpoints are created through EF templates and then edited for specific user purposes.

- A client application passes a request with HTTP verbs

	- GET

	- POST

	- PUT

	- DELETE

- And the API makes a request to the database with the .JSON formatted body of the client's request for certain information

- This is then returned to the client, in .JSON format where it can be parsed and displayed as the client application chooses

  
  

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIxMDEwNDg0OSw0MzEyNDM1NjQsLTQ0Mj
IwNzQxM119
-->