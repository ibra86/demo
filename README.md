# Kubernetes OpenAI created manifests

This repository contains various Kubernetes manifest files for deploying the application.

| Name | Prompt | Description| Example |
|----------------------------|------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| app.yaml | kubectl ai "create Basic application deployment manifest" | Basic application deployment| [app.yaml](./yaml/app.yaml) |
| app-livenessProbe.yaml | kubectl ai "create Configuring liveness probe for application manifest" | Configuring liveness probe for application | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml| kubectl ai "create Configuring readiness probe for application manifest" | Configuring readiness probe for application| [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml| kubectl ai "create Mounting volumes for application manifest" | Mounting volumes for application| [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | kubectl ai "create Configuring a cron job for the application manifest" | Configuring a cron job for the application | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| app-job.yaml | kubectl ai "create Configuring a job for the application manifest" | Configuring a job for the application| [app-job.yaml](./yaml/app-job.yaml) |
| app-multicontainer.yaml| kubectl ai "create Deployment with multiple containers manifest" | Deployment with multiple containers| [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml | kubectl ai "create Resource constraints for the application manifest" | Resource constraints for the application | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml| kubectl ai "create Using secrets as environment variables manifest" | Using secrets as environment variables | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |
