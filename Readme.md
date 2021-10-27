# CI build for pet-clinic application using Maven [![Build Status](https://travis-ci.org/spring-projects/spring-petclinic.png?branch=main)](https://travis-ci.org/spring-projects/spring-petclinic/)

### Clone the repository and fork it into your workspace

```
git clone https://github.com/HaierT/spring-petclinic.git
```

### Set up a new workflow on github
Go to Actions -> New workflow -> search for "Java with Maven" -> click on "set up this workflow" 
![actionMaven](https://user-images.githubusercontent.com/33791925/137982339-0f06fedb-345e-4f08-8bb8-efc46960b031.PNG)


### Setup the following labels as secrets parameters
Go to Settings -> Secrets -> New repository secret

Set label values as written in docker-compose.yml file

labels:
```
DB_NAME
DB_PASSWOR
DB_PORT
DB_USER
```
