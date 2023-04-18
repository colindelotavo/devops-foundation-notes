# 1. DevOps Basics
## DevOps Core Values
### C - Culture
Emphasising the mportance of creating a positive culture that promotes collaboration
### A - Automation
Implementing automation to improve efficiency
### M - Measurement
Measuring key metrics to track progress and identify areas for improvement
### S - Sharing
Sharing ideas and problems to drive continuous improvement in a DevOps implementation

## DevOps Principles
### Systems Thinking
Importance of focusing on the entire value chain
### Amplify Feedback Loops
Creating short and effective feedback loops
### Continuous Experimentation
Promoting a culture of learning and experimentation to continuously improve the DevOps process

## DevOps Playbook
### People / Process / Tools
Emphasises the importance of people and their roles in a DevOps implementation over the process and tools.
### Continuous Delivery
Involves coding, testing, and releasing software frequently and in small batches to improve the overall quality and velocity of software development.
### Lean Management
Uses small batches of work, work in progress limits, feedback loops, and visualization to improve organizational outputs and employee satisfaction.
### Change Control
Emphasises control over changes in the environment and a light and practical approach to change control that eliminates fragile artifacts and creates a repeatable build process.
### Infrastructure as Code
Treats systems like code to improve overall quality and velocity and enhance organizational outputs and employee satisfaction.

## DevOps Practices
### 1. Chaos Monkey
Netflix invented a piece of software called Chaos Monkey, which forces developers and operators creating systems to engineer resiliency into their services instead of assuming that their infrastructure is always on.
### 2. Blue/Green Deployments
This deployment pattern involves having two identical systems, blue and green, one live and the other offline, and to perform an upgrade, you upgrade the offline system, test it, and then shift production traffic over to it.
### 3. Dependency Injection
This software design pattern focuses on loosely coupled dependencies and ensures that the application shouldn't know anything about its external dependencies.
### 4. Andon Cords
This is an innovation used by Toyota on its production line, which can be implemented in your software delivery pipeline to stop ship when a problem is detected and prevent the bug from propagating downstream.
### 5. The Cloud
Cloud technologies provide an API-driven way to create and control infrastructure, which allows you to treat your systems infrastructure exactly like any other program component.
### 6. Embedded Teams
Embedding an Operations Engineer on each development team and making the team responsible for all its own work can resolve conflicts and promote cooperation.
### 7. Blameless Postmortems
Examining failures and learning from them without blaming individuals helps avoid logical fallacies and improve the situation.
### 8. Status Pages
Creating public status pages and communicating promptly and clearly during outages has been shown to increase customer satisfaction and retain trust.
### 9. Developers on Call
Putting developers on call for the services they create creates a fast feedback loop and results in rapid improvements.
### 10. Incident Command System
A process for managing incidents in IT that can work for both small and large incidents.

## Tool Criteria
### Programmable
Automatable, being completely UI driven can lead to failure
### Verifiable
Exposure to its action and validating its success
### Well-behaved
Easily configurable, testable, and deployable <br/><br/>
Note: Existing tools are preferred, but writing your own tools are normal.

# 2. DevOps. A Culture Problem
## The IT crowd and the coming storm
The IT industry faces a problem of division within its teams, resulting in a harmful conflict of interest that hinders feedback loops and optimisation for the organisation. The institutional causes of this division are due to the conflicting responsibilities of development and operations teams and the separation of duties, incentivising groups to only optimise their own area of concern. The internal misalignment of IT processes and organisations, with outdated practices that cause delays, is no longer acceptable in today's tech-savvy business world. The chapter explores how to change IT culture to align with modern business needs.

## Use your words
In this section, the focus is on two communication aspects in DevOps: blameless postmortems and transparent uptime. Blameless postmortems involve holding a meeting within 24 to 48 hours after a major outage and assigning one person to run the meeting. The goal is to prevent future outages rather than assign blame. It is important to record action items and agree on deadlines. Transparent uptime is about communicating with customers during an outage by admitting failure, sounding like a human, having a communication channel, and being authentic. One person should manage communication during the outage, figure out stakeholders, and be authentic about the issues at hand.

## Do unto others
Collaboration is important in DevOps, but it can be challenging due to misunderstandings and conflicting goals. Breaking down team barriers and getting people from different specialties to work alongside each other can help. However, there may be differences in language and sub-cultures with different terminology. Being open and transparent, allowing people to access chat rooms, team Wiki pages, code, infrastructure, monitoring tool, and ticket tracker can help promote sharing. The practice of ChatOps is especially empowering, using chat clients not only as a gathering place for the team to discuss but as part of the operational system.

## Throwing things over walls
This section emphasises the importance of building a culture of trust and collaboration, and recommends breaking down team barriers by embedding specialists from different areas into cross-functional teams. They also highlight the need for leadership to support the transition and help team members navigate role changes. The video also covers the importance of focusing on organisational and process issues, such as eliminating silos and implementing lean agile processes. They also recommend using minimum viable processes and adapting them as needed, while keeping an eye out for processes that can be removed.

## Kaizen: Continuous Improvement
This section discusses the concept of Kaizen, which means continuous improvement and is a cultural practice in DevOps that originated in Japan. Kaizen is based on six principles and emphasizes going to the actual place where value is created or where a problem is to make improvements. The Kaizen process involves a cycle of plan, do, check, act, and it is a more tactical form of the scientific method. The five Why's is another tool used in Kaizen to get to the root cause of a problem. It involves asking the question "why" multiple times until the root cause is identified. They also mention the importance of critical thinking skills and the idea that human error is attributed to an issue in processes.

# 3. The Building Blocks of DevOps
## DevOps building block: Agile
Agile originated from the Agile Manifesto in 2001, which emphasised collaboration, flexibility, and customer satisfaction. It evolved from the traditional software development approach called waterfall, which moves software through sequential stages from requirements gathering to development, testing, and release. In contrast, Agile is iterative and emphasises collaboration between workers and customers, with a focus on delivering working software in frequent feedback cycles. This approach reduces the risk of major problems emerging later in the development process, leading to better customer satisfaction (due to the implementation of the iterative feedback loops), increased productivity and faster time to market.

## DevOps building block: Lean
Lean is a systematic process for eliminating waste that was originally devised in the manufacturing world (Toyota in Japan) and later adapted to software development by Mary and Tom Poppendieck. Lean is a building block of DevOps and focuses on recognising activities that add value and eliminating those that do not. It has seven principles that apply to software and identifies three types of waste: muda (useless waste), muri (the major form of waste, though there is a necessary waste type, such as compliance), and mura (inconsistent waste). Lean techniques include Kaizen and value-stream mapping, and it has become an important part of successful DevOps implementations. 

## Agile versus Lean
- Agile's main goal is to deliver working software frequently and enable rapid adaptation to changing requirements. Agile values individuals and interactions, working solutions, customer collaboration, and being proactive in responding to change. <br/>
- Lean's main goal is to optimise processes, reduce waste, and maximise value for customers. Lean helps optimise the entire software development lifecycle by identifying and removing bottlenecks, reducing 'waste', and honing the flow of work. <br/>

## ITIL, ITSM, and the SDLC
ITIL - Information Technology (IT) Infrastructure Library <br>
ITSM - Information Technology (IT) Service Management <br>
SDLC - Software Development Life Cycle <br>
***
IT service management (ITSM) highlights the importance of service delivery throughout the software development lifecycle (SDLC), from design to retirement. ITIL, the pioneering ITSM framework, was initially developed by the UK government to manage services, and has since evolved into a widely adopted framework with multiple versions. Although ITIL provides guidance for various IT processes, it is often associated with a waterfall or push-driven model. Gene Kim, co-author of "The Visible Ops Handbook," demonstrates how ITIL can be implemented in a lightweight and agile manner. The main idea is to implement processes as necessary using a lean and agile mindset— without introducing 'waste' or bottlenecks, other practices that have been introduced previously should also be considered, such as how the processes impact or value to the customer, rather than implementing processes for the sake of standard IT practice.

# 4. Infrastructure Automation
## Infrastructure as Code
Infrastructure as code is a programmatic approach to infrastructure that allows leveraging development practices for systems, treating systems like code, and automating everything from the bare metal up. Tools exist to configure servers automatically, and everything can be created, changed, and destroyed programmatically. The biggest challenge in infrastructure as code is changing mindsets, and the key to treating infrastructure as code is changing infrastructure engineers' way of thinking. It's important to assume that systems are ephemeral, and servers are not something to be handcrafted and named and manually kept up anymore (cattle, not pets). 

