# Deployment

## Digital Ocean Kubernetes actions
- Check out [the official Gitbug Action](https://github.com/marketplace/actions/digitalocean-kubernetes)

## Google Cloud

### Gcloud
- Install `gcloud` [here](https://cloud.google.com/sdk/docs/install)
- Do `gcloud init`
- Add the container registry: `gcloud auth configure-docker`

## Tagging an image
- Tag the image by doing: `docker tag ffk_services_admin:latest gcr.io/staging-services-294420/ffk-services-admin:latest`
    - `staging-services-294420` is the project name
- Push to the registry: `docker push gcr.io/staging-services-294420/ffk-services-admin:latest`
