
# Deployment Notes


## Jargon
_"Single Responsibility Principle"_
 a unit of work should do one thing and one thing only (could be a whole component)
>&ndash; Do one thing really well. Only one reason to change


## Deployment
- extract configuration into environment variable
- set up a workflow where we commit our changes, push them to a branch on github and the app gets updated automatically 
>Continuous Deployment


## adding a new remote pointing to a url

>git remote add name url

now you can
 >git push name master

 on a different webservice for instance (bitbucket)

 ## Package.json
 devdependencies will not get installed on heroku because we are saying we only use that in development