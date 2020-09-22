# github-actons-auto-pull-request-merger
A github action workflow that generates pull request and merges them automatically upon pushing to development branch

#### STEP 1
####### Create a Personal Access Token
- Go to setting page on your profile icon
<img src="https://github.com/Mulubwa17/github-actons-auto-pull-request-merger/blob/master/public/settings.png"> 
- Create a personal access token
<img src="https://github.com/Mulubwa17/github-actons-auto-pull-request-merger/blob/master/public/pat.png"> 
#### STEP 2
####### Create your workflow
- Create a .github/workflows directory in the root of your project
- Inside the '.github/workflows' directory,create a yaml file that will have all the hobs required.
#### STEP 3
####### Define jobs inside your yaml file
- Define the name of your workflow
- Set a trigger event,e.g can be when a push is made to the development branch
- Define jobs to run after set trigger is actioned
- define the steps of the jobs,steps and environments
- Your yaml file should look like this :
<img src="https://github.com/Mulubwa17/github-actons-auto-pull-request-merger/blob/master/public/yaml.png"> 
#### STEP 4
####### Check your actions status
- Go to reposiroty tab labeled 'Actions'
<img src="https://github.com/Mulubwa17/github-actons-auto-pull-request-merger/blob/master/public/actions.png">
- Check the status of your workflow and jobs
<img src="https://github.com/Mulubwa17/github-actons-auto-pull-request-merger/blob/master/public/jobs.png

For More on Github Actions,click on the link : https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions.