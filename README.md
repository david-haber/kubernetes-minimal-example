# kubernetes-minimal-example
This repo contains a job template and script to populate simple jobs among Kubernetes worker nodes.

## Instructions

Clone this repo to the cluster's master node and run

`./create_jobs {number of jobs you want to create}`

followed by

`kubectl create -f job_spects/`

You can then monitor the jobs with

`kubectl get pods`
