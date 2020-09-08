# Node JS Based basic ToDo Application

Backend implementation for a basic node js based To Do Appliaction with the following routes.


Routes:

    POST /add
        Request Body:
         - name : String - Name of the task
         - description: String - Descripton of the task
         - creator: String - Name of the Creator
         - duration: Integer - Number of seconds the task will last
        
        Response:
         - 201 : Success
         - 400 : Error Message

    GET /list
        Response:
         - 200 : Array Containing the tasks
         - 400 : Error Message

The tasks will be deleted after the mentioned duration from the database using the mongoDB TTL property.

Author: Ravi 1706251
