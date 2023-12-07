
| NAME| PROMPT | DESCRIPTION | EXAMPLE |
|-|-|-|-|
| app.yaml| create nginx deployment | YAML to define the basic schema of nginx              | [app.yaml](app.yaml)                 |
| app-livenessProbe.yaml      | create nginx livenessProbe | YAML to define a liveness probe for nginx                    | [app-livenessProbe.yaml](app-livenessProbe.yaml) |
| app-readinessProbe.yaml     | create nginx readinessProbe | YAML to define a readiness probe for nginx                   | [app-readinessProbe.yaml](app-readinessProbe.yaml) |
| app-volumeMounts.yaml       | create nginx volumeMounts | YAML to define and configure storage volumes nginx       | [app-volumeMounts.yaml](app-volumeMounts.yaml) |
| app-cronjob.yaml            | create nginx cronjob| YAML to define a cron job for nginx                       | [app-cronjob.yaml](app-cronjob.yaml) |
| app-job.yaml                |create nginx job | YAML to define a job for nginx                            | [app-job.yaml](app-job.yaml) |
| app-multicontainer.yaml     | create nginx multicontainer | YAML to define a pod that runs more than one container                  | [app-multicontainer.yaml](app-multicontainer.yaml) |
| app-resources.yaml          | create nginx resources | YAML to configure resource requests and limits for nginx     | [app-resources.yaml](app-resources.yaml) |
| app-secret-env.yaml         | create nginx secret-env    | YAML to define environment variables using secrets                      | [app-secret-env.yaml](app-secret-env.yaml) |