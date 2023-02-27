## TODO APP
# LogIn Page

# Main Page without tasks
![image](https://user-images.githubusercontent.com/73232366/221599021-5dc40ad8-424c-4ecf-8764-9231d55949fd.png)
# Main Page
![image](https://user-images.githubusercontent.com/73232366/221599209-4fe5fce5-8e6e-4c41-b671-9888f4f7f226.png)
# Main Page with open profile info
![image](https://user-images.githubusercontent.com/73232366/221599387-93aa24bb-8184-499f-8a06-e9cab523362a.png)

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

