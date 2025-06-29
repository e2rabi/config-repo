## Testing Skypay Hotel Project

### Cloning It

The first thing to do is to open **git bash** command line, and then simply you can clone the project under any of your favorite places as the following:

```bash
> git clone https://github.com/mohamed-taman/Springy-Store-Microservices.git
> git checkout staging
> docker-compose up
```
### Next version :
In the next version I'll continue the dev with the following fixes : 
-  Add Unit test using JUnit and mockito
-  Adding keycloak for login using JWT 
-  Send email for success reservation with the reference ID
-  Add security filter in the API-Gateway to secure the API
-  Add redis for cache management
-  Change the microservice user-service to customer-service for customer management
-  Add connect the room-service with an object store minaio to fetch room photos
-  Try to deploy it in kubernetes 
