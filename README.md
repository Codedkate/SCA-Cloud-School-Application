# SCA-Cloud-School-Application
This repository is about my technical assessment into she-code-cloud school.

The She Code Africa cloud School (in partnership with Deimos Cloud) is a 3months cohort-style, bootcamp program specifically targeted at ladies across Africa, looking to kick off or switch careers into the Site Reliability Engineering (SRE) field. 

# Pre-requisite
- Github account
- Docker account
- Docker installed in your machine.

# Deployment instructions
```Create a VM with Azure,AWS, GCP or use your PC.```


```Create a github respository called SCA Cloud School Application.``` 

```Create a folder called shecode,add Dockerfile and app files(index.html file) in the docker folder.```
![image1](https://github.com/Codedkate/pix/blob/main/shecodepix/d1.jpeg)

  ```Building image sudo docker build -t shecode-app:v1.0.0```
![image1](https://github.com/Codedkate/pix/blob/main/shecodepix/d2.jpeg)

 ```Confirm image was build sucessfuly.``` 
 ![build](https://github.com/Codedkate/pix/blob/main/shecodepix/d3.jpeg)
 
  ```Running a container from the image.```
  ![build](https://github.com/Codedkate/pix/blob/main/shecodepix/d4.jpeg)
  
  ```Confirm the container is running and can view the page on the browser and it shows the specified content.```
  ![build](https://github.com/Codedkate/pix/blob/main/shecodepix/d5.jpeg)

  ```Tagged the image and made it ready to be pushed to Docker Hub.```
  ![build](https://github.com/Codedkate/pix/blob/main/shecodepix/d6.jpeg)
  
  ```I pushed the image to my Docker Hub repository.```
  ![build](https://github.com/Codedkate/pix/blob/main/shecodepix/d7.jpeg)

 ```I confirmed the Image was pushed to my Docker Hub Repository.```
  ![build](https://github.com/Codedkate/pix/blob/main/shecodepix/d8.jpeg)
  
```Link to my deocker hub repository```
https://hub.docker.com/repository/docker/catherine247/shecode-app

```Documentation used```
https://docs.docker.com/engine/reference/builder/



