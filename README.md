# dockerhub-stub
This repo is basically used only me for creating an organization's automated build on dockerhub. Since dockerhub currently does not have GUI for creating an automated build which links to organzation's repo on github.

To create an organization's automated-build, just go to user's automatded build and change the url in the form of:-

    https://hub.docker.com/add/automated-build/github/form/{organization_on_github}/{repo_name_on_github}/?namespace={organization_on_dockerhub}

for example

    https://hub.docker.com/add/automated-build/github/form/wongnai/dockerhub-stub/?namespace=wongnai
