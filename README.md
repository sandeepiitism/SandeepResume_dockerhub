## This is flask application for resume hosted on DockerHub using CI/CD pipeline

### How to run

```bash
docker pull sandeepiitism/resumedocker-app
docker run -d -p 5000:5000 --name resume-app sandeepiitism/resumedocker-app
http://localhost:5000


### to remove
docker stop resumedocker-app
docker rm resumedocker-app
```
