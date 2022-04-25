

```
gcloud artifacts repositories create quickstart-docker-repo --repository-format=docker --location=us-west2 --description="Docker repository"

gcloud artifacts repositories list

```

Building the docker image
```
gcloud builds submit --region=us-west2 --tag us-west2-docker.pkg.dev/cloudbuildlearning1/quickstart-docker-repo/quickstart-image:tag1

```

![quickstartimageInartificatregistry](images/quickstartimageInartificatregistry.png)