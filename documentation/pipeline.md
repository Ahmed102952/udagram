# Pipeline Process

The pipeline is setup and connected with this GitHub repository in CircleCI.

## Order of commands

1. The pipeline uses orbs to install Node, the AWS cli and the EB cli.
2. It checks out the code from the repo
3. FrontEnd & BackEnd
    - install dependencies
    - lint code
    - build
    - deploy to EB
