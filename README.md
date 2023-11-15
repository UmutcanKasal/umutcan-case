#     I started with setting up a minikube in my local environment. But after that I realized that I'm using Windows as OS(which is making it difficult)
#     and started to build on GCP kubernetes cluster. After setting HELM and ARGOCD on cluster with ideal namespace,
#     I produced one repository on Docker Hub and created 2 tags on it. 
#     I created a Docker image locally for a Node.js app, then tagged that image and pushed it to Docker Hub.
#     Then build an image with Docker to use it on helm chart.
#     I build the ARGOCD application that is connected to Helm charts repo. It automatically created the pod for the test environment.
#     I tested the application with pushing changes and saw it is synced.
#     To be honest, nowadays I'm participating in kind of busy project thats why I was able to spare that much time on that case.
#     Thank you. 

#     To reach out my ARGOCD panel : 34.118.110.23   ID = admin  Pass=Umutcan143

#     URLs=https://github.com/UmutcanKasal/umutcan-case.git
#          https://hub.docker.com/repository/docker/umutcan143/umutcan-case-study/general>