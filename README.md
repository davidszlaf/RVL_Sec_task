# RVL_Sec_task

In this repo I will:

Step_1) Create CI/CD workflow in GitHub Actions

Build the docker image from the docker file
docker build -t nginx .

*) Upload the docker after creation of Image:

docker tag nginx localhost:5000/nginx
docker push localhost:5000/nginx


*) Deploy k8s cluster based on a kind_config file:
kind create cluster --config=kind.config.yaml

*) Pull the docker image from docker registry:
docker pull localhost:5000/nginx



Step_2) Create a bash script that performs the following tasks using yq
