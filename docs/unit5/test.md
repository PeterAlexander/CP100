
## Lesson1: Explaining the Extension Strategy
=================================

179
---

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Explain, why extensibility is so important

### Extensibility Suite

 In particular, we'll look at the following topics in this lesson

-   What is the extension suite

-   Short repetition

-   Categorization into 3 areas - first look

-   Going deeper in the categories

-   What are extensions ?

-   Why build extensions?

-   Where can I find the information if and how i can extend an SAP Saas
    app via side-by-side?

 What is the extension suite?

 What is the extension suite?

-   With the Integration Suite, you can make sure that you have the
    right data at the right time in the right system in the correct
    format.

-   The Extension Suite now leverages the data provided by the
    Integration Suite and adds UX, processes and development
    capabilities on top.

 First of all, the Extension Suite comes was best run methodologies and
 guidance and guidelines for the customers on how to implement a good
 user experience, a good process integration and with very efficient,
 cloud based developer tools. In this chapter we will only take care of
 the Extension Suite.

 Short repetition

 Remember the Intelligent Enterprise strategy chapter. The following
 picture was shown there.

 ![](.//media/image2.png)

 <img src=".//media/image3.jpeg" style="width:3.90406in;height:1.7225in" /On
 the left-hand side, you see all the cloud solutions, may it be an SAP
 system or a non-SAP system.

 And on the right-hand side, you see systems on-premises. So here, SAP
 systems with S/ 4HANA or an SAP Enterprise Suite, for instance, but it
 could also be non-SAP systems.

 Categorization into 3 areas - first look

 <img src=".//media/image4.jpeg" style="width:3.8675in;height:2.275in" /To
 easier understand the offered tools and services we have introduced
 three categories in the Extension Suite as seen here.

![](.//media/image2.png)

 It has no technical impact to have this separation as all these
 services work hand in hand. You have development tools from
 "Development Efficiency" to build a modern, Digital Experience
 exposing digital, automated processes to end users.

 Going deeper in the Categories

 If we take a closer look at the Extension Suite, we see three main
 pillars.

 ![](.//media/image2.png)

 <img src=".//media/image5.jpeg" style="width:3.575in;height:2.08in" /On
 the left-hand side, you see the digital experience. This contains all
 the tools and services that helps you to provide an engaging user
 experience for your customers as well as your employees.

 So, from a technology point of view, it's all the technologies, how
 you build Web applications, mobile applications, and conversational
 bots, for instance.

 On the right-hand side then, you see the digital process automation
 area. These are the tools and services that help you to build
 processes, adapt processes, and also get an overview of the current
 state of all the processes, and gain insights into your processes.

 The third pillar is the development efficiency. So this is the toolset
 and the area where you see the development tools and also the low-code
 tools, we later come to that in more detail, that help you to build
 the digital experience on the one hand and the digital process
 automation on the other.

 Digital experience - tools and services are:

-   Mobile

-   Launchpad

-   SAP Fiori technology

-   Work zone

-   Conversational AI

 Digital process automation - tools and services are:

-   Workflow Management

-   Intelligent Robotic Process Automation (iRPA)

-   Live Process Content

-   Process Mining

 Development efficiency - tools and services are:

-   Business Application Studio

-   SDKs

-   Low Code Tools



-   Programming Models / Runtimes

-   DevOps

-   Event-Driven Architecture

 What are extensions?

-   SAP Cloud Platform Extension Suite Extensions – The Engineering View

-   Software engineering principle that allows for enhancements without
     impairing existing system functions.

-   Extensions can be addition of new functionality or through
     modification of existing functionality.

-   Extensibility is measure of ability to extend and effort required to
    implement extension.

 Why build extensions?

 <img src=".//media/image6.jpeg" style="width:3.575in;height:2.08in" /One
 can't expect that a given software supports all individual user
 requirements. SAP Cloud Platform Extension Suite is for business
 solutions! And we go one step more to allow even real differentiating
 requirements to be implemented that either optimized existing
 processes or drives completely new business models and innovations.

![](.//media/image2.png)

 The blue circle describes the scope of the functionality delivered by
 SAP. The light green circle describes the necessary requirements of
 the customer. Nor in the area of overlap, the delivered software can
 meet the customer's requirements. The rest must be created either
 together with SAP or in its own direction (dark green circle).

 Extension Types - 3 basic types:

 Classic

-   Web GUI

-   Web Dynpro

-   BAPIs

-   Function modules In-App

    -   Custom SAP Fiori app deployed to SAP S/4HANA.

    -   Custom Business Objects deployed to SAP S/4HANA.

    -   Other SaaS apps.

 Side-by-Side

-   Custom development outside of the application to be extended Cloud
    services

-   3rd party services

-   Cloud services from SAP

 The SAP Extension Suite wants to cover the green areas.

 What can be extended with the side-by-side Approach?

-   Basically, all SAP software products can be extended. The
    prerequisites are:

    -   The application to be expanded provides a usable API.

    -   The application to be expanded can send events.

    -   It doesn't matter which SaaS app is to be extended.

-   Examples are:

    -   Concur

    -   Fieldglass

    -   SAP S/4HANA essential

    -   SAP Success Factors

    -   More

 Where can I find the information if and how i can extend an SAP Saas
 app via side-by- side?

 In the SAP API business hub I find this information. We took a closer
 look at this in a previous chapter.

 ![](.//media/image7.jpeg)

 In the SAP API Business HUB you can see the available API es and/or
 events for the respective products, which can be used for a
 side-by-side extension. In addition to this white listed information,
 there are others that are only available in cooperation with SAP.

 LESSON SUMMARY

 You should now be able to:

-   Explain, why extensibility is so important

<img src=".//media/image8.png" style="width:0.39289in;height:0.22548in" / Building side-by-side Extensions on SAP Cloud
========================================================================================================================

 **<sup185</sup** Platform

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Explain the tools used for creating an extension

### Tools for Extension Building

 In particular, we'll look at the following topics in this lesson:

-   Extensions step-by-step - side-by-side

-   Extension Suite at a Glance

-   Use cases

 Extensions step-by-step - side-by-side

 <img src=".//media/image9.jpeg" style="width:3.83094in;height:2.23031in" /The
 general approach to the creation and operation of an extension is
 followed.

![](.//media/image2.png)

 Explanations about the figure:

1.  Connect

 Connect on-premise and cloud systems to SAP Cloud Platform to extend
 standard SAP solutions.

1.  Create endpoint

 Create endpoint extension applications based on your existing skill
 set.

1.  Add channels

 Web, mobile, conversational, others.

 Extension Suite at a Glance

 If you combine the general procedure with the tools and concepts of
 the Extension Suite, you will come to the following overview.

![](.//media/image10.jpeg)

 On the left side are the SaaS applications to be expanded. The
 following tools and concepts are available.

 Explanations:

 1: Connect

-   Cloud Connector

-   Cloud Integration (Integration Suite)

-   API Business HUB

-   SAP Graph

-   Enterprise Messaging (Integration Suite)

-   Smart Data Integration 2: Build Endpoint

-   Workflow Management

-   Cloud Programming Model (CAP)

-   Micro services

-   ABAP Restful Programming Model (RAP) 3: Add Channels

-   Mobile Services

 4: Deploy and Operate

-   Portal

-   Fiori Launchpad

    -   Workzone

    -   Runtimes ( ABAP, Cloud Founddry, Kyma, Serverless)

    -   DevOps ( Ci/CD services, Piper, Transport)

 ●

 In the following we will refer to this picture again and again so that
 you know where you are.

 Use cases

 <img src=".//media/image11.jpeg" style="width:3.58312in;height:2.01094in" /Real-time
 Pricing Freight Platform -Transportation / Supply Chain

![](.//media/image2.png)

 Use case:

 Logistic customer brings SAP Logistic Business Network customers
 transparent pricing, a dense carrier network, and always-on
 availability from the nationwide, digitally enabled carriers using
 customers Freight's platform. In addition to unlocking this carrier
 capacity to SAP's LBN shippers, the customers Freight and SAP LBN
 integration also delivers continued innovation from customer' platform
 to SAP LBN customers via new product enhancements as well as the
 ability to further automate the supply chain within SAP's suite of
 products to better control transportation management. Utilizing
 real-time rates directly in workflows in SAP software enables
 customers to save time and money Guaranteed capacity directly into the
 software infrastructure of SAP customers

 Components:

-   SAP HANA

-   SAP Cloud Platform Integration Suite

-   SAP S/4 HANA, TM Value Driver:

-   Enables customers to save time and money on freight and operational
     costs

-   Automate workflows to meet goals

-   Make sourcing capacity more efficient

-   Reduce underutilized assets

-   Increase transparency and streamlined logistics communication



-   Cut trucking costs

-   Lower freight costs through real-time visibility of market prices
     versus carrier contracted prices

-   Saves time by meeting dynamic logistics needs with real-time rates
     pricing & guaranteed capacity

-   Provides actionable insights and transparent market conditions which
     will help shippers estimate freight cost savings versus contracted
     rates and take actions.

 Business Pattern:

-   Creating true business innovation wit new business models

-   Applying real time business processes

-   Multi-channel, custom UX

 <img src=".//media/image12.jpeg" style="width:2.73406in;height:1.90125in" /Time
 Recording - Professional Services Industry / Finance and Accounting

![](.//media/image2.png)

 Use case:

 Customer offers consulting services and wants to provide its employees
 or service consultants a light-weight application which can allow them
 to record their time worked on a project.

 Customer runs lot of customer projects with different personas who
 would like to enter the time worked for a specific project.

 This time is then approved by a 'Project Manager' persona who can then
 understand and plan resources working for a project.

 Components:

-   SAP HANA

-   SAP Analytics Cloud

-   SAP Cloud Platform Enterprise Messaging

-   SAP Cloud Platform Integration Suite

-   Cloud Application Programming Model (CAP)

-   SAP SuccessFactors

    -   SAP S/4 HANA Cloud

    -   IonBiz ( 3rd Party)

    -   Omnitracker ( 3rd Party) Value Driver:

    -   Light weight UI to enter and approve Timesheet Application.

    -   Extending the standard business process for managing projects.

    -   Customer has 'HANA Cloud' as one source of truth from different
         systems.

    -   Cloud application allows easy integration of customer's
        third-party systems. Business Pattern:

    -   Custom UI with Logic and Persistence.

    -   Extend the Digital Core with new processes.

    -   Data Integration Hub Pattern.

    -   Replication of data from SAP S/4 HANA Cloud to Cloud Platform.

 <img src=".//media/image13.jpeg" style="width:3.5425in;height:2.10437in" /Equipment
 Management and Maintenance - Constructions and Operations / Asset
 Management

![](.//media/image2.png)

 Use case:

 Customer needs to digitize paper-based processes within equipment
 management & maintenance in order to meet the needs of steadily
 increasing volume of business.

 Data had to be manually entered, using paper, into SAP ETM, PM, & BI.
 Data was consistently obsolete due to time-delayed posting. Big
 opportunity for improving User Experience. There were no existing apps
 from SAP Fiori, so the SAP ETM & SAP PM were adapted & subsequently
 developed in-house.

 Customer needs to Digitize Paper-Based Processes within Equipment
 Management & Maintenance. Existing SAP Processes have been combined
 with FIORI Apps. Using SAP Cloud Platform, the Apps are readily
 available to Technicians on iOS & Windows Mobile Devices.

 SAP Fiori gives customer the opportunity to access our ERP directly
 through apps and to receive equipment data such as scheduling,
 profitability, analysis, repair orders, or equipment documents and
 perform in real time.

 Customer requirements included to make data available in Real-Time &
 On-Site in order to maximize Equipment Management efficiency. Data has
 to available via Mobile Devices.

 Customer also wanted to merge related processes that are spread across
 ERP into Applications to remove duplicate entries and to validate
 process for Entry Accuracy.

 Components:

-   SAP Cloud Platform Portal

-   SAP Cloud Platform Identity and Authentication Services

-   SAP Cloud Platform Integration Suite

-   SAP ERP 6.0 EhP 8

-   SAP S/4 HANA Value Driver:

-   Digitizing processes & providing employees with access to real-time
     Information - resulting in increased productivity & customer
     satisfaction.

-   Eliminated annual need of 200,000 paper pages.

-   Real-time bookings = 10-fold increase in efficiency. Business
    Pattern:

-   Digitizing existing business processes.

-   SAP Fiori applications and mobile applications accessing backend
     data in real-time.

-   ![](.//media/image2.png)<img src=".//media/image14.jpeg" style="width:3.72937in;height:1.91344in" /Custom
    UX with reading data from SAP back end. Real-time Industry
    Management Oil & Gas / Operations

 Use case:

 Customer was looking to reduce the non-productive time during well
 operations. Non- productive time caused by mechanical failures,
 weather, and logistical problems add substantial overhead to
 operations. Reductions in these overheads can result in lower costs
 and improved health, safety, and environmental performance.

 Components:

-   Mobile Services, OData Provisioning, Portal, iRPA, Workflow
     Management, Integration Suite, HANA DB, Document Service

    -   SAP ERP

    -   SAP SuccessFactors

    -   Legacy DB, Geotab Data (3rd party) Value Driver:

    -   Faster decision making ability for increased efficiency.

    -   Reducing operational cost by providing remote assistance, 12%
         reduction in cycle times.

    -   Leveraging AI to identify data anomalies for faster reaction.

    -   Improved employee health and safety by 10%. Business Pattern:

    -   Applying real time business processes.

    -   Applying innovative AI-based analytical capabilities.

    -   Providing multi-channel UX.

    -   Bringing together data from various systems.

 Innovating Customer Service Automotive / Customer Experience

![](.//media/image15.jpeg)

 Use case:

 Sales agents that are handling car delivery at the dealership did not
 have a consolidated insight into customer orders and production status
 as it was a paper intensive process to coordinate across multiple
 departments. To ensure they can provide a premium customer experience
 in new car delivery and react to changes on the fly, the company
 turned to experts from SAP and Apple to create a "car delivery"
 application.

 Components:

-   Cloud Connector

-   Mobile Services

-   SAP S/4 HANA

-   SAP Business Warehouse

-   Various 3rd party tools Value Driver:



-   Deliver consistent premium experience.

-   Standardize processes across dealers.

-   Reduce underutilized assets.

-   Increase sales rep insight into order status for better change
     management.

-   Digitize custom car delivery process. Business Pattern:

-   Digitizing existing business processes.

-   Applying real time business processes.

-   Multi-channel, custom UX.

 LESSON SUMMARY

 You should now be able to:

-   Explain the tools used for creating an extension

 Building Connections
====================

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Discover the place and the features of the Cloud Connetor in
    connectivity

### <img src=".//media/image16.jpeg" style="width:3.77in;height:1.7225in" /<img src=".//media/image17.jpeg" style="width:5.66312in;height:2.62844in" /Cloud Connector Features

![](.//media/image2.png)![](.//media/image2.png)

 Classification in the Extension Suite

 In this lesson we will look at the following tools

 Slide

 1: Cloud Connector

 2: SAP Cloud Platform Integration 3: API Business HUB

 4: SAP Graph

 5: Enterprise Messaging

 We have already discussed the API Business HUB, SAP Graph, SAP Cloud
 Platform Integration and Enterprise Messaging as part of the
 Integration Suite. Therefore, we will only look at the Cloud Connector
 below.

![](.//media/image2.png)

 <img src=".//media/image18.jpeg" style="width:5.1675in;height:2.51062in" /Connectivity
 Service at SAP Cloud Platform Slide

 In the upper part you can see the Cloud Platform. In the lower part
 the two connected landscapes. One is a direct connection that can be
 reached via HTTPs, and an on-premise system connected via the Cloud
 Connector. Communication is bi-directonal

 The Connectivity service allows SAP Cloud Platform applications to
 securely access remote services that run on the Internet or
 on-premise. This service:

-   Allows subaccount-specific configuration of application connections
     via destinations.

-   Provides a Java API that application developers can use to consume
     remote services.

-   Allows you to make connections to on-premise systems, using the
     Cloud Connector.

-   Lets you establish a secure tunnel from your on-premise network to
     applications on SAP Cloud Platform, while you keep full control
     and auditability of what is exposed to the cloud.

    -   <img src=".//media/image19.jpeg" style="width:5.07in;height:2.79094in" /Supports
         both the Neo and the Cloud Foundry environment for application
         development on SAP Cloud Platform.

![](.//media/image2.png)![](.//media/image2.png)

 <img src=".//media/image20.jpeg" style="width:4.745in;height:1.495in" /Slide

 Get more details:

 Serves as a link between SAP Cloud Platform applications and
 on-premise systems.

-   \- Combines an easy setup with a clear configuration of the systems
     that are exposed to the SAP Cloud Platform.

    -   Lets you use existing on-premise assets without exposing the
        entire internal landscape. Runs as on-premise agent in a secured
        network.

-   \- Acts as a reverse invoke proxy between the on-premise network and
     SAP Cloud Platform.

 Provides fine-grained control over:

-   \- On-premise systems and resources that can be accessed by cloud
     applications.

    -   Cloud applications using the Cloud Connector.

 Lets you use the features that are required for business-critical
 enterprise scenarios.

-   \- Recovers broken connections automatically.



-   Provides audit logging of inbound traffic and configuration changes.

-   Can be run in a high-availability setup.

![](.//media/image21.jpeg)![](.//media/image22.jpeg)![](.//media/image2.png)

 <img src=".//media/image23.jpeg" style="width:3.41656in;height:2.0475in" /Connecting
 Cloud Applications to On-Premise Systems

 Slide

 <img src=".//media/image24.jpeg" style="width:3.3475in;height:2.04344in" /Data
 access is based on the SAP Cloud Platform - subaccount. Here is the
 example of the Destination API's . The tunnel is TSL encrypted. The
 Cloud Connector then distributes the calls to various connected
 backend connections.The idea is to provide data from the on- premise
 network on the SAP Cloud Platform.

![](.//media/image2.png)

 Connecting On-Premise Database Tools to SAP HANA Databases

 Slide

 In this case, the data access starts from the on-premise database. On
 the SAP Cloud Platform

 <img src=".//media/image25.jpeg" style="width:4.745in;height:1.91344in" /-
 subaccount you need an SAP HANA service instance. The idea is to make
 data available from the cloud in the on Prem network.

![](.//media/image2.png)

 Feature Slide

 Get more in detail:

 High Availability Setup

-   The Cloud Connector lets you install a redundant (shadow) instance,
    which monitors the main (master) instance.

 Secure the Activation of Traffic Traces

-   Tracing of network traffic data may contain business critical
     information or security sensitive data. You can implement a
     "four-eyes" (double check) principle to protect your traces.

 Monitoring

-   Use various views to monitor the activities and state of the Cloud
     Connector.

 Alerting

-   Configure the Cloud Connector to send email alerts whenever critical
     situations occur that may prevent it from operating.

 Audit Logging

-   Use the auditor tool to view and manage audit log information

 LESSON SUMMARY

 You should now be able to:

-   Discover the place and the features of the Cloud Connetor in
     connectivity

<img src=".//media/image8.png" style="width:0.39289in;height:0.22548in" / Building Endpoints
=============================================================================================

199
---

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Explore the area of endpoint building

### Endpoint Building

 In particular, we'll look at the following topics in this lesson:

-   Classification in the Extension Suite.

-   What Is Workflow Management?

-   Cloud Application Model (CAP)

-   ABAP Restful Programming Model (RAP).

-   SAP Cloud SDK.

 Classification in the Extension Suite

![](.//media/image26.jpeg)

 In this lesson we will look at the following tools: 1: Workflow
 Management

 2: Cloud Application Model (CAP)

 3: ABAP Restful Programming Model (RAP)

 What Is Workflow Management?

 Digitize workflows, manage decisions, and gain end-to-end process
 visibility:

-   SAP Cloud Platform Workflow Management allows you to digitize
     workflows, manage decisions, gain end-to-end process visibility,
     and configure processes in a low-code approach.

-   It allows users to build, run, and manage workflows.

-   It allows users to digitize and automate decision making.

-   It enables process excellence, process transparency, process
     transformation by providing one view of the process.

-   <img src=".//media/image27.jpeg" style="width:5.0375in;height:2.405in" /Users
     can configure the process flow without the involvement of IT to
     improve process efficiency.

![](.//media/image2.png)

 SAP provides a comprehensive workflow platform that is heavily
 configuration (no-code)- based but also with textual code support.

 Drag and drop is supported for process, integration and UX, including
 agent conversations and integration with RPA bots. With the release of
 SAP Cloud Platform Workflow Management we are combining:

-   Workflow

-   Business rules

-   Process visibility in one service.

 With one user metric and service plan. We are also adding new features
 for business process experts to achieve process flexibility and also
 "live process content packages" as templates to accelerate your
 digital workflow automation projects.

 There are several use cases where digital process automation with SAP
 Cloud Platform Workflow Management will provide immediate value. You
 might want to group them like this:

-   Digital workflows and bots.

-   Process-driven application development.

    -   Process excellence and optimization.

    -   Facilitate process transformation journeys. Immediate outcomes
        are:

    -   Do more with less - empower employees through process
         automation, freeing up their time to do more meaningful work.

    -   Ensure compliance - comply with policies and regulations via
         clear responsibilities and audit trails.

    -   Flexibly adapt to new requirements - tailor business processes
         to the business needs and support new business model
         innovations.

 Business process experts are now able to manage changing business
 needs directly on live, running processes. Customers can use dedicated
 business expert tooling to discover, configure, and run workflows,
 like capital expenditure approvals, business partner creation or
 procurement data collection. To speed up and simplify these changes
 without involvement of the IT department, customers will be able to
 leverage pre-defined live process content packages via SAP API
 Business Hub to manage workflows on top of SAP ERP Central Component
 (ECC), SAP Utilities and SAP S/4HANA (Procurement). This enhanced
 real-time process flexibility increases the level of automation,
 empowers business users and ensures compliance with business policies
 and regulations via clear responsibilities and audit trails.

 Workflow management in your landscape

![](.//media/image28.jpeg)

 You can see on the left the possible data/event provider . These are
 connected via REST interfaces.

 The saturation options are indicated in the upper part for example
 Mobile Services, SAP Work Zone and much more.

 What is Cloud Application Model (CAP)?

-   <img src=".//media/image29.png" style="width:0.38189in;height:0.36179in" /The
     SAP Cloud Application Programming Model is a framework of
     languages, libraries, and tools for building enterprise-grade
     services and applications.

-   It guides developers along a ‘golden path’ of proven best practices
     and a great wealthof out-of-the-box solutions to recurring tasks.

 The CAP framework features a mix of proven and broadly adopted
 open-source and SAP technologies, as highlighted in the figure below.

 ![](.//media/image2.png)

 <img src=".//media/image30.jpeg" style="width:2.99in;height:1.59656in" /On
 top of open source technologies, CAP mainly adds:

 Core Data Services (CDS) as our universal modeling language for both
 domain models and service definitions.

 Service SDKs and runtimes for Node.js and Java, offering libraries to
 implement and consume services as well as generic provider
 implementations serving many requests automatically.

 Focus on Domain, Powered by CDS

 CAP places primary focus on domain, by capturing domain knowledge and
 intent instead of imperative coding - that means, What, not How -
 thereby promoting:

 Close collaboration of developers and domain experts in domain
 modeling. Out-of-the-box implementations for best practices and
 recurring tasks.

 <img src=".//media/image31.jpeg" style="width:3.12in;height:1.92562in" /Platform-agnostic
 approach to avoid lock-ins, hence protecting investments.

![](.//media/image2.png)

 The figure illustrates the prevalent use of CDS models (in the left
 column), which fuel generic runtimes, like the CAP service runtimes or
 databases.

 Core Data Services (CDS)

 CDS serves as our universal modeling language to capture static, as
 well as behavioral aspects of problem domains in conceptual, concise,
 and comprehensible ways, and hence is the very backbone of CAP.

 ![](.//media/image32.jpeg)

 Two tables, books and orders with the corresponding attributes, are
 created. A link from orders to books is further created.

![](.//media/image33.jpeg)

 Complete UI's can also be defined via CDS.

 In the service layer, any further implementations can be created, for
 example in Java with the cloud sdk and/or spring boot.

 Golden Path

 Following the golden path of the programming model helps you implement
 data models, services and UIs in order to develop stand-alone business
 applications or extend other cloud solutions, like SAP S/4 HANA or SAP
 SuccessFactors.

 Details about the "golden Path":

 Table 3: The Golden Path

<table
<thead
<tr class="header"
<thYour Task</th
<thUsing</th
<thand let the framework take care of....</th
</tr
</thead
<tbody
<tr class="odd"
<tdDefine your Data Model</td
<tdCDS</td
<tdautomatic deployment to SAP HANA</td
</tr
<tr class="even"
<tdDefine your Services</td
<tdCDS</td
<td<ul
<li<pTranslating to ODataservice definitions.</p</li
<li<pServing requests out of the box.</p</li
<li<pAuthorisation*) and standard validations.</p</li
<li<pFilling in primary keys and audit information.</p</li
<li<pWriting trace and audit logs.</p</li
<li<pHealth checks.</p</li
<li<petc.</p</li
</ul</td
</tr
</tbody
</table

<table
<thead
<tr class="header"
<thYour Task</th
<thUsing</th
<thand let the framework take care of....</th
</tr
</thead
<tbody
<tr class="odd"
<tdAdd Custom Logic</td
<tdJava EE, Spring Boot, Node.js</td
<td<ul
<li<pHandling database connections</p</li
<li<pIncluding tenant isolation</p</li
<li<pParsing input</p</li
<li<pSerialising responses</p</li
</ul</td
</tr
<tr class="even"
<tdAdd Fiori UIs</td
<tdCDS Annotations</td
<td<ul
<li<ptranslation to OData vocabularies</p</li
<li<pgenerating a SAP Fiori elements app skeleton</p</li
</ul</td
</tr
<tr class="odd"
<tdReuse existing Serv- ices</td
<td</td
<td</td
</tr
</tbody
</table

 What is ABAP Restful Programming Model ?

-   The ABAP RESTful programming model defines the architecture:

 \- for efficient end-to-end development of intrinsically SAP
 HANA-optimized OData services (such as SAP Fiori apps) in SAP Cloud
 Platform, ABAP Environment or Application Server ABAP.

 It supports the development of all types of Fiori applications as well
 as publishing Web APIs.

 It is based on technologies and frameworks such as Core Data Services
 (CDS) for defining semantically rich data models and a service model
 infrastructure for creating OData services with bindings to an OData
 protocol and ABAP-based application services for custom logic and
 SAPUI5-based user interfaces - as shown in the figure below.

 <img src=".//media/image34.jpeg" style="width:3.91219in;height:2.04344in" /Architecture
 Overview

![](.//media/image2.png)

 The architecture can be divided into:

-   Data Modelling & Behavior

-   Business service Provisioning

-   Service Consumption

 <img src=".//media/image35.jpeg" style="width:3.38in;height:1.85656in" /Data
 Modelling & Behavior

![](.//media/image2.png)

 The layer of data modeling and behavior deals with data and the
 corresponding business logic.

 The data model comprises the description of the different entities
 involved in a business scenario. We use CDS data modelling therefore.

 The behavior describes what can be done with the data model, for
 example if the data can be updated. (ABAP or BDEF)

 Business Service Provisioning

![](.//media/image36.jpeg)

 In the context of the ABAP RESTful programming model, a business
 service is a RESTful service which can be called by a consumer. It is
 defined by exposing its data model together with the associated
 behavior. It consists of a service definition and a service binding.

 <img src=".//media/image37.jpeg" style="width:1.40562in;height:1.58031in" /Service
 Consumption

![](.//media/image2.png)

 An OData service can be exposed as a UI service, that can be consumed
 by an SAP Fiori UI, or as a Web API that can be consumed by any OData
 client.

 SAP Cloud SDK

![](.//media/image38.jpeg)

 The Cloud SDK is a set of tools and libraries for consuming, building
 or extending SAP services and applications in the cloud-native way and
 deploying them to SAP Cloud Platform.

 SAP Cloud SDK was conceived as a collection of best practices for
 developing cloud-native applications withing SAP. Eventually it grew
 into a fully-fledged and feature rich development library consisting
 of three main components.

 We will have a quick look to the parts of SAP Cloud SDK.

 ![](.//media/image2.png)

 <img src=".//media/image39.jpeg" style="width:3.38406in;height:0.93844in" /Use
 Java or java script for your cloud native development. Java has the
 largest range of functions - all blue fields in the organization
 chart. Both implementations can also be used in the Cloud Application
 Programming Model (CAP).

 Continuous Delivery belongs to the Deploy & Create section and is
 discussed there.

![](.//media/image2.png)

 <img src=".//media/image40.jpeg" style="width:3.38406in;height:0.86125in" /For
 all API' for SAP S/4HANA listed in the SAP API Hub and others, there
 are predefined Java classes in the Cloud SDK. Access is via Typed
 Clients. This can be done with OData V2 , V4 and REST .

 <img src=".//media/image41.jpeg" style="width:4.80594in;height:1.63312in" /Business
 Partner oData API within API Business Hub

![](.//media/image2.png)

 You have -for example- Basic CRUD Functions, Filter and much more to
 consume a predefined OData API.

 <img src=".//media/image42.jpeg" style="width:3.38812in;height:0.86937in" /Code
 generator for Odata & REST

![](.//media/image2.png)

 While a number of pre-generated API's are already provided in the
 cloud sdk, of course, the possibility to create Java classes based on
 Custom OData or REST interfaces with the Code Generator also includes
 the possibility.

 <img src=".//media/image43.jpeg" style="width:3.38406in;height:0.86937in" /Support
 of multiple runtimes

![](.//media/image2.png)

 Supports multiple runtimes:

-   Cloud Foundry

-   KyMA

 Cloud native development approach

![](.//media/image44.jpeg)

 The Cloud native development approach consists of:

-   Multitenancy

-   Authentication Flows

-   Caching

-   Resilience

-   And many more

 <img src=".//media/image45.jpeg" style="width:3.38406in;height:0.86125in" /Additional
 functionality

![](.//media/image2.png)

 Additional functionality:

-   Client for BAPI/RFC

-   Integration

    -   Extensions

    -   Works with CAP

 LESSON SUMMARY

 You should now be able to:

-   Explore the area of endpoint building

 <img src=".//media/image8.png" style="width:0.39289in;height:0.22548in" /
 Adding Channels

211
---

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Explain which channels are available within the extension suite

### Channels

 In particular, we'll look at the following topics in this lesson.

-   Classification in the Extension Suite.

-   What is SAP Conversational AI?

-   Bot-Building Platform.

-   What is SAP Ui5?

-   SAP Cloud Platform Mobile Services

 Classification in the Extension Suite

 <img src=".//media/image46.jpeg" style="width:5.09031in;height:2.36844in" /In
 this lesson we will look at the following tools:

![](.//media/image2.png)

 In this lesson we will look at the following tools: 1: SAP UI5

 2: Conversational AI

 3: Mobile

 What is SAP Conversational AI?

-   SAP Conversational AI helps users efficiently manage business tasks.

-   As the conversational AI layer of SAP’s Business Technology
     Platform, it enables users to build and monitor intelligent
     chatbots in one interface to automate tasks and workflows.

 You can expect:

 Bots in any language

-   Leverage the power of our highly performing NLP technology capable
     of building human-like AI chatbots in any language.

-   Low-code bot building.

-   Customize and expand ready-to-use chatbots.

-   Multilingual Easy to use

 Simple UX, collaboration, organizational accounts, versioning and
 environments: we’ve made a bot platform all teams can smoothly use.

 Fastest time to market

 Through an efficient bot building process and a full integration to
 the SAP software suite, you can launch your bot in days.

 Bot-Building Platform

 <img src=".//media/image47.jpeg" style="width:3.4125in;height:2.1125in" /Your
 way to build bots

![](.//media/image2.png)

 Bot training

 Analyze text inputs and enrich key data in any language with our
 world-class natural language processing (NLP) technology.

 Bot building

 Build adaptable conversational flows and skills through our powerful
 bot builder.

 Bot connector

 Connect chatbots to any SAP solution, external communication channel,
 or back-end system.

 Bot analytics

Lesson: Adding Channels

 Understand how customers and employees talk to your chatbot and
 improve the user experience based on usage and training data.

 What is SAPui5

-   UI5 apps run on smartphones, tablets, and desktops. The UI controls
    automaticallyadapt themselves to the capabilities of each device and
    make the most of the availablereal estate.

-   It comes with built-in support for architectural concepts like MVC,
    two-way data binding, and routing.

-   It Includes standards like MVC and various data-binding types.

-   Further facts:

    -   Choose between different view formats (XML, HTML, JavaScript,
        JSON).

    -   Binding with OData, JSON, XML and other data formats.

    -   Built-in support tool for exploring the object tree and binding
        status.

-   Created by professionals, for modern developers building state of
    the art web applications.

-   It comes with all features needed to cover most current application
    requirements, with standards high enough to be delivered in standard
    SAP solutions:

    -   Translation and internationalization support.

    -   Extensibility concepts at code and application level.

    -   High Contrast theme to aid visually impaired users.

 What is Fiori?

-   SAP Fiori is the design language that brings great user experiences
    to enterprise applications. Based on user roles and business
    processes, SAP Fiori simplifies doing business.

-   SAP Fiori is a paradigm shift away from monolithic ERP solutions
    towards light-weight apps tailored to the users’ tasks.

-   It is:

    -   Role-Based

    -   Adaptive

    -   Coherent

    -   Simple

    -   Delightful

 <img src=".//media/image48.jpeg" style="width:2.4375in;height:2.08812in" /SAP
 Cloud Platform Mobile Services

![](.//media/image2.png)

 SAP Cloud Platform Mobile Services:

 1: Mobile Cards

 2: Platform SDK (iOS, Android) 3: Mobile Development Kit

 Key capabilities are:

-   Offline OData synch, push notification.

-   Enterprise security with encryption and authentication.

-   Reporting and Usage analytics.

-   Scalable supportability features.

-   Hybrid or full-cloud scenarios supported.

-   Back-end mobile integration and creation toolset. Benefits

-   Increase developer productivity with support for a wide range of
     mobile app types to meet all use cases.

-   Engage a highly mobilized workforce, consumers, suppliers and
     partners with preferred channel.

-   Increase user productivity via anytime, anywhere connectivity with
     back end systems.

-   Scale to meet large enterprise app and user demands.

 LESSON SUMMARY

 You should now be able to:

-   Explain which channels are available within the extension suite

 Explaining Deployment and Operations
====================================

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Identify which tools for the deployment and operate area exist

### Deployment and Operations

 In particular, we'll look at the following topics in this lesson:

-   Classification in the Extension Suite.

-   What is SAP Work Zone?

-   What is SAP Fiori Launchpad?

-   What is Portal?

-   What is Open Piper?

-   What are CI/CD services?

-   What are Transport Management Services?

 <img src=".//media/image49.jpeg" style="width:5.10656in;height:2.41719in" /Classification
 in the Extension Suite

![](.//media/image2.png)

 In the following we will deal with the following components: 1: SAP
 Work Zone

 2: SAP Fiori Launchpad

 3: Portal

 4: Open Piper

 5: CI/CD services

 6: Transport Management Services

 The runtimes are discussed in another lesson.

 What is SAP Work Zone?

-   SAP Work Zone provides an intuitive digital experience solution,

-   Which increases user engagement and productivity,

-   By providing a delightful and personalized working environment

-   <img src=".//media/image50.jpeg" style="width:2.665in;height:2.14094in" /To
     easily access relevant business applications, information and
     collaboration at the moment of truth.

![](.//media/image2.png)

 <img src=".//media/image51.jpeg" style="width:3.6075in;height:2.08406in" /It
 is based on Jam, and it is personalized.

![](.//media/image2.png)

 All apps, tasks, etc. that I need for my job every day should be on
 this workplace.

 What is SAP Fiori Launchpad ?

-   SAP Cloud Platform Launchpad enables organizations to establish an
     intuitive, central entry point,

-   Unifying access to multiple SAP products and solutions (cloud and
     on-premise).

 Key Capabilities and Benefits are:

 Key Capabilities

-   Central home page providing harmonized user experience.

-   Role-based access to applications (fro example from multiple SAP
    S/4HANA systems).

-   Application integration for different SAP UI technologies and
    third-party web apps.

-   Configuration of launchpad services and content (for example custom
    roles and tiles).

-   Integration with central services such as inbox, notifications and
     SSO. Benefits

-   Users quickly and easily find relevant apps and services to get
    their job done efficiently.

-   Streamlined business roles and end-to-end business processes with
    app-to-app navigation across products.

![](.//media/image52.jpeg)

 The difference to SAP Work Zone is, among other things, that there is
 no collaboration here.

 What is Portal ?

-   SAP Cloud Platform Portal empowers organizations to build digital
     experiences through engaging business sites.

-   Key capabilities:

    -   Build engaging user experiences with *SAP Fiori 3* or custom
         site design.



-   Provide central access to applications (cloud and on premise).

-   Integrate apps based on SAPUI5/Fiori and classic SAP UI
    technologies.

-   Use public APIs to extend and optimize site experience.



-   Benefits:



-   Simplify and streamline access to applications and information.

-   Increase user satisfaction and engagement.

-   Drive UX innovations and gain agility using cloud services.

-   Enhance administration efficiency via templates and open
    integration.

 <img src=".//media/image53.jpeg" style="width:3.4125in;height:1.625in" /Use
 case of portal service

![](.//media/image2.png)

 The portal can be accessed directly from the mobile phone. The
 Launchpad modules and apps can be used on the portal.

 Sample of an Portal App

![](.//media/image54.jpeg)

 The figure shows a sample of an Portal App.

 CI/CD services

 What are CI/CD services?

-   At the moment, SAP offers three different solutions that help you
    apply CI/CD in your software development:

    -   SAP Cloud Platform Continuous Integration and Delivery.

    -   Project "Piper".

    -   Continuous Integration and Delivery Best Practices GuideThe
         CI/CD Best Practices Guide provides best practice procedures
         to implement continuous delivery pipelines on any CI/CD stack
         and demonstrates how to apply the principles of CI/CD to SAP-
         specific technologies.

 SAP Cloud Platform Continuous Integration and Delivery is a service on
 SAP Cloud Platform, which lets you configure and run predefined
 continuous integration and delivery pipelines that test, build, and
 deploy your code changes. At the moment, it supports the development
 of SAP Cloud Application Programming Model (CAP) and SAPUI5/SAP Fiori
 applications.

![](.//media/image55.jpeg)

 It is a service on the SAP Cloud Platform.

 In the cockpit, the individual tasks/jobs are configured.

 Open Piper

 What is Open Piper?

-   Continuous delivery is a method to develop software with short
    feedback cycles.

-   It is applicable to projects both for SAP Cloud Platform and SAP
    on-premise platforms.

-   SAP implements tooling for continuous delivery in project "Piper".
    The goal of project"Piper" is to substantially ease setting up
    continuous delivery in your project using SAP technologies.

 Project "Piper" offers you the following artifacts:

-   A set of ready-made Continuous Delivery pipelines for direct use in
     your project.

-   ABAP Environment Pipeline.

-   General Purpose Pipeline.

-   SAP Cloud SDK Pipeline.

-   A shared library that contains reusable step implementations, which
     enable you to customize our preconfigured pipelines, or to even
     build your own customized ones.

-   A standalone command line utility for Linux and a GitHub Action.

 Note: This version is still in early development. Feel free to use it
 and provide feedback, but don't expect all the features of the Jenkins
 library.

-   A set of Docker images to setup a CI/CD environment in minutes using
     sophisticated life- cycle management.

-   Also used in CAP.

 Project "Piper" is an open-source project that provides preconfigured
 Jenkins pipelines, which you can use in your own Jenkins master
 infrastructure and adapt according to your needs, if necessary. It
 consists of two components:

-   A shared library, which contains the description of steps,
     scenarios, and utilities required to use Jenkins pipelines.

-   A set of Docker images.

 <img src=".//media/image56.jpeg" style="width:3.705in;height:1.86875in" /Sample
 Pipline in jenkins running at Docker

![](.//media/image2.png)

 You will see several steps with configured functionality, Init, Build,
 Local Tests …

 Transport Management Services

 What are Transport Management Services ?

-   Manage transports of development artifacts and application-specific
     content.

-   SAP Cloud Platform Transport Management lets you manage transports
     between SAP Cloud Platform accounts in Neo and Cloud Foundry
     environments, such as from DEV to TST and PROD accounts.

-   It lets you transport development artifacts (in form of Multitarget
     Application archives) and application-specific content, such as
     SAP Cloud Platform Integration content.

 ![](.//media/image57.jpeg)

 Here, the possible things are still shown schematically.

 <img src=".//media/image58.jpeg" style="width:4.04625in;height:2.69344in" /Cockpit
 of the Transport service at SAP Cloud Platform

![](.//media/image2.png)

 On the left is the menu with which can configure and monitor
 transports.

 LESSON SUMMARY

 You should now be able to:

-   Identify which tools for the deployment and operate area exist

<img src=".//media/image8.png" style="width:0.39289in;height:0.22548in" / Undergoing a birds view: In-App Extensions
=====================================================================================================================

223
---

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Undergo a Birds View In-App Extensions

### In-App Extensions, a Birds View

 In particular, we'll look at the following topics in this lesson:

-   Birds view of possible extensions independent of the SAP S/4HANA
    version.

 Birds view In-App Extensions

 All in-app extensions are technically implemented inside the core of
 SAP S/ 4HANA.

 As a result, no remote communication between the extension and the
 extended app is required.

 <img src=".//media/image59.jpeg" style="width:3.0875in;height:2.42937in" /SAP
 S/4HANA offers the following in-app extension options depending on the
 version.

![](.//media/image2.png)

 The figure shows all possible options:

 1 User Interface Adaptation

 Key users may change the layout of tables and forms directly in the
 running user interface.

 A special graphical user interface adaptation mode provides the
 mechanisms to hide fields in existing forms, tables, or filters; to
 rename labels; to add fields to the user

 interface from the field repository; and to move fields or entire
 blocks to other sections of the screen.

1.  Custom Fields

 In the Custom Fields and Logic SAP Fiori application, you can add and
 edit custom fields to extend SAP database tables, CDS views, and OData
 APIs.

 Moreover, this extension application helps to define how custom fields
 are used in user interfaces, reports, or forms.

 Furthermore, you can use custom fields along with predefined business
 scenarios so that all involved business objects are extended and
 values are passed along automatically.

1.  Custom CDS Views, Analytics, Forms

 The Custom CDS View application enables customers to create new views
 based on an existing view model supporting features like associations,
 joins, transformations, field relabeling, selections, etc.

 With OData APIs on top of these views, customers may, in addition,
 expose the data for consumption outside the SAP S/ 4HANA core.

1.  Business Logic

 Many SAP S/ 4HANA applications have enhancement spots (also called
 Business Add- Ins \[BAdIs\]). With the ABAP web editor, customers may
 create custom logic for the BAdIs.

 Typically, customers implement additional checks, set default values,
 or create mappings in combination with custom fields.

1.  Custom Business Objects

 Besides custom views, you can create completely new business objects
 using the Custom Business Objects application.

 This application helps define the business object structure in the
 form of business object nodes, which automatically create the required
 database tables

1.  Custom User Interfaces

 You can use the SAP Web IDE to create your own SAP Fiori user
 interfaces either from scratch or based on templates. The SAP Fiori
 user interfaces consume SAP S/ 4HANA's RESTful OData interfaces.

 How to Perform an InApp Extensibility in an SAP S/4HANA System What
 are you going to show?

 It shows how to extend a standard interface (BusinessPartner) with its
 own fields. The Standard BusinessPartner object is to be extended with
 social media fields. The following demo shortens the procedure.

![](.//media/image60.png)

 ![](.//media/image60.png)

 Structure of the Demo:

-   Create and publish a custom business object: Step 1.

-   Investigate the corresponding Custom CDS View : Step 2.

-   Expose the Custom View as OData interface: Step 3.

-   Explore the OData Interface in SDAP Gateway: Step 4.

1.  Create and publish a custom business object.

    1.  Call
        [<uhttps://wdflbmt7189.wdf.sap.corp/ui</u](https://wdflbmt7189.wdf.sap.corp/ui)
        on the *dx-s4c1911-sactest*.

    2.  Log on with the following credentials:

<table
<thead
<tr class="header"
<thField</th
<thValue</th
</tr
</thead
<tbody
<tr class="odd"
<tdUser</td
<tds4c-00</td
</tr
<tr class="even"
<tdPassword</td
<tdWelcome1</td
</tr
</tbody
</table

![](.//media/image60.png)

1.  ![](.//media/image61.jpeg)The required roles are already assigned.

2.  Choose *YY1\_BPSOCIALMEDIAACCOUNT*.

 ![](.//media/image62.jpeg)

1.  Click on *Go To Generated UI* with Open link in a new tab for better
     Navigation.

2.  ![](.//media/image63.jpeg)Click on the button *Go to* see one
     Business Partner.

3.  Click on the line with the selected Business Partner

 ![](.//media/image64.jpeg)

1.  ![](.//media/image65.jpeg)Check the entries with at the newly added
     fields *Service/Account*and *Lifecycle Status*.

2.  Go back to your *Custom Business Object App*.

3.  On the details page choose *Fields* → *SocialMediaAccount* to see
     the fields.

 ![](.//media/image66.jpeg)

1.  Investigate the corresponding custom CDS view.

    1.  Open Custom CDS View (1) in the launchpad where you search for
         the term

#### YY1\_BPSOCIALMEDIAACCOUNT.

 ![](.//media/image67.jpeg)The Custom View aggregates the standard
 object *BusinessPartner* with the Custom Object
 *YY1\_BPSOCIALMEDIAACCOUNT*.

1.  In the *Name* field search for **YY1\_BP\_SocialMedia**.

2.  ![](.//media/image68.jpeg)![](.//media/image69.png)Click on the
     *Edit Draft* button at the top right after marking the selected
     line.

3.  Show the structure there.

4.  Click *Preview* at the right bottom of the footer.

 ![](.//media/image70.jpeg)

1.  ![](.//media/image71.jpeg)This is the result:

2.  The Custom view with the new fields *Service* and *Account*, now
     filled with data

 ![](.//media/image72.jpeg)

1.  Expose the Custom View as OData interface.

    1.  Open the Custom Communication Scenario App via *Home* menu or
         search for it:

 ![](.//media/image73.jpeg)

1.  ![](.//media/image74.jpeg)Click on the row *YY1\_BP\_SOCIALMEDIA* to
     see the two bound artifacts: the Business Object and the view:

2.  Search for *Communication Arrangement* App and in the search bar
     enter

#### ![](.//media/image75.png)YY1\_BP\_SOCIALMEDIA.

1.  Click on the row *YY1\_BP\_SOCIALMEDIA* to see the bound system and
     the URL:

 ![](.//media/image76.jpeg)

1.  Explore the OData Interface in SDAP Gateway.

    1.  Choose *SAP Logon*.

    2.  ![](.//media/image77.jpeg)Start the system *T77*.

    3.  Log on with the following credentials:

<table
<thead
<tr class="header"
<thField</th
<thValue</th
</tr
</thead
<tbody
<tr class="odd"
<tdUser</td
<tds4c-00</td
</tr
<tr class="even"
<tdPassword</td
<tdWelcome1</td
</tr
</tbody
</table

![](.//media/image60.png)

1.  Choose the transaction /N/IWFND/MAINT\_SERVICE.

 ![](.//media/image78.jpeg)

1.  Find all available services.

2.  Navigate to the bottom and find the *Technical Service* named

 ![](.//media/image79.jpeg)*YY1\_BP\_SOCIALMEDIA\_CDS*.

1.  Click on the *SAP Gateway Client* button, then choose *Excecute*.

 ![](.//media/image80.jpeg)

1.  At the bottom, choose *EntitySets - YY1\_BP\_SocialMedia* and click
     on *Execute* again.

 ![](.//media/image81.jpeg)

1.  Now you see the added fields *Service* and *Account*.

 LESSON SUMMARY

 You should now be able to:

-   Undergo a Birds View In-App Extensions

 Undergoing a birds view: Side-by-Side
=====================================

 Extensibility

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Undergo a Birds View Side-by-Side Extensibility

### Side-By-Side Extensions in SAP S/4HANA, a Birds View

 Birds view In-App Extensions

 In particular, we'll look at the following topics in this lesson:

-   Birds view of possible extensions independent of the SAP S/4HANA
    version.

-   Offered SAP S/4HANA versions by SAP, status today (2020).

 Extensions Independent of the SAP S/4HANA Version

 Remember what side-by-side extension means:

-   Extension and integration with custom or standard business
    applications of the SAP cloud platform. Either via stable APIs or
    through business events from an SAP product, for example SAP
    S/4HANA.

-   All side-by-side extensions are technically implemented outside the
    core of SAP S/ 4HANA.

-   <img src=".//media/image82.jpeg" style="width:3.38in;height:2.19781in" /As
    a result, remote communication between the extension and the
    extended app is required.

![](.//media/image2.png)

 The picture shows the side-by-side extensibility use cases:

 S1: Custom UI on SAP CP

-   Custom SAP Fiori UI, build with SAP Web IDE, running on SAP CP with
    SAP pre- defined released OData service

-   Use UI5 technology, UI5 templates, editors, testing capabilities

-   Build UI applications with offline support.

-   Deploy to your SAP CP account (or to SAPUI5 ABAP repository) S2: SAP
     CP Application

-   SAP CP application (Java, JavaScript, HANA) running on SAP CP with
    SAP pre- defined released OData service

-   Benefit from open standards and from a partner ecosystem that
    contribute value to existing solutions and services

-   Integration Scenarios (Cloud Integration), benefit from SAP
    prepackaged integration content as reference templates to quickly
    realize new business scenarios.

 S3: Custom UI on SAP CP or SAP CP app w/ custom OData service

-   Same as S1 and S2, but with custom OData service built with in-app
     extensibility tools S4: New SAP CP Service called from SAP S/4
     Extension

 SAP S/4HANA, Success Factors, C/4HANA can fire business events to call
 apps on the SAP CP

 S5: Analytics on SAP CP (Replication)

 <img src=".//media/image83.jpeg" style="width:5.4275in;height:2.4375in" /Offered
 SAP S/4HANA Versions

![](.//media/image2.png)

 The figure gives an overview of the most important features, offered
 by SAP today (2020). The following SAP S/4HANA versions are offered by
 SAP, status today (2020):

-   SAP S/4HANA Cloud essentials edition (ES): previously called
    Multi-Tenant Edition.

-   SAP S/4HANA Cloud extended edition (EX): previously called
     Single-Tenant Edition.

    -   SAP S/4HANA Private Cloud managed by SAP (HEC).

    -   SAP S/4HANA On-Premise or managed by cloud provider Hyperscaler.

 As you can see the ES version only has the key user tools for In-App
 Extensibility available. Compared to the other versions you have only
 limited extensions. Here the necessity is the biggest to realize the
 extensions over Side-by-Side.

 The remainder of the document outlines common extension scenarios
 which are split between:

-   Enhancements - changing something that was provided as standard.

-   Custom Development - building something new (in some cases using a
    standard template as a starting point).

-   Configuration - adapting the standard to your needs.

 How to Perform an Side-By-Side Extensibility What are you going to
 show?

 The use of a Custom OData interface within a microapp in Java. We use
 the SAP Cloud SDK.

 Two examples are shown. One with a SAP Fiori app that also displays
 custom fields (inApp\_address-manager).

 Another that calls only the default interface 2
 (extensibility-demo-simple).

 Workflow of the applications

![](.//media/image84.jpeg)

 The figure illustrates the workflow of the applications, used in this
 demonstration.

 ![](.//media/image60.png)

![](.//media/image60.png)

 The demonstration consists of the following four parts:

-   Execution of the application - inApp\_address-manager: step 1.

-   Show the relevant locations in the implementation: step 2.

-   Running the extensibility-demo-simple application: step 3.

-   Show the relevant code snippets: step 4.

1.  Execute the application - inApp\_address-manager.

    1.  Go to the url [<uhttps://inappaddress-manager-daring-</u
        <udingo.cfapps.eu10.hana.ondemand.com</u](https://inappaddress-manager-daring-dingo.cfapps.eu10.hana.ondemand.com/).

    2.  Click on the *Address Manager* link.

    3.  ![](.//media/image85.jpeg)Click on the user *John Doe* (1).

    4.  Under (2) you can see extensions of the standard business
        cutting point A\_BusinessPartner. These were created by an InApp
        Extensibility.

2.  Show the relevant locations in the implementation.

    1.  Navigate to:
        [<uhttps://account.eu2.hana.ondemand.com/cockpit\#/globalaccount/</u
        <u822af597-cc75-4fbe-b83d-71c32cf0394a/subaccount/77199a89-</u](https://account.eu2.hana.ondemand.com/cockpit%23/globalaccount/822af597-cc75-4fbe-b83d-71c32cf0394a/subaccount/77199a89-a0c0-4d0b-8733-5656f9ec54e8/saasApplications)

 [<ua0c0-4d0b-8733-5656f9ec54e8/saasApplications</u](https://account.eu2.hana.ondemand.com/cockpit%23/globalaccount/822af597-cc75-4fbe-b83d-71c32cf0394a/subaccount/77199a89-a0c0-4d0b-8733-5656f9ec54e8/saasApplications).

 The source code is implemented on the Business Application Studio.

1.  As login enter the following data:

<table
<thead
<tr class="header"
<thField</th
<thValue</th
</tr
</thead
<tbody
<tr class="odd"
<tdUser</td
<td<a href="mailto:cp-a@education.cloud.sap"cp-a@education.cloud.sap</a</td
</tr
<tr class="even"
<tdPassword</td
<tdWelcome1</td
</tr
</tbody
</table

![](.//media/image60.png)

1.  ![](.//media/image86.jpeg)In the *SAP Business Application Studio*
     tile, click *go to application*.

2.  As login enter the following data:

<table
<thead
<tr class="header"
<thField</th
<thValue</th
</tr
</thead
<tbody
<tr class="odd"
<tdEmail</td
<td<a href="mailto:cp-a@education.cloud.sap"cp-a@education.cloud.sap</a</td
</tr
<tr class="even"
<tdPassword</td
<tdWelcome1</td
</tr
</tbody
</table

![](.//media/image60.png)

1.  Start the workspace *JAVA\_DEMO* with (1). It takes a little while.
     After successful start, the link becomes active JAVA\_DEMO and
     RUNNING appears.

2.  Click on the link *JAVA\_DEMO* (2).

 ![](.//media/image87.jpeg)

1.  ![](.//media/image88.jpeg)You can see the demos listed under
    *Projects*.

2.  Click on the project *inApp\_address-manager* and open to the *order
    commands,models and util*.

 ![](.//media/image89.jpeg)

1.  You see the Custom Business Objects.

 ![](.//media/image90.jpeg)

1.  Run the extensibility-demo-simple application.

    1.  Go to the following URL
         [<uhttps://extensibility-demo-simple-appreciative-</u
         <uparrot.cfapps.eu10.hana.ondemand.com</u](https://extensibility-demo-simple-appreciative-parrot.cfapps.eu10.hana.ondemand.com/).

 ![](.//media/image91.jpeg)This application shows only the pure
 BusinessPartner implementation.

1.  Click on the link / [<u/businesspartners - Business Partner
     data</u](https://extensibility-demo-simple-appreciative-parrot.cfapps.eu10.hana.ondemand.com/businesspartners).

 ![](.//media/image92.jpeg)

1.  Show the relevant code snippets.

    1.  In the Business Application Studio, open the project
         *extensibility-demo-simple*.

    2.  Find the *BusinessPartnerServlet.java*.

 ![](.//media/image93.jpeg)

1.  Under (2) you will see the context path of the URL.

2.  Under (3) the destination used.

3.  Under (4) you will see the BusinessPartner implementation of the SAP
    Cloud SDK.

4.  Navigate to the KTE-EXT-DEMO subaccount with:[<uhttps://</u
    <uaccount.eu2.hana.ondemand.com/cockpit\#/globalaccount/822af597-cc75-4fbe-</u
    <ub83d-71c32cf0394a/subaccount/77199a89-a0c0-4d0b-8733-5656f9ec54e8/spaces</u](https://account.eu2.hana.ondemand.com/cockpit%23/globalaccount/822af597-cc75-4fbe-b83d-71c32cf0394a/subaccount/77199a89-a0c0-4d0b-8733-5656f9ec54e8/spaces)

5.  Navigate to the KTE-EXT-DEMO.

6.  Open the destinations via the *Destinations* link and find the
    Destination *MyErpSystem*

 ![](.//media/image94.jpeg)as used in the *BusinessPartnerServlet*,
 above. (2).

 LESSON SUMMARY

 You should now be able to:

-   Undergo a Birds View Side-by-Side Extensibility

 Explaining Extensibility Possibilities Depending
================================================

 on the SAP S/4HANA Version, an Overview

 LESSON OBJECTIVES

 After completing this lesson, you will be able to:

-   Realize which extensions, in-App and side-by-side, are available
    depending on the SAP S/ 4HANA versions

### Possibilities of Extensibility Depending on the SAP S/4HANA Version

 In particular, we'll look at the following topics in this lesson:

-   Explanations for this lesson.

-   User interface enhancement.

-   Data model enhancement - add custom fields to a standard SAP
    business object.

-   Data model enhancement - custom CDS views.

-   Business logic enhancement.

-   Custom development – apps.

-   Custom development – workflow.

-   Output – print forms and emails.

-   Configuration

-   Restricted ABAP.

 Key User Tools in SAP Fiori Launchpad

 For each SAP S/4HANA version the possible extension techniques are
 listed below.

 Key User Extensibility describes the possibility to implement
 enhancements with predefined apps. In SAP S/4HANA essential, this is
 the only enhancement option. It also includes the possibility of
 restricted programming with Restricted ABAP.

-   Everything that is possible in Essential is also possible for
    Extended and HEC/onPrem.

-   Everything that is possible in Extended is also possible for
    HEC/onPrem.

 ![](.//media/image95.jpeg)

 The screenshot illustrates the available tiles for extensibility in
 the SAP Fiori Launchpad.

 User Interface Enhancement

![](.//media/image96.jpeg)

 The following table gives further details about the illustration of
 the figure above:

 Table 4: Details about the illustration

<table
<thead
<tr class="header"
<thUI Technology</th
<thEssential</th
<thExtended</th
<thHEC/onPrem</th
</tr
</thead
<tbody
<tr class="odd"
<tdAll</td
<td<pPersonalization.</p
<pFor some UI elements users can make changes themselves. For example, for ta- bles, it's typically pos- sible to change the fields displayed, the order of the columns or the overall sort or- der. If the require- ments are user-spe- cific, then consider any personalization options first.</p</td
<td</td
<tdInclude all the left</td
</tr
<tr class="even"
<td</td
<tdConfiguration / Set- tings. To apply changes more widely, there may be associ- ated configuration or settings relating to the app. These may control for example what fields are dis- played, read only or mandatory. It's worth checking if such con- figuration is available ahead of using other techniques. If the app being changed is available in SAP S/4 HANA Cloud (multi- tenant) then the re- lated settings may be available there also, however this is not guaranteed.</td
<td<pConfiguration / Set- tings.</p
<pTo apply changes more widely, there may be associated configuration or set- tings relating to the app. These may con- trol for example what fields are displayed, read only or manda- tory. It's worth check- ing if such configura- tion is available ahead of using other techni- ques. If the app being changed is available in SAP S/4 HANA</p
<pCloud (multitenant) then the related set- tings may be availa- ble there also, howev- er this is not guaran- teed.</p</td
<tdInclude all the left</td
</tr
</tbody
</table

<table
<thead
<tr class="header"
<thUI Technology</th
<thEssential</th
<thExtended</th
<thHEC/onPrem</th
</tr
</thead
<tbody
<tr class="odd"
<tdSAPUI5 Fiori Apps</td
<tdRun Time Adaptation (RTA). Use to make simple changes like hiding or adding fields or rearranging fields.</td
<td<pSAP Web IDE - hide controls.</p
<pSuitable if you only need to hide some UI controls, but the app does not support Run Time Adaptation.</p
<pNote that using SAP Web IDE to change the UI of a standard app is not supported in SAP S/4 HANA</p
<pCloud (multi-tenant).</p</td
<tdInclude all the left</td
</tr
<tr class="even"
<td</td
<td</td
<tdSAP Web IDE - exten- sion points Use pre- defined extension points to change the app. These are docu- mented in the SAP Fiori Apps Library.</td
<tdInclude all the left</td
</tr
<tr class="odd"
<td</td
<td</td
<td<pSAP Web IDE - re- place views.</p
<pIf the available exten- sion points are not sufficient, then the entire view may be replaced with a cus- tom one. The custom view may be created as a copy of the standard one. The disadvantage of this approach is that any improvements to the standard screen sup- plied through up- dates or SAP Notes will not automatically be applied to the cus- tom one – if needed they would have to be applied manually.</p</td
<tdInclude all the left</td
</tr
<tr class="even"
<tdWeb Dynpro Apps, in- cluding Floorplan Manager apps</td
<td</td
<tdSAP Screen Personas or Web Dynpro Cus- tomizin</td
<tdInclude all the left</td
</tr
</tbody
</table

<table
<thead
<tr class="header"
<thUI Technology</th
<thEssential</th
<thExtended</th
<thHEC/onPrem</th
</tr
</thead
<tbody
<tr class="odd"
<tdWeb UI Apps. For ex- ample SAP S/4 HA- NA for Customer Management; SAP Solution Manager, SAP ChaRM</td
<td</td
<tdSAP Screen Personas or Web UI Configura- tion Tool</td
<tdInclude all the left</td
</tr
<tr class="even"
<td</td
<td</td
<tdSAP Screen Personas</td
<td</td
</tr
<tr class="odd"
<td</td
<td</td
<tdClassic extensibility techniques such as CMOD enhance- ments or BAdIs. This technique may be needed to add cus- tom fields to the UI, if this cannot be done using the Custom Fields and Logic app.</td
<td</td
</tr
</tbody
</table

 Data Model Enhancement - Add Custom Fields to a standard SAP business
 object

![](.//media/image97.jpeg)

 Further information about the figure:

 Essential

 Key user extensibility

-   Use the *Custom Fields and Logic* app to define additional custom
    fields for a given Business Context. The app can extend not only the
    underlying database tables, but also any associated CDS views and
    OData services.

 Extended

 Use predefined Customizing Includes (CI\_\*)

-   These are predefined Include structures present in some standard SAP
    tables, in which custom fields may be added. The fields may be
    defined through customizing (hence the name), for example in Finance
    the CI\_COBL 'coding block' structure. It may also be possible to
    add fields to the includes directly. All custom field names must be
    in the customer namespace (for example starting '**ZZ**') to avoid
    any clashes with SAP fields which may be added in the future.

 Use an Append Structure

-   Additional fields may be added to standard SAP tables
    modification-free using an Append Structure. These are not
    predefined - they may be added to any table. Fields should again be
    in the customer namespace (see above). Typically, such a change
    would be made along with associated UI and Business Logic
    enhancements. In some cases, SAP have provided 'How to' guides
    describing all the steps required. Append structures may also be
    used to attach search helps or define foreign keys for existing
    standard fields.

 Extension Includes

-   These may be used to add custom fields to an app's OData service, if
    the app cannot be changed through 'Custom Fields and Logic'.
    Technically these are provided as DDIC Includes in standard
    structures, which can be extended using an Append Structure.

 HEC/onPREM

 Direct table modification is not allowed, but regardless should never
 be necessary, as fields can always be added using an Append Structure.

 Data Model Enhancement - Custom CDS Views

![](.//media/image98.jpeg)

 Essential

 Key user extensibility

-   Use 'Custom CDS Views' app. This allows a custom view to be created
    using data from other published views. Quantities/Values may be
    aggregated. Input parameters and filters may be defined.

-   Side-by-side extensibility could mean:

-   Replicating data tables to HANA in the SAP Cloud Platform (for
    example using SLT), and building a CDS view on top of them there. 2.
    Extracting data out to a separate BW system or other data warehouse,
    to build views on it there.

 Extended

 Classic extensibility

-   A CDS view may be defined using the ABAP Development Tools in
    Eclipse. In this case the CDS Data Definition Language is coded
    directly and therefore more sophisticated selection logic may be
    implemented

 Business Logic Enhancement

![](.//media/image99.jpeg)

 Essential

 Key user extensibility

-   Use 'Custom Fields and Logic' app to implement a BAdI, using
    restricted ABAP.

-   Side-by-side extension may be used in combination with 'Custom
    Fields and Logic', to implement more sophisticated logic involving
    an external service. Note that side-by- side extension does not
    provide any additional extension points for standard apps, and any
    extension is still limited by the input and output parameters
    provided in the BAdI interface.

 Extended

-   Use a classic extensibility technique with a stable enhancement
    point, that does not require a modification key. For example - ABAP
    BAdIs (SE18/SE19) - AMDP BAdIs to enhance standard SQL Script
    procedures - SMOD/CMOD enhancements - BTEs (Finance).

-   Use a classic extensibility technique with a stable enhancement
    point, but that requires a modification key. For example - User
    Exits - VOFM routines such as pricing formulas

 HEC/onPrem

-   Implicit enhancements, or enhancement spots. These do not require a
    modification key, but otherwise are much like Modifications. They
    enable customers to change any SAP code at the start or end of any
    coding block. In an upgrade, these would need to be processed in
    SPAU\_ENH - the risk is that the enhancement point may no longer
    exist or may no longer have access to the same data.

-   Modifications In this standard SAP code is directly changed without
    restriction. The customer must first obtain an SSCR Modification
    Key, so each change is registered with SAP. In an upgrade, these
    would need to be processed in SPAU - the risk is that the
    enhancement point may no longer exist or may no longer have access
    to the same data.

 Custom Development-Apps

![](.//media/image100.jpeg)

 Essential

 Key user extensibility

-   Use 'Custom Business Objects' app to implement any custom data model
    required, then generate the maintenance app, and code determination
    and validation logic as required using restricted ABAP.

-   Use 'Custom Business Objects' app as above, and then use the SAP Web
    IDE (available in SAP Cloud Platform, SCP) to further enhance the
    UI.

 Side-by-side extensibility

-   Build the app in the SCP. ABAP is on the roadmap for the SCP, but
    currently business logic must be written in another language such as
    Java. SAP S/4 HANA Cloud SDK may be used to integrate with SAP S/4
    HANA Cloud, Single tenant edition where needed, for example calling
    OData services and BAPIs.

 Extended

-   Classic extensibility using the BOPF framework. This is the same
    application framework underlying the Custom Business Objects app,
    but by working directly in this framework with classic ABAP, it's
    possible that a more sophisticated application may be build.

-   Classic extensibility using the BOL / GenIL, when developing Web UI
    based apps, for example relating to SAP S/4 HANA for Customer
    Management; SAP Solution Manager, SAP ChaRM.

-   Web Dynpro or Floorplan Manager apps without the BOPF. Possible if
    there's some barrier to using BOPF to define the business object.

-   SAPGUI Dynpro Transactions. Generally, this is no longer recommended
    for new applications - it should be possible to use one of the other
    approaches instead.

 Custom Development – Workflow

 Information about the custom development of Workflows:

-   Essential

    -   Key user extensibility

        -   Use the various Manage Workflow apps, relating to
            pre-defined business processes such as purchasing approval.
            These apps support the definition of workflows with multiple
            steps, recipient determination, and preconditions, for
            example based on value.

    -   Side-by-side extensibility

        -   To create an entirely custom workflow process, use the SCP.
            It may be possible to use Business Events raised from SAP
            S/4 HANA as a trigger. Using the SCP, more complex workflow
            processes are possible which could involve multiple systems.

-   Extended

    -   Classic extensibility may still be more suitable than a
         side-by-side approach in two scenarios: 1) You may need more
         sophisticated workflow logic than the Manage Workflow apps
         support. With classic extensibility you may still reuse a
         standard workflow template as a starting point. 2) It may be
         that a suitable standard workflow exists already for the
         required business process, and could be adapted, but is not
         yet supported in the SAP Fiori apps.

 <img src=".//media/image101.jpeg" style="width:4.55in;height:3.04281in" /Output-Print
 Forms and Emails

![](.//media/image2.png)

 Essential

 Key user extensibility

-   Use Maintain Form Templates app in combination with Adobe LiveCycle
    Designer. Data is supplied through an OData service, separate forms
    exist for the document headers/footers, and for the body content.
    LiveCycle Designer is a fully featured, form design tool. For more
    complex form logic some scripting may be needed, which could be
    JavaScript.

-   Use Maintain Email Templates App. Create the required email template
    based on one pre delivered by SAP.

 Extended

 Classic extensibility

-   Older print form technologies are also supported in SAP S/4 HANA on
    premise and single tenant edition, including 'classic' Adobe Forms
    (transaction SFP). However, it is recommended to use one consistent
    approach for all print forms, which should be the Maintain Forms
    Template app.

-   Prior to SAP S/4 HANA, there was no single and consistent approach
    to determine email texts. In some cases, it may be possible through
    configuration; in others an enhancement may need to be coded.

 Configuration

 Details about Configuration:

 Table 5: Configuration, Details

<table
<thead
<tr class="header"
<thSub Type</th
<thEssential</th
<thExtended</th
<thHEC/onPrem</th
</tr
</thead
<tbody
<tr class="odd"
<tdPrograms - back- ground jobs</td
<tdClassic extensibility - ABAP These are pro- grams that should be scheduled to run reg- ularly in the back- ground without user intervention, usually to perform some technical activity or long-running update process.</td
<tdInclude all the left</td
<tdInclude all the left</td
</tr
<tr class="even"
<tdPrograms - reports</td
<tdIt's still technically possible, but should no longer be necessa- ry, to write a report in ABAP. Recommend- ed approach is to de- fine a data source us- ing a CDS view, then use one of the SAP S/4 HANA embedded analytics options. For more sophisticated reporting the SAP An- alytics Cloud or BW/ 4HANA could be used.</td
<tdInclude all the left</td
<tdInclude all the left</td
</tr
</tbody
</table

<table
<thead
<tr class="header"
<thSub Type</th
<thEssential</th
<thExtended</th
<thHEC/onPrem</th
</tr
</thead
<tbody
<tr class="odd"
<tdCustom Configura- tion table</td
<td<pClassic extensibility - define the table and generate table main- tenance in the usual way, with the ability to transport the data. The table mainte- nance may be added to the IMG (transac- tion SPRO). Note that in SAP S/4 HANA</p
<pCloud, users do not have access to the IMG.</p</td
<td<pKey user extensibility</p
<p- 'Custom Business Objects' app may be used to define cus- tom tables, however this is designed for master and transac- tional data, not con- figuration. There is no option in this app to make the table con- tents transportable. However, it may be used to create cus- tom tables to hold nontrans portable settings, which per- haps depend on mas- ter data which differs in each environment.</p</td
<tdInclude all the left</td
</tr
<tr class="even"
<tdAdd/Change/Delete standard entries in standard table with no table maintenance</td
<tdNot possible</td
<tdAdd/Change/Delete standard entries in standard table with no table maintenance</td
<tdAdd/Change/Delete standard entries in standard table with no table maintenance</td
</tr
</tbody
</table

 Restricted ABAP

 Information about restricted ABAP:

-   Key user extensibility apps *Custom Fields and Logic*, *Custom
    Business Objects* and *Custom Re-usable Elements* include an in-app
    ABAP editor for coding, for example data validations, substitutions
    or determinations. In this editor only a restricted form of ABAP is
    possible.

-   Supported language features in restricted ABAP are:

    -   Basic expressions, control and flow statements, variables and
        internal tables.

    -   String, math, data & time operations.

    -   Read and write access to the interface of the enhancement
        option.

    -   Read and write access to white-listed SAP APIs (classes).

    -   Read access (full SQL select support) to white-listed SAP CDS
        views.

-   The following ABAP features are not allowed to ensure the
    robustness, security and data consistency target:

    -   Any database operation except selects from released views, for
        example the commit work statement is not allowed

    -   Access to files and other I/O commands.

        -   Creating new tasks (parallel processing).

        -   Dynamic programming.

        -   Code generation.

        -   To simplify the syntax, obsolete ABAP statements are removed
             from the syntax.


-   The complete list of allowed ABAP statements is available in the
    documentation.

 LESSON SUMMARY

 You should now be able to:

-   Realize which extensions, in-App and side-by-side, are available
    depending on the SAP S/ 4HANA versions
