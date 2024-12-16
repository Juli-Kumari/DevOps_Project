# DevOps_Project
Github Actions

## Advantages of Github Action over Jenkins
1. No installation needed e.g. no need to add plugins and all
2. Can execute jobs in parallel with no efforts 
3. Actions will be available for almost all possible steps (https://docs.github.com/en/actions/guides)
4. Access through to work with github actions

   ##Notes:-
   1. uses: actions/setup-java@v4  -> here 'actions' is present that's mean it's officially present in github action.
   2. uses: axrioty/setup-selenium -> someone has created this, we will use it our project.
      
## Workflow Triggers 
-> Workflow triggers are events that causes workflows to run.
-> There are so many way to trigeer a workflow
-> Path of YAML file
### .github ---> workflows ----> nightly_test.yml
-> Go to ACTION tab inside the GITHUB ----> to create a pipeline.
1. workflow-dispatch ----> Allows you to run this workflow manually from the Actions tab
2. issues  ----> tab present in GITHUB.
3. 
