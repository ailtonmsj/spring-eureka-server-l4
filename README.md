# spring-eureka-server-l4
### It is necessary include the host configuration for the eureka server runs with three instances:
#### In the host include the lines:
127.0.0.1       eureka-primary  
127.0.0.1       eureka-secondary  
127.0.0.1       eureka-tertiary  

### Change the application.yml removing the uncommented contend and uncommenting the last lines from the file (server.port and the eureka... configuration)

## To open the dashboard use:
#### single instance:  
localhost:8010
  
#### The cluster above:  
localhost:8011  
localhost:8012  
localhost:8013  


