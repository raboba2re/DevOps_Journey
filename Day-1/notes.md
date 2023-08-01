# What is DevOps?

Devops can be seen as the union of people, process and products with the objective of delivery continous values to application end users.DevOps focuses  on people over process and process over tooling. It focus on accelerating software production from Ideation to production.

## Why DevOps?

 Initialy, sofrware development comprises of two department:

- The development team that is resposible for developing the plan, design and build the system. 
  
- The operation team that is responsible for managing and maintaining the infrastructure, systems, and applications in a software development environment. The operationt team gives the development team feedback on bugs that need to be fix and any new feature that need to be implemented.
  
During this time, the developement team will be iddle, waiting for feedback from the operation team. The result in delays, extended timeline and delay software development cycle. For example, the development team can move on to another team or feature, whiel the operation team continue to provide feadback from previous project or feature, reluting in long time delays or extention in the project closing date. 

To address this issue, the DevOps culture/Philosophy was developed to enable these teams work together. This brought about an infinity process of improving effitiancy and contstsnt activity.
The DevOps culture is implemented in several phase using different tools.

## Phase of DevOps

1. The first Phase of  Devops is the **Planning phase**, in this phase the development team draft out a plan for the project/application keeping in mind what  desire or objectives  of the application the user expect.

2. After planing, the next stage is the **Code phase** where different version of the application are developed and kept in a version control system such as Git. 
3. The next Phase is the **BUILD phase** where code are executed using tools like MAVEN.
4. After the completion of the **BUILD**, the code is then tested in for bugs and errors in the **TEST phase** using tool such as selenium.
5. After a successful test, the code is said to be ready for deployment and sent to the operation team.  
6. With   tools like Ansible, Docker and *Kubernetes*, the operation team deploy the code to a working enviroment. 
7. After deploying the product, the team continue to monitor the code  with automation tools like **Nagios**. 
8. Any feedback obtain from the Ansible, Docker and Kubernetes, is sent to the development team, forming the code of devops lifecyle, which is the integration phase. Using tools like Jenkins to send the code for buid and testing. 