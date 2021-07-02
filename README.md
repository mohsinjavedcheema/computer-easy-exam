Agile vs DevOps

DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that focuses on collaboration, customer feedback and small rapid releases.
DevOps focuses on constant testing and delivery while the Agile process focuses on constant changes.
DevOps requires relatively a large team while Agile requires a small team.
DevOps leverages both shifts left and right principles, on the other hand, Agile leverage shift-left principle.
The target area of Agile is Software development whereas the Target area of DevOps is to give end-to-end business solutions and fast delivery.
DevOps focuses more on operational and business readiness whereas Agile focuses on functional and non-function readiness.

Define CI, Continuous Delivery & Continuous Deployment
Continuous integration
Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid integration challenges that can happen when waiting for release day to merge changes into the release branch.
Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.

Continuous delivery
Continuous delivery is an extension of continuous integration since it automatically deploys all code changes to a testing and/or production environment after the build stage. 
This means that on top of automated testing, you have an automated release process and you can deploy your application any time by clicking a button.
In theory, with continuous delivery, you can decide to release daily, weekly, fortnightly, or whatever suits your business requirements. However, if you truly want to get the benefits of continuous delivery, you should deploy to production as early as possible to make sure that you release small batches that are easy to troubleshoot in case of a problem.

Continuous deployment
Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.
Continuous deployment is an excellent way to accelerate the feedback loop with your customers and take pressure off the team as there isn't a Release Day anymore. Developers can focus on building software, and they see their work go live minutes after they've finished working on it.

What are the benefits of Cloud Computing
Using different services, cloud computing offers more benefits than traditional computing. Cost saving, scalability, mobile storage, anytime anywhere access, better security, energy saving, environment benefits are some of benefits of the cloud computing.

Difference b/w Git & Github
Git is a revision control system, a tool to manage your source code history.

GitHub is a hosting service for Git repositories.

So they are not the same thing: Git is the tool, GitHub is the service for projects that use Git.

Stages of Git
Commited (stored in local database)
Modified (file changed but not commited to database)
Staged (modified file is marked to go into the next commit snapshot)

3 methods of git reset?
Soft
Mixed
Hard

Explain Docker Containers vs VMs
First, a container is more lightweight than a VM. A container includes only the executables and its dependencies and different containers on the same machine share the same OS(operating system). While a VM  contains a full set of OS, and different VMs do not share the OS. A VM can run an OS that is different from its host machine, while the container needs to use the same OS as the host. Second, the hypervisor, such s VMware ESXi and KVM, is necessary in a VM environment, while it is not required for containers. For a VM, it needs to act as an independent machine which has the control of all its resources. However, in act, a VM runs in a non-privileged mode which does not have the capability to execute many privileged instructions. Therefore, a hypervisor is needed to translate a VM instruction into an instruction that can be executed by the host. On the contrary, since a container does not need to execute any privileged instruction, it communicates with the OS through the system calls, thus no other layer is required in between. Third, each VM has its own image file, while different containers may share some of their images. More specifically, container images are created in a layered manner,in which a new image can be created upon an existing image by adding another layer that contains the difference between the two. The image files of different VMs are isolated from each other.