## Golden image to foil ball
Configuration management (CM) is the process of maintaining and upgrading systems and applications on servers. It includes provisioning, deployment, and orchestration. Imperative and declarative approaches and idempotency are important in configuration management. Initially, CFEngine, Puppet, and Chef were used as provisioning tools by operations teams. Although with the shift towards the STEM cell system approach, CM tools became the de facto standard. When virtualisation gave way to cloud, CM became crucial for a well-managed environment. Orchestration became a challenge, which led to the emergence of push mechanism tools like Ansible and SaltStack. A variety of orchestrated deployment techniques, including Canary deployment, blue-green deployment, and immutable deployments have come into play.

> Note: The STEM cell system approach is a configuration management approach where the initial provisioning of a system is kept as minimal as possible, typically including only the necessary components to enable communication with the CM tool. The CM tool then takes over and provisions the rest of the system incrementally later, which helps to prevent configuration drift and provide later updates using the same mechanism.

## Immutable deployment
Immutable deployment refers to the practice of creating a declarative model of base systems, which can be used to create systems and applications. In this model, the entire container, including OS dependencies and app code, is treated as an artifact, and once it is deployed, it is immutable. Upgrades are rolled out by deploying an entirely new system, rather than changing the state via configuration management. This approach is becoming increasingly popular in the container world and is called immutable infrastructure for systems and immutable delivery for apps. Service discovery stores are used to manage and coordinate workers for container orchestration tools like Mesos and Kubernetes. The traditional approach of using a central configuration management database (CMDB) has fallen out of favor, and newer solutions like ZooKeeper, LCD, and HashiCorp Console have emerged.

## Your infrastructure toolchain
Infrastructure as code tooling depends on the backend used, such as AWS, Azure, or a container-based approach. CloudFormation templates and Azure Resource Manager templates allow you to specify infrastructure in JSON format, while HashiCorp's TerraForm provides a more abstract approach. Configuration management tools like Chef, Puppet, Ansible, Salt, or CFEngine can help dynamically configure machines, and can also be used to build images. Etcd, Zookeeper, and Consul are common tools for service discovery and state tracking. Docker platforms like Docker Swarm, Kubernetes, and Mesos allow for orchestration of containers. Habitat, by the creators of Chef, extends into the application build and deploy cycle.

# 5. Continuous Delivery
## Small + Fast = Better
Continuous Integration (CI) and Continuous Delivery (CD) are essential practices in DevOps, enabling faster time-to-market, while also ensuring higher quality. CI involves automatically building and testing the entire application frequently, ideally with each source code check-in. CD goes further by deploying every change to a production-like environment and performing automated integration and acceptance testing. High-performing IT organisations can deploy on demand and have a three times lower change failure rate compared to their peers. This is achieved by integrating testing earlier in the delivery pipeline, reducing work in progress, and working from the master branch. Continuous Delivery also helps in reducing mean time to recover (MTTR) by enabling faster remediation of failures and easier identification of error sources, since changes are made incrementally, rather than all at once.

## Continuous integration practices
### 1. Builds should pass the coffee test
Ensure that builds are completed quickly, within the time it takes to make a cup of coffee, to establish a fast feedback loop that encourages automated testing, reduces rework, and promotes a smoother development process.
### 2. Commit really small bits
Submit the smallest amount of code per commit, facilitating easier comprehension for team members, and simplifying the process of isolating and addressing failures.
### 3. Fix broken builds immediately
Leaving the build broken blocks delivery, and the team should delay meetings or stop other work until it is fixed to set a positive tone for the delivery culture.
### 4. Use a trunk-based development flow
Adopt a trunk-based workflow where all developers work on the same codebase, frequently commit code changes, and use feature flags instead of separate code branches to limit work in progress, improve collaboration, and minimise errors during merging.
### 5. Don't allow flaky tests
Fix any tests that sometimes fail and sometimes pass without a clear reason, as it is hard to trust the build if the tests are inconsistent.
### 6. Return status, log, and artifact
The build should provide a simple pass/fail status, a log of all the tests run and results, and an artifact uploaded and tagged with a build number to ensure trust, audibility, and immutability.

