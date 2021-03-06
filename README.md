# Ops compilation

## Introduction

This is my devops/infrastructure stack-and-module compilation that is easy to set-up for multiple projects from MVPs to large-scale types.

### Tech stacks:

- Terraform
- Serverless framework (AWS cloudformation)
- Ansible
- Docker & Docker swarm
- Scripting languages (Python, NodeJS, Bash,...)
- CI frameworks (Github actions, CircleCI,...)

### Structure:
  
- `/core`: Contains core setup files (ansible playbooks/roles, terraform modules/stacks, CI templates,...).
- `/config`: Contains templated configuration files for each infrastructure stacks, that could be customized depends on each project needs (`Dockerfile`, `docker-compose.yaml`, `yaml` config file,...)
- `/resources`: Extra resources/documentation that is attached for some infrastructure stacks/modules
## Notes:

If you guys want to contribute, please open a PR from the master branch, I'll review it if possible :grinning:, though I'm quite busy.

Also, any suggestions are welcome by opening new issues in Github, I'll try to discuss on the feature/bug-fixes or answering the questions from you guys.

Thanks again for noticing. Please leave a star if you find this repo useful.
