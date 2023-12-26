<div align="center">
  <h1 style="color: red;">Solve github-action-k8s-helm challenge :globe_with_meridians::hammer_and_wrench:</h1>
</div> 

##
## :zap: DevOps Assignment

![Capture](https://github.com/AbdelrhmanAli123/github-action-k8s-helm-challenge/assets/133269614/8be0f33e-7294-4eef-b605-2e2262ac5fa4)

## 
## :scroll: Overview

This repository presents a robust solution for deploying applications in a Kubernetes cluster while incorporating CI/CD practices using GitHub Actions. I created three branches - the main branch for primary development, a second branch for creating pull requests, and the last one for saving the Helm chart using GitHub Pages. This branch strategy enhances collaboration, code review, and Helm chart versioning, providing a comprehensive solution for deploying and managing applications in a Kubernetes environment.

## :diamond_shape_with_a_dot_inside: Branches:
- **Main Branch:** The primary branch containing the latest stable code.
- **Pull Request Branch:** A branch specifically for creating and managing pull requests.
- **GitHub Pages Branch:** Created a dedicated branch for storing the Helm chart using GitHub Pages. This branch may contain documentation and artifacts related to the Helm chart.

## :diamond_shape_with_a_dot_inside: Assumptions

- I assume that you have k8s cluster running to deploy and perform the task, in my case i used AWS EKS.


## ⌛  Steps

1. **create the k8s manifest files as required in task**

2. **Package the k8s files using helm chart**   
    
3. ** create intial work flow to deploy you helm chart on k8s cluster for the first time**

   note: You can deploy the cart manully in the first time.

4. **Create second wokflow for creating the pull request**

5. **Create branch that's used to open the pull request from and trigger the PR workflow**

6. **create empty branch for storing the helm chart in it**

7. **create last work flow for merging the pull request in the cluster**

8. **run the first workflow manaully to deploy the helm chart**

![deploy](https://github.com/AbdelrhmanAli123/github-action-k8s-helm-challenge/assets/133269614/46e6d71d-9096-4da4-acd0-79902ae38068)

9. **do any chage in the pull request branch and then open the PR, it will trigger the workflow immediately**

![PR](https://github.com/AbdelrhmanAli123/github-action-k8s-helm-challenge/assets/133269614/32eae02a-eead-4f5e-b0c9-f6ab77c03352)

10. **enable the github pages on the repo that we created to store the helm chart**

![github pages](https://github.com/AbdelrhmanAli123/github-action-k8s-helm-challenge/assets/133269614/416db5ef-797b-4b02-9c6f-ea3249e5d775)

11. **merge the pull request and then you will see that the merge pipeline work flow triggered **
    
![merge](https://github.com/AbdelrhmanAli123/github-action-k8s-helm-challenge/assets/133269614/a2d93593-a8e4-4bae-a2a9-b89abfaa491c)


## :rocket: Conclusion

In conclusion, this DevOps assignment employs a streamlined approach to deploy applications in a Kubernetes cluster, integrating CI/CD practices through GitHub Actions. The key steps include creating Kubernetes manifest files, packaging them using Helm charts, and establishing a robust branch strategy with dedicated workflows. By leveraging GitHub Actions, we've automated the deployment process, enhanced collaboration through pull requests, and ensured Helm chart versioning. Additionally, the implementation of GitHub Pages for Helm chart storage further facilitates accessibility and documentation. The combination of these steps results in an efficient and scalable solution for deploying and managing applications in a Kubernetes environment.


