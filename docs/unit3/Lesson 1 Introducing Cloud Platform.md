# Lesson 1: Introducing Cloud Platform
## LESSON OBJECTIVES
---
After completing this lesson, you will be able to:

    -   Introduce the basic components of SAP Cloud Platform

## Basic Components of SAP Cloud Platform
---
In particular, we'll look at the following topics in this lesson:

    -   SAP Cloud Platform in a nutshell.
    
    -   SAP Cloud Platform Cockpit.
    
    -   The Environments
    
    -   Which services are available?
    
    -   SAP CP Reference Architecture.

## SAP Cloud Platform in a nutshell
---
SAP Cloud Platform is an enterprise platform-as-a-service (enterprise PaaS) that provides:

    -   Comprehensive application development services and capabilities.
    
    -   Which lets you build, extend, and integrate business applications in
        the cloud.

 SAP Cloud Platform offers two types of global accounts, Trial accounts
 and enterprise accounts. In the following we will only deal with the
 enterprise accounts.

 
## Cloud Platform Cockpit
---

![](.//media/image2.jpeg)


 On the screenshot you will see the following:

    1.  Region of the global account - here Europe Rot.
    
    2.  Global Account - here KTE\_CP100\_A+B.
    
    3.  Subaccount - here EXT-KYMA-DEMO.
    
    4.  Environment Cloud Foundry with organisation and endpoint - here:
        https:// api.cf.eu20.hana.ondemand.com (Netherlands Europa).
    
    5.  Environment Kyma with name ext-kyma-demo.

##  The Environments
---

 Currently, the following environments are available:

    -   Cloud Foundry ( fully managed by SAP).
    
    -   ABAP ( platform as a Service).
    
    -   Kyma (open Build-on approach).
    
    -   More to come.

### Cloud Foundry

 SAP Cloud Platform Cloud Foundry environment is an open
 Platform-as-a-Service (PaaS) targeted at microservice development and
 orchestration.

 SAP Cloud Foundry should be used if you prefer a Managed Build-on
 approach. Cloud Foundry is fully managed by SAP and you benefit from a
 high level of abstraction from the underlying infrastructure.

 You don't have to deal with technical aspects such as virtual
 machines, networking, monitoring, and more. It provides out-ofthe-box
 integration into all mandatory kernel services.

 Cloud Foundry runs on Kubernates (K8s)

### ABAP

 The ABAP environment is a platform as a service that allows you to
 extend existing ABAP-based applications and develop ABAP cloud apps
 decoupled from the digital core. You can leverage your ABAP know-how
 in the cloud and reuse existing ABAP assets by writing your source
 code with ABAP Development Tools for Eclipse.

### Kyma

 The Kyma environment ( Isteio with K8s) allows you to extend existing
 SAP systems with your own Functions or microservices.

 Kyma is a platform for extending applications with serverless
 functions and microservices. It provides a selection of cloud-native
 projects glued together to simplify the creation and management of
 extensions.

 Kyma should be used for an Open Build-on approach. It provides you
 with more flexibility by using containers and Kubernetes, to build
 cloud native applications. By using Kubernetes, it will be easier to
 develop a solution that is highly scalable.

 
## Which services are available?
---
![](.//media/image4.jpeg)

 All services currently available can be found at
 https://discovery-center.cloud.sap/viewServices. There
 they are listed in the derivative of the regions, commercial models
 and more.

 Not all Services are available at KYMA environment.

## SAP Cloud Platform Reference Architecture
---
 So that you get an approximate overview of what the SAP Cloud Platform
 is from a technical point of view.

 ![](.//media/image6.jpeg)

#### Explanations:

    1.  The PaaS Layer provides all functionality, applications and services
        we can use direct or indirect. It runs on K8s.
    
    2.  The Virtualisation Layer.
    
    3.  Hardware and Infrastructure (IaaS).

 #### Get more in Detail:

 SAP sets the following priorities:

    -   Security
    
    -   Availability
    
    -   Operational Efficiency
    
    -   Performance
    
    -   Development Efficiency

### Security

 Customers, especially in managed cloud services scenarios, expect
 maximum security and data protection compliance when moving their
 business processes to the Cloud. SAP CP architectures are and should
 be built in a way that SAP's Product Standard Security is fulfilled.

### Availability

 Customers also expect an "always-on" behavior for Cloud services.
 Therefore, SAP CP targets a 99,9% availability

### Operational Efficiency

 Optimizing operations isn't just about cost optimization, but about
 empowering people to safely operate complex distributed systems

 Performance

 All SAP CP services and solutions should define relevant performance
 KPIs, and constantly measure them, optimize them and keep them equal
 or better than the target values.

### Development Efficiency

 Hyperscalers do not list development efficiency as a quality, but for
 SAP CP it is an important topic.

## LESSON SUMMARY
---
 You should now be able to:

-   Introduce the basic components of SAP Cloud Platform

 
 