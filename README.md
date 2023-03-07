# Devops_1
docker build -t andriipe/devopsapp:v1 .
docker run -p 80:80 --cpu-shares=512 --memory=512m andriipe/devopsapp:v1
docker login
docker push andriipe/devopsapp:v1
