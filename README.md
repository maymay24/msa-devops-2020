# msa-devops-2020

Website URL: https://msa-2020-devops-may.azurewebsites.net

Description:
For the build pipeline, the "trigger" section in *azure-pipelines.yml* is specified with the command '\*' to indicate that all branches (master and develop) will cause a CI build to run. 
For the release pipeline, a new branch filter for "develop" was added so that builds from the "develop" branch would also be released.
