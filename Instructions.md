## Deploy a High-Availability WebApp using Cloudformation

### Create the Stacks
There are two templates in yaml format and two parameters file in json format. One for creating network infrastructures and another for creating servers, security groups, loadbalancer and so on.
The two stacks can be created as follows -

![create_stacks](./images/create_stacks.png)

First, **NomanAppInfrastructure** stack is created completely and then **NomanAppServers** stack is created. 

![infrastructure](./images/NomanWebAppInfrastructure.png)

![servers](./images/NomanWebAppServers.png)

Once the stacks are created successfully, verify other services from the AWS console. In this case, all the services' screenshots are given in the **images/screenshots** directory.

Thank you.