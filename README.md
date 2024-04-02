# RVL_Sec_task

In this repo I will:

1) Create CI/CD workflow in GitHub Actions

Build the docker image from the docker file
docker build -t nginx .

Upload the docker after creation of Image:

docker tag nginx localhost:5000/nginx
docker push localhost:5000/nginx


2) Create a bash script that performs the following tasks using yq
