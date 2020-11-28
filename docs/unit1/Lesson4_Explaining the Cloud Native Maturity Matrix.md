# Lesson 4: Explaining the Cloud Native Maturity Matrix
## LESSON OBJECTIVES
---
 After completing this lesson, you will be able to:

    -   Detect the position of your company in terms of culture, team,
        process and white criteria. With the help of the matrix, you can now
        sketch your goals and how to get there

## Cloud Native Maturity Matrix
---
 In particular, we'll look at the following topics in this lesson:

        -   Cloud Native Transformation - Overview
        
        -   Culture
        
        -   Product/Service Design
        
        -   Team
        
        -   Process
        
        -   Architecture
        
        -   Maintanance
        
        -   Delivery
        
        -   Provisioning
        
        -   Infrastructure

## Cloud Native Transformation - Overview
---
 Cloud Native Maturity Matrix, a unique framework for evaluating and
 understanding your company where it is right now. The matrix is a
 pragmatic process you can apply to map your current maturity, identify
 gap analysis, and discern where they should focus their efforts in
 order to reap the most benefits.

This part comes from the book :
    Cloud Native Transformation Practical Patterns for Innovation
    Pini Reznik, Michelle Gienow, Jamie Dobson
    ISBN: 1492048909

 ![](.//media/image25.jpeg)

 As we see, the Maturity Matrix is divided into nine separate areas (or
 axes), each one an individual and essential member of an integrated,
 interdependent system. Each axis is further divided into four specific
 stages of organizational development a company may currently occupy:

    -   No process
    
    -   Waterfall
    
    -   Agile
    
    -   Cloud native
    
    -   Next

 We'll take a closer look. We limit ourselves only to the living of the
 Cloud Native and Next specific stages of organizational development.

## Culture
---
![](.//media/image26.jpeg)

### Cloud native: Collaborative

 A Collaborative organization tends to have big but not deeply specific
 goals (i.e., there may be a wide vision but without a detailed
 specification or a fixed delivery date). This culture embraces
 learning and consistent, continuous improvement over predictability.
 Emphasis is on self-education, experimentation, and research. Results
 are coldly assessed based on field data.

 A collaborative culture is crucial for companies operating in areas of
 high uncertainty or fast change.

### Next: Generative

 We predict the next type of organization will be a Generative one. An
 extension of a collaborative organization, in a generative
 organization IT will co-create solutions as equal partners with the
 business.

## Product/Service Design
---
![](.//media/image27.jpeg)

 This is the place where we assess just what it is you do and how you
 go about doing it. We evaluate whether you are organized around
 long-term planning, delivering a tightly coupled product on a slow and
 deliberate schedule - or whether you iterate rapidly in shorter
 sprints, ideally using customer feedback to drive the changes.

### Cloud native: Data Driven

 The final say on which features stay in a product is based on data
 collected from real users. Potential new features are chosen based on
 client requests or designs by product owners without a long selection
 process. They are rapidly prototyped and then developed and delivered
 to users with copious monitoring and instrumentation. They are
 assessed against the previous features (better or worse?) based on A/B
 or multivariate testing. If the new feature performs better, it stays;
 if worse, it is switched off or improved.

### Next: AI Driven

 In the future, humans will be cut out of this process entirely!
 AI-driven systems will make evolutionary tweaks and test themselves
 with little developer interaction.

## Team
---
![](.//media/image28.jpeg)

 Does your enterprise take a top-down, "Do what the boss says"
 approach, likely with highly specialized teams? Or one that is more
 cross-functional, composed of teams where each member has specific
 skills? Possibly you have progressed all the way to DevOps - an
 effective approach that takes advantage of cloud native architecture.

### Cloud native: DevOps/SRE

 Traditionally, developers/engineers have been responsible for building
 software and then handing it off to the operations team for
 deployment. A DevOps team joins the two in a single team capable of
 designing and building applications as part of a distributed system,
 and also operating the production platform/tools. Across the
 organization, each team has full responsibility for delivering an
 individual set of microservices and supporting them. DevOps teams
 typically include planning, architecture, testing, dev, and
 operational capabilities.

 There will still often remain a separation of tasks. For example, it
 is common to see a platform DevOps team in charge of building the
 cloud native platform, while site reliability engineering (SRE) or
 first-level support teams respond to incidents (and spend the rest of
 their time working on automation to prevent them from happening in the
 first place). However, there is considerable collaboration between
 those teams and individuals can easily move between them.

### Next: Internal supply chains

 In an Internal Supply Chain organization, each service is a separate
 product with full tech and business generation responsibilities in the
 teams - much as many ecommerce teams have been managed for a decade.

## Process
---
![](.//media/image29.jpeg)

 Does your enterprise do long-term planning up front and then follow
 with execution? Or do you change things responsively and on the fly?
 Currently, Scrum/Kanban is what we find most enterprises using. Cloud
 native and CI/CD require the next jump in speed: now developers need
 to be able to deliver every day - and do so independently from other
 developers.

### Cloud native: Design Thinking + Agile + Lean

 Design Thinking and other research and experimentation techniques are
 used for de-risking large and complex projects. Many proofs of concept
 (PoCs) are developed to compare options. Kanban is often then used to
 clarify the project further, and finally Agile methods like Scrum can
 be applied once the project is well understood by the entire team.
 Highly proficient organizations might choose to follow the Lean model.

 This relatively new approach is very effective in situations of high
 uncertainty or where the technology is changing rapidly.

### Next: Distributed, self-organized

 In the future, self-organized systems will be highly experimental.
 There will be less up-front design. Individuals or small teams will
 generate ideas, which will then form the seeds of a new

 product or feature. Once implemented, these will be iterated and
 improved on automatically by the platform.

## Architecture
---
![](.//media/image30.jpeg)

 Is your enterprise trying "batteries included" to provide everything
 needed for most use cases

The Tightly Coupled Monolith? Or perhaps you have reached the next
 step in the evolutionary architecture chain, Client-Server. The cloud
 native goal is to use microservices architecture where a large
 application is built as a suite of modular components or services.
 Microservices enable development teams to take a more decentralized
 (non-hierarchical) approach to building software. Microservices enable
 each service to be isolated, rebuilt, redeployed and managed
 independently.

### Cloud native: Microservices

 Microservices architecture is highly distributed. It comprises a large
 number (usually more than 10) of independent services that communicate
 only via well-defined, versioned APIs. Often, each microservice is
 developed and maintained by one team. Each microservice can be
 deployed independently, and each has a separate code repository.
 Hence, each microservice team can work and deploy in a highly parallel
 fashion, using their own preferred languages and operational tools and
 datastores (such as databases or queues).

 Because the system is distributed and components are decoupled, not
 only from each other but from other copies of themselves, is it easy
 to scale the system up by deploying more copies of each service.
 Operationally, microservice deployment must be managed in a fully
 automated way.

### Next: Functions-as-a-Service/Serverless

 A Functions-as-a-Service (FaaS, also known as Serverless) architecture
 is one where no infrastructure needs to be provisioned. Each piece of
 business logic is in separate function, which is operated by a fully
 managed Function-as-a-Service such as AWS' Lambda, Azure Functions, or
 Google's Cloud Functions. No operations tasks such as up-front
 provisioning, scaling, or patching are required. There is a
 pay-as-you-go/pay-per-invocation model.

## Maintenance
---
![](.//media/image31.jpeg)

 On this axis we assess how you monitor your systems and keep them
 running. It's a broad spectrum, from having no process whatsoever to
 full automation with little or no human intervention. No Process/Ad
 Hoc means every now and then going in to see if the server is up and
 what the response time is. (And the somewhat embarrassing fact is, a
 lot of folks still do just that.) Alerting means having some form of
 automation to warn when problems arrive, but it is nowhere near fast
 enough for this new world because once a problem is alerted, a human
 being still needs to intervene. Comprehensive monitoring and full
 observability, where system behavior is observed and analyzed so
 problems can be predicted (and prevented) in advance, rather than
 responded to when they do happen, are an absolute necessity for cloud
 native.

### Cloud native: Full observability and self-healing

 In full observability and self-healing scenarios, the system relies
 upon logging, tracing, alerting, and metrics to continually collect
 information about all the running services in a system. In cloud
 native you must observe the system to see what is going on. Monitoring
 is how we see this information; observability describes the property
 we architect into a system so that we are able to discern internal
 states through monitoring external outputs. Many issue responses
 happen automatically; for example, system health checks may trigger
 automatic restarts if failure is detected. Alternatively, the system
 may gradually degrade its own service to keep itself alive if, for
 example, resource shortages such as low disk space are detected
 (Netflix is famous for this). Status dashboards are often accessible
 to everyone in the business so that they can check the availability of
 the services.

 Operations (sometimes now referred to as "platform") engineers respond
 to infrastructure and platform issues that are not handled
 automatically. Live application issues are handled by development
 teams or system reliability engineers (SREs). The SRE role may be
 filled by individuals embedded in a DevOps team or separated into a
 dedicated SRE team.

 Logs are all collected into a single place. This often includes
 distributed tracing output. Operations, developers, and SREs all have
 access to the logging location. They no longer have (or need) security
 access to production servers.

 All update processes are fully automated and do not require access by
 individual engineers to individual servers.

### Next: Machine learning (ML) and artificial intelligence (AI)

 In the next generation of systems, ML and AI will handle operational
 and maintenance processes. Systems learn on their own how to prevent
 failures by, for instance, automatically scaling up capacity.
 Self-healing is the optimal way for systems to be operated and
 maintained. It is faster, more secure, and more reliable.

## Delivery
---
![](.//media/image32.jpeg)

 Delivery is really all about how quickly you can get things out and in
 how automated a fashion. The Maturity Matrix moves from traditional
 major version releases every six to 12 months to Agile's more rapid
 iterations of weekly to monthly releases. Reaching cloud native grants
 the ability to release daily, or even multiple times per day.

### Cloud native: Continuous Delivery (CD)

 Continuous delivery describes an organization that ensures new
 functionality is released to production at high frequency, often
 several times per day. That does not mean the new functionality is
 exposed to all users immediately. It might be temporarily hidden or
 reserved for a subset of experimental or preview users.

 With CD we typically see:

 A so-called "deployment pipeline" where new code from developers is
 automatically moved through build and test phases.

 Automatic acceptance (or rejection) of new code for deployment.

 Thorough testing of functionality, integration, load, and performance
 happens automatically. Once a developer has put their code into the
 pipeline, they cannot manually change it.

 Individual engineers do not have permission to change the production
 (live) servers.

 Cloud native organizations typically combine integration and
 deployment processes, known as "CI/CD," to drive continuous
 improvements to their systems. They also run tests on their production
 systems using methods such as "chaos engineering" (a way of forcing
 outages to occur on production systems to ensure those systems recover
 automatically) or live testing for subsets of users (for example "A/B
 testing").

### Next: Continuous Deployment

 The next evolution of delivery is continuous deployment, where we see
 fully automatic deployment to production with no approval process -
 just a continuous flow of changes to customers. The system will
 automatically roll back (uninstall) new changes if certain key metrics
 are negatively impacted, such as user conversion.

## Provisioning
---
![](.//media/image33.jpeg)

 How do you create new infrastructure and new machines? How quickly can
 you deploy everything, and how automated is this process? Provisioning
 is the Maturity Matrix axis where we are happiest to see a company
 leading the other eight areas!

### Cloud native: Dynamic Scheduling/Orchestration (Kubernetes)

 Applications in production are managed by a combination of
 containerization (a type of packaging that guarantees applications are
 delivered from development with all their local operational
 dependencies included) and a commercially available or open source
 orchestrator such as Kubernetes.

 The risk of a mismatch between development and live environments is
 reduced or eliminated by delivering applications from Dev to Ops in
 containers along with all of the app's dependencies. The Ops team then
 configures Kubernetes to support the new application by describing the
 final system they want to produce in production. This is called
 declarative configuration.

 The resulting system is highly resilient, automated, and abstracted.
 Neither engineers nor the apps themselves need to be aware of hardware
 specifics. Everything is automatic. Detailed decision making about
 where and when applications will be deployed is made by the
 orchestrator itself, not a human.

### Next: Serverless

 All hardware maintenance and configuration is done in a fully
 automated way by your cloud provider's platform. Code is packaged by
 developers, submitted to the serverless service(s), and can
 potentially be distributed and executed on many different platforms.
 The same function can run for testing or live. Inputs, outputs, and
 dependencies are tightly specified and standardized. Serverless is
 rapidly being adopted across the cloud native ecosystem and is well on
 its way to becoming standard cloud native best practice.

## Infrastructure
---
![](.//media/image34.jpeg)

 Everyone knows this one: single server to multiple servers to VMs
 running in your own data center. Then shifting to Hybrid cloud for a
 computing environment that mixes on-premises infrastructure with
 private and/or public cloud services best tailored to your company's
 specific needs and use case.

### Cloud native: Containers/hybrid cloud (cattle)

 Here, individual machines don't matter: they are called "cattle"
 because there is a big herd and they are interchangeable. There is
 usually full automation of environment creation and maintenance. If
 any piece of infrastructure fails, you don't care - it can be easily
 and almost instantly recreated.

 Unlike VMs, these are never directly provisioned; they are accessed
 only through automated processes exposed through APIs. This automation
 means new infrastructure takes minutes, even seconds, to provision.
 Containers are used for application packaging, which makes it easier
 to run those applications anywhere, including different "hybrid" cloud
 environments, whether public or on-premises.

### Next: Edge computing

 The next evolution for infrastructure is edge computing. Decentralized
 computer processing as the edge of your network. Edge computing takes
 applications, data, and computing power (services) out of a
 centralized location and distributes them to locations closer to the
 user. (Kind of like microservices for compute loads, really.) Edge
 computing returns results fast and works well in applications where,
 for example, adequate data is available locally.
 
## LESSON SUMMARY
---
 You should now be able to:

    -   Detect the position of your company in terms of culture, team, process and white criteria. With the help of the matrix, you can now sketch your goals and how to get there