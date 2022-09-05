# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
- Cost: 
    + VM: Minimum 1 A0 - $13.19/month    
    + App Service: 1 F1 - Free tier $0/month
=> With cost optimization and application I don't care about performance, App Service is a great choice.

- Scalability:
    + Project is small and i can always scale up in the future if need as lower cost and configuration work if i were to need to scale on a VM
=> I don't care my application high demand for scalability, control the underlying OS and install software on the serve 
=> Can choose any

-Availability: 
    + The availability of the web app seems the same as compared to the VM but based on the extra user configuration and risk, I think the web app would have greater
    reliability and availability to be up and running, versus if it were on a VM tha needed to do restarts and OS maintenance
=>  App Service is a great choice.

- Workflow:
    + VM: Configuration of the application server in the VM
    + App service: Instant deployment
=> App service config very easy

_Justify your choice_
My solution for deploying the app: App Service
- _Justify your choice_
Because, lower cost, simple, faster to deploy than a VM. And App Service does not require the high maintenance, 
I can very easy upload project to my github repository
### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._

########################################## OPTIONAL: A URL to your Python App Service.
https://chengwebapp.azurewebsites.net