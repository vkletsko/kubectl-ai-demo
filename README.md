# kubectl-ai-demo
examples of usage AI tools in kubernetes plugins
| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| nginx-deployment | create deploy nginx | Deployment from official Nginx Docker image | [app.yaml](/yaml/app.yaml) |
| liveness-probe | create liveness probe every 30 seconds for nginx | every 30 seconds liveness probe for Nginx pod  | [app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml) |
| readiness-probe | create readiness probe every 30 seconds for nginx | every 30 seconds readiness probe for Nginx pod  | [app-readinessProbe.yaml](/yaml/app-readinessProbe.yaml) |
| volume-mounts | create volume mounts for nginx | Mounts volume to nginx pod | [app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml) |
| cronjob-pod | create cron job running daily at 9 AM with echo "hello world" | cron job running daily at 9 AM with echo "hello world" | [app-cronjob.yaml](/yaml/app-cronjob.yaml) |
| job-pod | create job archiving data from postgres table | archiving data from postgres table | [app-job.yaml](/yaml/app-job.yaml) |
| multicontainer-pod | create multicontainer pod nginx with ubuntu and common volume | Pod contained 2 containers (Ubuntu and Nginx) and volume | [app-multicontainer.yaml](/yaml/app-multicontainer.yaml) |
| resources-pod | create resources pod | Resources pod | [app-resources.yaml](/yaml/app-resources.yaml) |
| secret-env-pod | create secret env pod | Secret env pod | [app-secret-env.yaml](/yaml/app-secret-env.yaml) |