# github-actons-auto-pull-request-merger
A github action workflow that generates pull request and merges them automatically upon pushing to development branch

#### STEP 1
####### Create a Personal Access Token
- Go to setting page on your profile icon
<img src=> 
- Create a personal access token
<img src=> 
#### STEP 2
####### Create your workflow
- Create a .github/workflows directory in the root of your project
- Inside the '.github/workflows' directory,create a yaml file that will have all the hobs required.
#### STEP 3
####### Define jobs inside your yaml file
- Define the name of your workflow
- Set a trigger event,e.g can be when a push is made to the development branch
- Define jobs to run after set trigger is actioned
- define the steps of the job

<img src=""> 


For More on Github Actions,click on the link : https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions.