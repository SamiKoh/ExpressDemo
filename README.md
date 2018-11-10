# Express Demo

This is a web development homework based on [Mozilla tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)


To build from repository

```
docker build https://github.com/SamiKoh/ExpressDemo.git -t imagename
```` 

To list images
```
docker images -a
```
To spin up a container from image 
```
docker run --detach --publish 8080:3000 --name containername imagename
```

To list containers
```
docker ps -a
```
To stop a process

```
docker stop containername
```

To delete container
```
docker rm containername
```
To delete image 
```
docker rmi imagename
```