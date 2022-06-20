# Overview
This project involved the creation of a CI/CD pipeline. The pipeline achieves the creation of infrastructure, configurattion of infrastructure 
using Ansible. Testing and deployment of application, smoke tests and subsequent deployment to production

## Tools
- Ansible - configuration management
- AWS - Cloud provider
- Coudformation - Infrastructure as code
- Cicleci - CI/CD
- Vscode 

## Procedure
- Write source code using vscode
- Write cloudformation scripts for provisioning resources using vscode
- Highlight jobs in circleci `config.yml` file, provision resources in the jobs, configure resources, smoke test and deploy app.
- Push could to github and ensure workflow runs and passes.
- Check AWS console for provisioned resources and that the application works
