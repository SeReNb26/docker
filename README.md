# Docker
![docker](https://blog.seeweb.it/wp-content/uploads/2015/06/homepage-docker-logo.png)

#### This project is a simple example how to use docker with spring boot applications;

<br/>

#### Project contain only 1 end-point ("/") that print "Hello, World!" message;

<br>

#### Dockerfile -> FROM, COPY, ENTRYPOINT
#### Commands: mvn package, docker build -t {name of new image} ., docker run -p 8080:8080 {name of new image}


## Instructions for launching

<ol>
    <li>
        Install Docker on your OS.
    </li>
    <li>
        Run following commands in your OS console.
    <ul>
        <li>
            docker pull serenb/spring-boot-docker
        </li>
        <li>
            docker run -p 8080:8080 serenb/spring-boot-docker
        </li>
        <li>
            docker start {new container name}
        </li>
    </ul>
    </li>
    <li>
        Go to http://localhost:8080/, and you will see the "Hello, world!" message.
    </li>
</ol>
