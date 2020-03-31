# watchtower
## Info About to watchtower 
Watchtower is the way to update container from respected docker registry 
Inshort watchtower is an automated container monitoring and updating tool
Watchtower automatic detects changes and update / create the container

## Creating a container of watchtower to start monitoring 
```
docker run -d \
    --name watchtower \
    -v /var/run/docker.sock:/var/run/docker.sock \
    containrrr/watchtower
    
```
## Above watchtower container will check changes in the interval of 5 minutes

## changing the interval time to 30 seconds
```
docker run -d \
    --name watchtower \
    -v /var/run/docker.sock:/var/run/docker.sock \
    containrrr/watchtower -i 30
    
  ```
  
  ## To read more about watchtower 
  watchtower link  [official watchtower link](https://containrrr.github.io/watchtower/)  <br/>
  
  
  Enjoy Reading  :p)
