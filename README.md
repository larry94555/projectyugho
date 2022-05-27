# project yugho

Can self-run applications be so easy to create that non-technical folks with an idea can create a business presence?

A typical software system requires developers to build it and developers to maintain it.  This also requires a management hierarchy to recruit and hire developers, plan, schedule, and run software development, and an issue tracking process to handle bugs and requests for enhancements.  The effort involved in starting a business on the web requires either a technical co-founder, a trusted service for software development, or a third party contracted for development.

This greatly limits the businesses that can be started, gives tremendous power and influence to the technology companies that provide services, and further, infuses a technical bias to the software development.

Self-run applications provide an interesting alternative to the status quo.  A self-run application would run on an infrastructure that provides incentives for evolution (feature development) and quality control (issue tracking of bugs and requested enhancements).  The idea is that the infrastructure itself provides tools for any individual to build an application that would then be part of the infrastructure and receive a financial stake that will be high or low depending on the success of the idea on the infrastructure.

This is not meant to replace the existing system.  This is solely meant as an alternative.  The revenue model is that the originator of such a service who invests time in setting it up and defining it receives at the end a set of tokens that would be worthless or have value depending on the success of the service.  Likewise, individuals who participate in the evolution of the service or the maintenance of the service also receive incentives in the same way.  As the service accrues revenue, the financial tokens can be converted into present currency or can be held on for future currency.

THe self-run service must be intuitive to set up and define by someone business savvy but not necessarily technical.  An amateur or business newbie should also be able to attempt to set up a service.  

The goal then is an infrastructure that provides self-run application creation, evolution, and maintenance as a service.  In addition, the infrastructure should provide for transactions, dispute resolution, communication, and reputation management.  This is very ambitious of course.  I will do my best to outline each point either as a problem that hopefully will be solved in the future or as an approach which should be taken as a first stab at a solution.

In theory, if a person designs a self-run service that has high value, it should be possible for others to find out about it and for the financial stake associated with it to go up in value relative the amount of values offered by the service to the general community.

Here are some open questions:

* What does the UI look like that will be so easy to use?

Clearly, visual programming for the most part has not fulfilled the promise of making development possible for the non-technical.  Indeed, as far as I know, there is only one software application that has proven itself to be highly usable by nontechnical folks and that is Minecraft.  So, my first question: Can the success of minecraft be generalized for use with Project Yugho?

* What is a self-run application

A self-run application is not necessarily a smart agent that is completely independent of people.  Rather, it is an application that runs on top of a state machine that provides a process and incentives for people to interact with the application.  Rather than a traditional business where employees sign a job contract, work for a management hierarchy, and get a salary, a self-run application provides financial tokens as incentives for user actions.  Ideally, people participate solely because they enjoy the technology and/or problem that they are working on or they work on it as a way to learn the latest technology.  Additionally, if the service is succcessful, they should receive a sufficient financial reward.  

Every person in the application is equal.  They can choose any needed opportunity that they wish (assuming that they get there in time and there are enough spaces to accommodate demand), receive a token if they successfully complete tasks, nad then those tokens are convertible to money as the service is successful.

Such services will be easier to start (it only takes one's time and an idea) and cheaper to run (no need for a management hierarchy -- just individual contributors) and potentially faster to improve quality (less hierarchy means more focus on objective criteria and less politics).  

Perhaps, a potential downside or upside (depending how you look at it) is the capacity for the features to change based on interest by the participants.  This raises the question: will it be possible for a competitor to sabotage a successful product by changing a popular feature or introducing bugs?  The over all infrastructure will need to squarely address these concerns in order to have a chance of being successful.

* How is a self-run application hosted

Self-run applications can run in 2 ways:  On-Demand Local.  In this case, a user downloads the application, runs it locally, and the application will communicate with other nodes in a p2p way that runs on top of kademlia.  Hosted.  In this case, a hosted service is used where the application has state and can respond to multiple clients from the hosted service.

* How is a self-run application evolved and maintained

The source code for such an application will have three forms.  A technical form is the programming language used to build the service, implement features, and fix issues, a domain-specific form (domain specific language) which is a domain-specific model for chacters data storage and objects for the application, and a visual form (Minecraft-like form) which is a virtual form that can interacted with and details in a virtual environment (this is hypothetical:  the details need to be worked otu)

There will be an issue tracking system.

* What is the application framework

The application framework itself is a distributed framework that runs on nodes that provides support for user accounts, verifiable messaging, and disputable transactions.  The application framewokr is the vehicle for supporting tokens, supporting user accounts, and supporting self-run application details.  The incentive system is based on this framework.  





