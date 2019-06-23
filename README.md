# Spring3Hibernate - A Sample Maven based Java Application

The main goal of this awesome Java Webapp is to encourage people to dive deep in Java Application Architecture and how we can make delivery pipeline faster, easier and much reliable using **Continous Integration**.

## Dependencies

The list of dependencies are not quite long but yes we do have some dependencies.

- [X] **Docker** - Download Docker on your Machine



## How to Run

#### Manual Setup

#From CMD/Shell -> Run Following Command where docker-compose.yml is present inside folder

docker-compose up -d
(-d  -> detached mode For Running in background)

## This will run tomcat Server for Java Application and It will also use nginx server for reverse proxy for tomcat server.

# Run 127.0.0.1 from web browser to access web page

## MySQL is also running using this docker-compose file and mysql server is linked to tomcat server.

You need to update your code for connecting employeedb database and its table by creating new table based on your requirement.

Use post and get for retrieving data and inserting data into database.

#for stopping docker-compose

docker-compose down

### docker-compose -> Running multiple container
```

### Docker-hub link - https://hub.docker.com/u/abhisheknipun1