## The continuous delivery pipeline
### 1. Only build artifacts once
Artifacts should be created upon successful completion of each build, stored in a central artifact repository, and not rebuilt for staging, testing, or production environments to reduce rework and ensure consistency across the pipeline.
### 2. Artifacts should be immutable
Artifacts should be prevented from being changed to ensure auditability and build trust between teams during debugging, and to allow teams to easily track specific code versions in source control to a successful build artifact to a running system.
### 3. Deployment should go to a copy of production
Deployments should be made to a staging/test environment that is a replica of the production environment, including all the necessary elements such as load balancers, network settings, security controls, and matching data. This allows for accurate testing of code and deployment processes and ensures that the deployment process works in the production environment.
### 4. Stop deploys if a previous step fails
The continuous delivery pipeline should be stopped immediately if any previous stage of the pipeline has failed, preventing errors from propagating to the next stage and ensuring that the pipeline is stopped until the previous stage has been fixed.
### 5. Deployments should be idempotent
Redeploying should leave the system in the same state, making it easy to redeploy without introducing new errors or causing inconsistencies. This can be achieved using a mutable packaging mechanism like Docker containers or through a configuration management tool like Puppet or Chef, ensuring that the deployment process is consistent and predictable.

## The role of QA
### 1. Unit testing
This type of testing is done at the lowest level of the language or framework to validate individual functions. Unit tests are usually the fastest and can easily run on the developer's machine.
### 2. Code hygiene
Code hygiene involves using best practices from the development community to ensure that code is clean, readable, and maintainable. This can be accomplished using linters, formatters, and banned function checks.
### 3. Integration testing
Integration testing is a type of technical testing that is performed with all the app's components and dependencies operating in a test environment. It is similar to unit testing but covers multiple components working together.
### 4. TDD, BDD, ATDD
##### TDD - Test Driven Development
TDD is a development practice that starts with writing tests before writing any code. The idea is to start with the desired outcome written as a test, then write code to pass the test. This approach encourages high feedback and results in a comprehensive test suite being developed alongside the application.
##### BDD - Behaviour Driven Development
BDD involves working with a business stakeholder to describe the desired business functionality of the application and expressing the test in a DSL close to the English language. BDD is useful for ensuring that the application meets the needs of the business.
##### ATDD - Acceptance Test Driven Development
ATDD builds on TDD and BDD, and involves defining scenarios from the end user's perspective. You write automated tests with examples of these use cases and then run them repeatedly while the code is being developed. ATDD helps ensure that the application meets the needs of end users.
### 5. Infrastructure testing
Infrastructure testing involves testing the host and configuration management to ensure that the infrastructure is working correctly. 
### 6. Performance testing
Performance testing involves testing the application's performance under load and stress to ensure that it is performant and can handle high levels of traffic.
### 7. Security testing
Security testing involves testing for simulated security attacks to ensure that the application is secure and protected against potential threats.

## Your CI toolchain
### 1. Version control
This phase involves committing code changes and viewing the entire history of all changes made. Popular tools for version control include Git, GitHub, and Bitbucket. These tools allow developers to stay in sync with each other by treating each change as an independent layer in the code.
### 2. Continuous Integration systems
Jenkins is a popular open-source CI system, while Travis CI and CircleCI are popular CI-as-a-service options. Other options include GoCD, Bamboo, and TeamCity.
### 3. Build
Build tools are language-dependent and execute a consistent set of steps every time. Options include Make, Rake, and Maven.
### 4. Test
Testing tools include unit testing frameworks like JUnit, integration testing frameworks like Robot and Cucumber, and performance testing tools like ApacheBench and JMeter. There are also code hygiene tools like Golint or Gofmt for Golang or RuboCop for Ruby.
### 5. Artifact repository
Artifact repositories like Artifactory or Nexus are used to store artifacts. Specific outputs like a Docker image can be sent to Docker Hub or your internal Docker registry. You can also use tools like Amazon S3 to upload your artifacts.
### 6. Deployment
Deployment tools include Rundeck and configuration management tools like UrbanCode. There's also an open source offering from Etsy, called Deployinator. This phase involves automating a workflow across your systems to deploy your code. <br/><br/>
Note: It's recommended to focus on building the easiest thing possible for each portion of the pipeline (minimum viable product) and to avoid over-investing in tools beyond what the product needs. Anything that doesn't directly add value to the product is considered waste.

