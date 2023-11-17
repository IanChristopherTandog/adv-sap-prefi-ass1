## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).

-Service-oriented architecture (SOA) is a method of software development that uses software components called services to create business applications. Each service provides a business capability, and services can also communicate with each other across platforms and languages. Developers use SOA to reuse services in different systems or combine several independent services to perform complex tasks.

For example, multiple business processes in an organization require the user authentication functionality. Instead of rewriting the authentication code for all business processes, you can create a single authentication service and reuse it for all applications. Similarly, almost all systems across a healthcare organization, such as patient management systems and electronic health record (EHR) systems, need to register patients. These systems can call a single, common service to perform the patient registration task.

2. List and discuss the characteristics of SOA.

-It supports loose coupling everywhere in the project: meaning the services and components in SOA are not very dependent with each other, this way if you change a service then it wont cause too much trouble for the other services.
 
-SOA supports interoperability: meaning any client can use the services even if their knowledge is not directly what type of technology the SOA uses. Its components being not very dependent with each other allows its services and system to work work together regardless of types of technologies, platform or programming languages it uses.

-It increases the quality of service: because of each services are like independent with each other therefore each service is specialized with something and can focus in it which helps improve the quality of service it will provide.

-It supports vendor diversity: SOA can use diverse technologies from more than just one vendor that can be utilized for different services.

-It promotes discovery and federation: SOA promotes discovery because it allows each components and services utilize each other. SOA also supports federation because it allows the distribution of its services to different loactions, group or other organizations

-It is location-transparent: SOA can be distributed to different location no matter where they are.

-It is still maturing and achievable idea: its capabality to grow is still there because it can adapt to the continues growth of technology

3. Define Microservices.

-Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.

Microservices architectures make applications easier to scale and faster to develop, enabling innovation and accelerating time-to-market for new features.

4. List and discuss the benefits of using Microservices.

- Improved Scalability: Each services has their own and independent resources, meaning if one mciroservice has problems with its resources or if it is experiencing high traffics then other microservices wont be affected  because it runs a different resources. This also allow changes like updates to happen without having to shutdown the whole system.

-Better Fault Isolation for More Resilient Applications: Problems like failures of a service are isolated or contained so that it wont affect other services, it is more effective because each service runs independently to others.

- Programming Language and Technology Agnostic: Developers can connect services that are built with diverse programming languages and Technology. This also allows it to adapt to new technology.

- Better Data Security and Compliance: Microservices offers each services to focus on a specific task that way a specific service can focus in implementing security measures at the service level reducing the risk of having problems when storing data in a signle database.

5. List and discuss the similarities and differences of SOA and Microservices.

Similarities:

- Its services are both independent to other services.
- Both supports the use of diverse number of Programming languages and technology
- Both allows each services/ microservices to grow independently

Differences;

-In SOA each service can connect with each other, in Microservice each microservice is smaller and specialized in a single task only and it does not share its resources to other microservice.
-SOA has a signle data storage that is shared by other services, Microservices dont share a signle storage because each microservice has its own storage.
-Microservice is designed to scale in the cloud environment, SOA is not.


References:

https://aws.amazon.com/what-is/service-oriented-architecture/#:~:text=you%20implement%20microservices%3F-,What%20is%20service%2Doriented%20architecture%3F,other%20across%20platforms%20and%20languages.

https://www.xenonstack.com/insights/service-oriented-architecture

https://blog.dreamfactory.com/7-key-benefits-of-microservices/


