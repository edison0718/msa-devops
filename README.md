# msa-devops

deployed website:
https://msa-devops-2020-p1.azurewebsites.net/

First, a window web app resource is created in Microsoft Azure with a name for the webapp.

Second, to build the pipeline, a new organization is created in Azure DevOps with the codes in github.
I have modified the starter pipeline YAML file by add the develop branch("- develop") when the pipeline is triggered,
, created variables for root directory and buil directory to access the pipeline, use the npm in the pipeline by install
node.js and lastly, to archive the build then publish it.

lastly, a release pipeline is created to deploy the artifact in the build pipeline with credential and the app service.
then set the continuous deployment trigger with master branch and create the first release.
