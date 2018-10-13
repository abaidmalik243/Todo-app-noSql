

Part I: Server REST API’s
=========================
Step 1: Todo RESTful API - Dcokerize rest API using NoSQL Database
-------------------------------------------------------------------------------

            TYPESCRIPT EXPRESS SERVER
            WITH
            MONGODB



In this step, we made a CRUD app by using NoSql database *(MongoDB)*. Data will be stored permanantly to the database



Running the App:
--------------

  1) docker-compose build
  2) docker-compose up







Code Structure:
---------------
  a) _Save data to NoSql database_<br />
      1) To save data to database, we made a *"POST"* request to server through axios. The server collects data and save to mongoDB



  b) _Get data from NoSql database_<br />
      1) To get data from NoSql database we send a *"GET"* request through axios to server. The server finds all the toDos and responed back.


  c) _Update Data on NoSql database_<br />
      1) To update data on database, we send the updated data along with unique id for that todo to server by *"PUT"* request through axios.
      <br />
      2) The server finds ToDo by id on mongodb and update it


  d) _Delete a todo_<br />
      1) To delete a ToDo, we made a "DELETE" request through axios along with id of ToDo <br />
      2) Then server finds the ToDo with same id and delete it.





Contributors:
-----------
Naveed complete this step.
