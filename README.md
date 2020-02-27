# Jira/Core integration

This is a simple integration between Jira v8.7.1 (from https://hub.docker.com/u/atlassian) and CloudBees Core Modern 2.190.3.2 (Helm chart - cloudbees-core-3.7.0+ffcae9c08fc6). Both applications were deployed in K8s - 1.13.12 on GKE.

* Both pipelines use containers (in Kubernetes) to execute the stages. 
* This example is just to use as guidance for your own pipelines. Use at your own risk.
* This setup is not using any plugin and is based in curl commands.

## Prereqs:

* Install CloudBees Core (if needed) 

https://docs.cloudbees.com/docs/cloudbees-core/latest/gke-install-guide/installing-gke-using-helm

* Install Jira (if needed) 

https://hub.docker.com/r/atlassian/jira-software

## Testing the pipelines in your Master

* Create two pipeline jobs in your master. Click in "New Item":

![new-item](images/new-item.png)






