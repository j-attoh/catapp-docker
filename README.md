# catapp-docker
Docker || Docker Compose Files for the Catalyst App

# run API 
  - docker compose up 
  
# pull dowm API 
  - docker compose down 
  
# pull dowm API as well as the DB Data 
  - docker compose down --volumes 
  
 check out the [docker](https://docs.docker.com/) && [docker compose](https://docs.docker.com/compose/) documentation for more details 
 
# NOTE ( FOR CLARITY)
  Api can be found/located at  **localhost:8080/docs** after running the "docker compose up" command
  
# NOTE 
    - Production API would use PostgreSQL/MySQL as the database as well as other DB options as at when necessary 
    - For now sqlite would be preferred due to its relative smaller size and easier config for development purposes
    - Kindly take note
    
