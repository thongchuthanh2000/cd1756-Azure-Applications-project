# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
_Justify your choice_
My solution for deploying the app: App Service
- _Justify your choice_
Because, lower cost, simple, faster to deploy than a VM. And App Service does not require the high maintenance, 
I can very easy upload project to my github repository and auto deploy when I commit code or write cmd: 
az webapp up \
--name chengwebapp \
--verbose
Base on the costs, scalability, workflow analysis i chose the Web App Service for deploy 

### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._
