# windows-vm-job-runner

This cronjob assumes you have a jenkins job to restart a windows vm. It also assumes you have a running k8s cluster, and helm charts v3 installed

1 - Clone this repository
1 - Replace the values in the `values.yaml`
1 - Run `helm install windows-vm-job-runner windows-vm-job-runner -n=<namespace>`
