# Project Title: 

Build a CI/CD pipeline using CLoud-Build to auto-deploy a dockerize image of static website on GCP Cloud.

# Description: 

Build a CI/CD pipeline using Cloud Build service of GCP Cloud. Which build a docker image of static website deploy on NGINX server.

# Project Structure:

GCP-NGINX-Pipeline
├── cloudbuild.yaml
├── README.md
└── webapp-nginx
    ├── Dockerfile
    ├── error_404.html
    ├── index.html
    └── nginx.conf

# Goals:

1. To automate the deployment process of static website that ensure efficient and reliable deployments.

# Tech Stack: 

1. Github
2. GCP (Google Cloud Platform) Account

# CI/CD Pipeline Flow:

1. Build - Test - Deploy

Code push to Github Repo - code Build will trigger on (push to a branch) - Docker image will build - Docker Image will push to nginx-repo - Deploy container to Cloud run service - You will get a link to access website


# Result:

1. CI/CD pipeline fully automated no need of manual efforts.



By Lalit Kumar Gautam