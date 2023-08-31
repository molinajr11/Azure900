# Azure900 ☁️
What is cloud 🌥 computing? 

# Shared responsibilities model
- Coustumer have divide responsabilities for all sorts of things like security
- on premises responsabilitys : the responsability its all yours
# Cloud virtual machine resposability: 
- its a mix and the client needs to handle
- Devices 
- User accounts 🕴️
- Data 
- Authentication platform
- Application Settings
- Network and firewall settings
And Azures works whit ☁️🏪
Building Security
Physical network security
Physical computer security
- Operation System patches
# Softare as a Software (Saas) Responsibility:
on the side of client 🤺 : Data, Devices, User Accounts , Authentication platform
on side of azure ☁️ 🔐 : Application Settings, Network and firewall settings, Operating system patches , 
Physical computer security , physical network security , Building security
RESUME
<img width="838" alt="image" src="https://github.com/molinajr11/Azure900/assets/105083946/ba23cb47-fdd4-41f8-8e02-8a0dcca142b4">

# Public Cloud: ☁️ 
- available to anyone
- just pay for the services
- if its a commpany azure provides licenses, credids thats still the public cloud.

# private cloud
- private newtworks is common used for goubertnet and bannks
- confidential resources

# Hybrid cloud
 is a computing environment that combines the use of both private and public cloud infrastructure. It allows organizations to leverage the benefits of both types of clouds 

# Benefits of Cloud Computing :earth_americas
# High Availability
The ability of a system to be accessible and usable by users when they need it.
- A conscious effort to avoid the obvious sources of downtime.
- Ability of a system to remain operational to users during planned or unplanned outages.
**Planned Outages** ⏰
they are controlled Outages:
- Operating System security patches.
- Application updates.
- Hardware replacement.
- Migrating to a new hosting provider.
**Unplanned Outages** ☄️
- Hardware failure
- Network disruptions
- Power outages
- Natural disasters
- Cyber attacks
- Software bugs
- Poor scaling/ architecture desing
**Methods to mitigate Planned Outages** 🧮
- Gradual deploymnet strategy
- Testing and monitoring of deploymnet
- Easy rollback plan
- Small deployments
- Frequent deployments
- Automation    

# Scalability 🪜
The abiliy of a system to accommodate increasing demand by adding or removing resources as needed.
Benefits:
- it allows a system to adapt to changing usage patterns and handle increased traffic without requiring changes to the application code or system desing.
**Vertical Scaling**
- Also called "scaling up" or "scaling down"
- Adding more resources to a single server
- Increase the amount of memory, the number of CPUs
- There is an upper limit to this
- Azure -96 vCPus, 384 Gb memory
- Does not improve availability  
**Horizontal Scaling** 🐳 🐳 🐳
- Also called "Scaling out" or "Scaling in"
- Adding more servers to a system
- No limits to scaling
- Additional complexities for a load balancing
- Can improve availability.

# Elasticity 🏹 (autoscaling) 
the ability of a system to quickly and easily scale up or down the amount of resources that a system uses in response to changing demand
- Has to involve some sort of automation
- adds resources when it exceeds a limit for beging busy.
- remove resources when it falls below a limit for being not busy.
-  More efficient and cost-effective use of resources.     

# Reliability (Safety)
the ability of the system to function with a high degree of accuracy
How is reliability achived?
- auto-Scaling
- Multi-region deployments
- Data backup and replication

# Predictability
- Autoscaling
- Load balancing
- Different instance types sizes pricing tiers
- Cost management tools
- API
- Pricing calculators

# Security Benefit
- Microsoft Security Response Center (Msrc)
- Always-on DDos
- Azure Policy and Blueprint
- Roled-based access control (Rbac)
- Azure active Directory
- Encryption by default
- Dozens of security services like firewall

# Governance
- Azure policy  and blueprint
- management groups 
- custom roles
- Soft delete
# Managability
# Management of the  cloud
- Templates
- Automation
- Scaling
- Monitoring and alerts
- self-healing
Is it Archived
Azure Portal, CLI, PowerShell, Cloud Shell, Rest Apis,

# Cloud Service Types

# Infrastructure as a Service (Iass)
- These are the essential services of technology
- Computing: Virtual Machines
- Storage: hard disk, blobs, files, queues, and tables.
- Networking: doesn't have a cost
- Cloud replacements of real-world things.

# Platform as a Service(Pass)
Middleware, development tools, database servers, and more.
**Pass computing**: Azure app services, Simply upload your code and configuration to Azure, and it runs your code without needing to worry about the VM underneath
- includes Scaling features, Ci/CD, containers, staging and development environments, etc.
**Pass Storage**: Managed Storage is an example, Azure SQL Database. Freed from worrying about the server VM itself or the hard disk itself.
**Pass Networking**
- Azure Front Door is an example of this
- Or Load Balancer
- Or Firewall
- These are software applications that perform networking tasks.

# Software as a Service (Saas) Aps
- Cloud apps.
- Tools such as Office 365, OneDrive, and Skype.
- The app is ready to be used and you simply need to set it up and use it.
