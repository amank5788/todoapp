##Architecture

![mongo](https://github.com/amank5788/todoapp/assets/88306289/7eeca31c-ceaf-4283-8883-beab573b9f3d)


# Documentation for APIs



:todoId - id of todo database
:taskId - id of task from database


## Todo routes 

- GET Todo
    - localhost:4000/api/getTodos

- CREATE Todo
    - localhost:4000/api/createTodo
    - body:{
        "title":""
    }

- EDIT Todo
    - localhost:4000/api/editTodo/:todoId
     - body:{
        "title":""
    }


- DELETE Todo
    - localhost:4000/api/deleteTodo/637a12ed69348dec4dfb91e3



## Task routes

- GET Task
    - localhost:4000/api/getTasks/:todoId

- CREATE Task
    - localhost:4000/api/addTask/:todoId
    - {
        "main":"create movie desgin"
       }

- EDIT Task
    - localhost:4000/api/editTask/:todoID/:taskId
    - {
        "main":"new task"
        }

- DELETE Task
    - localhost:4000/api/deleteTask/:todoID/:taskId

- CHECK/UNCHECK
    - localhost:4000/api/checkTask/:todoID/:taskId
