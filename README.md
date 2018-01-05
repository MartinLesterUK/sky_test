# sky_test
Small project for Sky Interview

## Objective:
- The objective of this exercise is to design, deploy and provision a highly available service. The service will accept a POST request that will persist the timestamp of that event into a database. You should be considering for all parts of your solution, multi-DC, zones & redundancy of components.
- Please note that the design must be elastic based on demand!
- For any areas, which you have not considered to automate, please state these clearly and if possible, provide details of the solution you would have implemented including your experience/depth of knowledge of that area.
- Be prepared to be questioned and ready to explain your reasons in regards of your choice of solution.

## Restrictions:
- The choice of technology is up to you. For example, if you choose to use a NoSQL database or a Relational database is your choice.
- The provisioning tool suggested below is Ansible, however, you may use any tool of your choice for your automation.

## Questions and Tasks:
1. Explain with as much detail as you can of your high level design and explain why that would meet the requirements outlined above.
2. Provide details of your web API that will be used to submit a curl command (curl -X POST http:// <someip> /app) that will insert the date time stamp into your database. The api code should be well documented.
3. In addition, provide any automation for your backup/restore process you would implement.
4. Provide details of your Persistency Layer, with details of your cluster setup and configuration.
5. If you consider any Load Balancer or queuing service to be used, please be ready to explain the reasons and your suggested configurations of each.
6. Please consider monitoring and maintainability
7. Please explain how elastic your service is, what would be trigger points and how the scale up or down would actually work

## Homework Assignment before the interview
1. Provide details of your high level design that would meet the requirements outlined above.
- This design must be submitted 24 hours before the interview scheduled via pdf and must show a logical design
2. Create a proof of concept (Please note, the proof of concept should consist a single web-application and a single database)
   1. Create a GitHub project for this assignment
   2. Create an application with simple API that will be used to submit a curl command (curl -X POST http:// <someip> /app ) that will insert the date time stamp into your database.
   3. Build provisioning automation code ( using Vagrant ) to provision your database node and web node with the API you created.
   4. A readme file must be populated with your git project detailing your solution and how to run it.

- Please submit your solution 24 hrs before your interview to ...

** Please note we are expecting your design pdf, your git project containing a vagrantfile, provisioning code and the api code within your git repository. **