# 6. Reliability Engineering
## Engineering doesn't end with deployment
Reliability engineering is a crucial part of DevOps that aims to ensure a system functions properly under specific conditions for a set duration. This practice area covers aspects such as performance, availability, and security. Software problems are now responsible for most outages and production problems, rather than infrastructure issues. Design for operation and operate for design are two critical areas to consider when addressing reliability. Google popularised the term 'site reliability engineering', which involves product teams supporting their services until they reach a certain level of maturity, with development teams handling 5% of the operational workload ongoing, which promotes a healthy feedback loop.

## Design for operation: Theory
Design for operation involves making decisions at the beginning of the pipeline that can help your application work well even in adverse conditions. This approach involves using design patterns that address stability, such as the circuit breaker, to prevent cascading outages caused by integration point failures. The [12 factor app](https://12factor.net/) manifesto provides guidelines for producing service-ready software, including separating runtime configuration from app code.

## Design for operation: Practice
it's important to acknowledge that all systems fail and pushing more money towards highly available systems is not the solution. Instead, embracing deliberate adversity, such as using the Chaos Monkey tool to intentionally cause failure, can lead to fundamentally different approaches to system design. Operational processes must depend on as few integration points as possible, and understanding how to draw an X through any dependency of the system is critical. Performance can also be improved through the use of code profilers and application performance management (APM) tools, and running baselines on every build in your CI pipeline is crucial to your service's health.

## Operate for design: Metrics and monitoring
### 1. Service performance and uptime
This is the highest level of monitoring and is often referred to as synthetic checks. These checks answer the question of whether the service or application is working or not. Synthetic checks are not real traffic or real customers, but are simulations of various scenarios that the service might encounter.
### 2. Software component metrics
This is monitoring that is done on ports or processes, usually located on the host. This layer of monitoring is one level deeper than service performance and uptime, and answers the question of whether a particular host or process is working or not.
### 3. System metrics
These are time-series metrics that can be anything from CPU or memory usage to disk I/O. System metrics help answer the question of whether a service, host, or process is functioning normally.
### 4. Application metrics
These are telemetry from the application that gives insight into what the application is actually doing. Examples of application metrics include the time it takes for a certain function call to complete, the number of logins in the last hour, or the count of all the error events that have happened. These metrics are often custom and specific to the application being monitored.
### 5. Performance 
Performance metrics are tied through all the previous types of metrics, and provide insights into the performance of the application or service. Application performance monitoring (APM) and real user monitoring (RUM) are two common types of performance monitoring. APM isolates function performance at the code level, while RUM uses front-end instrumentation to capture the performance observed by the users of the system
### 6. Security
Security monitoring includes four key areas: system, application security, custom events in the application, and anomalies. System security includes monitoring for bad TLS/SSL settings, open ports, and other system configuration issues. Application security involves detecting when XSS or SQL injection attacks are attempted. Custom events in the application, such as password resets, invalid logins, or new account creations, can also provide insights into potential security issues. Anomalies, such as HTTP 401 errors or access attempts from irregular IP segments, can also be indicators of security threats.

## Operate for design: Logging
### 1. Don't collect log data you won't use
Don't collect log data that you have no use for. Only log what you need to investigate outages or audit something in the future.
### 2. Keep logs for as long as they can be used
Retain log data for as long as you might need it or as long as it is prescribed by regulations. Keeping too much log data can be costly in terms of resources and maintenance.
### 3. Alert only on what you must respond to
Log all you can, but only alert your team based on critical problems like customer experience or security issues. Clearly define your log levels to make it easy to filter and prioritize logs.
### 4. Don't exceed business security needs
Don't overbuild capacity or defense in your logging system. Keep it lean and meet business needs.
### 5. Logs change
Logs can change in format or messages when new versions of software are released. Encourage everyone to take ownership of their logs in the centralized logging system and create a feedback loop to ensure everyone is aware of the changes.

## Your SRE toolchain
Monitoring tools include the likes of Nagios, Zabbix, Datadog, Netuitive, Ruxit, and Librato; open-source tools like StatsD, Ganglia, Graphite, and Grafana; log management tools like Splunk, Sumo Logic, Logentries, and ELK stack; incident management tools like PagerDuty, VictorOps, and Flapjack; status page tools like Statuspage.io; command dispatchers like Rundeck, SaltStack, and Ansible; and security monitoring tools. <br/><br/>
Note: As with other mentioned toolchains, it is normal and even preferrable at times to write your own tools.

# 7. Additional DevOps Resources
## Unicorns, horses, and donkeys, oh my
The concept of DevOps can be applied to three groups: unicorns (startups), horses (enterprise IT), and donkeys (small teams with budgetary constraints). The best way to learn and connect with like-minded individuals is through attending conferences such as DevOpsDays, Velocity, and DevOps Enterprise Summit. There are also technology-specific events and DevOps-related meetups in many cities.

## Ten best DevOps books you need to read
1. "The Phoenix Project" is a novel that walks through one company's problems and their transformation to lean and DevOps principles.
2. "Leading The Transformation" provides practical advice for directors, VPs, CTOs and anyone in charge of leading IT organisational change of any size.
3. "The DevOps Handbook" is a standard reference book on DevOps that explains how to create world-class agility, reliability, and security in technology organisations.
4. "The Practice of Cloud System Administration" is a textbook on system administration topics that covers DevOps principles and practices.
5. "Web Operations" is a collection of essays from practitioners that cover a wide variety of topics, from monitoring to handling postmortems, to dealing with stability with databases.
6. "Lean Software Development: An Agile Toolkit" explores the benefits of value stream mapping and waste reduction in software development and provides tools and examples for implementing lean principles.
7. "Effective DevOps" features practical advice for organisational alignment in DevOps and focuses on both cultural aspects and tooling.
8. "Release It!" provides design patterns for stability, security, and transparency in production-ready software.
9. "Continuous Delivery" is a comprehensive book on continuous delivery that provides practices and principles, along with common anti-patterns.
10. "Visible Ops" boils down IT into four key practices that bring high value to organisations through a lean implementation of change control principles.

## Navigating the series of tubes
The internet is a valuable resource for finding DevOps information, but it can be challenging due to its fragmented nature. Twitter is the most active social network for DevOps. DevOps Weekly is an excellent weekly email newsletter curated by Gareth Rushgrove. DevOps.com, DZone, and InfoQ are generic tech aggregators with DevOps channels. DevOps Cafe, Arrested DevOps, and Food Fight are popular podcasts. Many blogs have valuable posts, including Kitchen Soap, IT Revolution Press, Dev2Ops, Continuous Delivery, Stochastic Resonance, More Than Seven, Agile Admin, and more. SlideShare, YouTube, and Vimeo have recordings of conferences and user group meetings.

# 8. The Future of DevOps
## Cloud to containers to serverless
The evolution of computing infrastructure is rapid, from cloud, to containers to serverless technologies. Cloud computing has become the leading option for hosting computing needs, offering benefits like faster time to market, greater scalability, and higher availability. Containers, such as Docker, enable isolated process spaces with lower overhead and have experienced rapid growth. Developers appreciate the ease of packaging applications and dependencies in containers. Serverless computing, including AWS Lambda and Google Cloud Functions, is a newer option that provisions and deprovisions applications on-demand, eliminating the need for long-running virtual machines. This field is experiencing rapid change, with each new innovation shaping the way computing is approached.

## The rugged frontier of DevOps: Security
The integration of security into DevOps is crucial, but it presents challenges due to historical undervaluation and different priorities. The Rugged Manifesto offers aspirational values for a better defense approach. Deputising a security champion in each group can help overcome the understaffing problem. Infrastructure as code and continuous delivery pipelines can aid compliance auditors and enable security testing from the left. Four key areas for security testing in CI/CD systems are software supply chain security, regression testing, environment validation, and attack testing. Instrumenting runtime environments with defense products can help answer fundamental security questions.

## Next steps: Am I a DevOp now?
The importance of learning DevOps through hands-on experience and experimentation with various tools and techniques is emphasised. It addresses misconceptions about DevOps, highlighting that it represents a mindset and collaborative approach rather than a specific job role. The concept of a T-shaped individual is discussed, which refers to someone who has deep expertise in one area while understanding a broader range of technical subjects. The video emphasises the diversity of DevOps practices across organisations, indicating that there is no universally correct approach, as it is dependent on the people and needs of the organisation.