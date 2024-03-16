# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

A solution with a combination of multiple VMs would provide high availability and scalability. 
VMs are on the other hand more expensive and everything has to be set up on the VM by the developer himself 
in order to get the app working, which means much more work beforehand and the workflow would also be
more complicated during deployment. 

A solution with App Services would also provide high availability and supports auto-scaling.
It is a cheaper solution than VMs. 
A developer would only need to develop the app and a continuous deployment model is possible using e.g. 
GitHub, which makes the workflow very easy.
Such a solution would not have the flexibility and full control of a VM solution and also has 
some hardware limitations.

I choose an App Service solution for deploying this app, because
* it provides all that is necessary for deploying the app, no additional software except for the Python libraries needed.
* it is cheaper
* it also provides high availability and is scalable
* it makes deployment very easy
* there are no high demands on hardware for this basic app

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the app would use additional software next to the Python development, a VM solution would be necessary.
If the app would be widely used and demand much more computing power, a VM solution would be more appropriate.