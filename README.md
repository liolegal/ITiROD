## TODO APP
# LogIn Page
![image](https://user-images.githubusercontent.com/73232366/221599917-7cb8e985-ba05-425b-bb01-3e4ee633b70e.png)

# Main Page without tasks
![image](https://user-images.githubusercontent.com/73232366/221599021-5dc40ad8-424c-4ecf-8764-9231d55949fd.png)
# Main Page
![image](https://user-images.githubusercontent.com/73232366/221599209-4fe5fce5-8e6e-4c41-b671-9888f4f7f226.png)
# Main Page with open profile info
![image](https://user-images.githubusercontent.com/73232366/221602064-9b7cb8c7-3263-433f-b362-624a8acf9969.png)

## Main-functions
- Sign in  
  Method — "POST"  
  Params — username ___string___, password ___string___  
  Returns a response to a login request  

- Get todos by id  
  Method — "GET"  
  Params — userId ___number___  
  Returns a list of user's todos.  

- Add todo  
  Method — "POST"  
  Params — userId ___number___, task __string__  
  Returns the result of the request  

- Update todo  
  Method — "PUT"  
  Params — taskId ___number___, task __string__  
  Returns the result of the request 

- Delete todo  
  Method — "DELETE"  
  Params — taskId ___number___  
  Returns the result of the request
  
 - Get count of completed todos  
  Method — "GET"  
  Params — userId ___number___  
  Returns count of completed todos. 
  
 - Get user by id
  Method — "GET"  
  Params — userId ___number___  
  Returns data about user.
  
   - Edit user info  
  Method — "POST"  
  Params — userId ___number___, nickname __string__ 
  Returns count of completed todos. 


## Data-models


### Data to login  
Data required for authorization
- username ___string___
- password ___string___


### Full user info
Full info about user
- id ___number___
- username ___string___
- email ___string___


### Todo data
Info about todo
- id: ___number___
- todo: ___string___
- userId: ___number___
- usermade: ___boolean___
