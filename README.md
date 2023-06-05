# Kubernetes Manifests

This repository contains various Kubernetes manifest files for deploying the application.

| Name                       | Prompt                 | Description                                          | Example                                                                                           |
|----------------------------|------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| app.yaml                   |                      | Basic application deployment                          | [app.yaml](./manifests/app.yaml)                                                                 |
| app-livenessProbe.yaml     |                      | Configuring liveness probe for application           | [app-livenessProbe.yaml](./manifests/app-livenessProbe.yaml)                                     |
| app-readinessProbe.yaml    |                      | Configuring readiness probe for application          | [app-readinessProbe.yaml](./manifests/app-readinessProbe.yaml)                                   |
| app-volumeMounts.yaml      |                      | Mounting volumes for application                      | [app-volumeMounts.yaml](./manifests/app-volumeMounts.yaml)                                       |
| app-cronjob.yaml           |                      | Configuring a cron job for the application           | [app-cronjob.yaml](./manifests/app-cronjob.yaml)                                                 |
| app-job.yaml               |                      | Configuring a job for the application                | [app-job.yaml](./manifests/app-job.yaml)                                                         |
| app-multicontainer.yaml    |                      | Deployment with multiple containers                  | [app-multicontainer.yaml](./manifests/app-multicontainer.yaml)                                   |
| app-resources.yaml         |                      | Resource constraints for the application             | [app-resources.yaml](./manifests/app-resources.yaml)                                             |
| app-secret-env.yaml        |                      | Using secrets as environment variables               | [app-secret-env.yaml](./manifests/app-secret-env.yaml)                                           |
