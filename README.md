## Description

Here, In this template, we will pass the parameters for the kubernetes manifest at the runtime using the kustomization approach in the deployment.

---
##### Pre-Requisite


* Azure Account
* Install Dependencies as mentioned in the `rendered.yml` pipeline step.

---
### Steps

* Login into your Azure portal.
* Add the Kubernetes manifest from the `Kubernetes/base` folder.
* Add the kustomize file with all the defined resources.
* Run the pipeline `rendered.yml` from your Azure DevOps account and deploy your application using the kustomization approach.


---

#### Note

* Please change your account details in the respective mentioned areas in the files. 

---
 
