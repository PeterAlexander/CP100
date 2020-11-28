## Lesson2:  Explaining the Commercial Model for SAP Cloud Platform

 ## LESSON OBJECTIVES
---
 After completing this lesson, you will be able to:

    -   Explain the Commercial Model of SAP Cloud Platform

## The Commercial model of SAP Cloud Platform
---
 In particular, we'll look at the following topics in this lesson:

    -   The nature of Services
    
    -   Applications
    
    -   SAP Cloud Platform – Choice of Commercial Models
    
    -   Structure of the Commercial Models
    
    -   Consumption-Based Commercial Model - CPEA

 ## The nature of Services
--- 

 Services constitute SAP CP as PaaS offering since major function
 blocks are implemented and exposed as service. Services can be
 accessed and managed via the Service Manager

 Services have a provider and a consumer "view". For service providers
 it's an entity to "ship" functionality, manage the lifecycle and an
 operation unit. Consumers see it as re-use entity, for which an
 entitlement, configuration and access points (API and/or UI) are
 given. The default model for consuming services today is to separate
 service consumption from service provisioning completely. From a
 consumer perspective, this is ideal because the service is "provided
 as a Service" often-times with an SLA.

 ![](.//media/image7.jpeg)

Description of the figure:

-   A service is a Technical Service or a Business Service

-   Backing Services are either abstracted and exposed as Technical
    Service or it is natively consumed without any abstraction except
    the access via Service Manager (e.g. ObjectStore, MS Embrace project
    with OSB implementation)

-   A service can be a Kernel Service

-   A service has a deploy type. Essential services are deployed and
    exposed in all SAP CP data centers or availability zones
    respectively. Required services are deployed with the essential
    services since the essential services depend on them. Additional
    services are deployed on selected data centers or availability zones
    as needed on request. SAP CP offers approximately 70 essential or
    required technical services today, which are deployed on all SAP CP
    data centers and availability zones as defined in the Service
    Availabilitymatrix at the discovery center.

##  Applications
---
 Applications building on or integrating with SAP Cloud Platform can
 use the Service Discovery and Management Kernel Service (22), also
 known as Service Manager, for the provisioning/ deprovisioning of
 service instances listed in the marketplace and creating/accessing/
 updating/deleting credentials for these service instances.

 The actual implementations of these operations are service specific,
 and services implement them in service brokers that they register with
 the Service Manager.

### SAP Cloud Platform - Choice of Commercial Models
Basically, there are two models:

    -   The Subscription model licenses only the services you need.
    
    -   In the Consumption model you can use all services but only pay for
        the use.

 ![](.//media/image8.jpeg)


 ###  Subscription

    -   You plan and pay in advance for every service separately (high
        touch),whether you use it or not.
    
    -   Certain contract duration (three month or more, typical three
        years!).
    
    -   Coarse granularity for capacity (blocks of for example 100 users,
         5.000 visits). 
         
### Consumption-based
    
    -   You get access to all eligible services, without quotas or
        limitations.
    
    -   Self-service activation and de-activation ("low touch").
    
    -   Only pay for what you use. 
    
### Cloud Credits
    
    -   Cloud credits are a pre-paid commitment for the consumption of SAP
        Cloud Services in a defined time period à unused cloud credits
        expire at the end of the phase and contract year.
    
    -   Cloud credits are subject to discount.
    
    -   Purchasing of top-up cloud credits at any point of time.

## Structure of the Commercial Models
---
![](.//media/image9.jpeg)

 As you can see on the slide, the Consumption based Model is much more
 flexible. It offers Elastic services. The picture on the far right
 describes the ability of the model to adapt to load changes. The
 middle picture shows a completely flexible adjustment of the costs to
 the actual usage.

## Consumption-Based Commercial Model - CPEA
---
 CPEA (Cloud Platform Enterprise Agreement) is a Consumption-Based
 Commercial Model for SAP Cloud Platform.

 ### Facts about Consumption-Based Commercial Model - CPEA:

    -   You get access to all eligible services, without quotas or
        limitations.
    
    -   Self-service activation and de-activation (“low touch”)
    
    -   Only pay for what you use.

 #### Go deeper:

 The consumption-based model decouples:

    -   Commercial agreements and
    
    -   Technical adoption

 to help customers easily to:

    -   Find,
    
    -   Try,
    
    -   Buy,
    
    -   Consume and
    
    -   Pay

 ### Facts about Cloud Credits:

    -   Cloud credits are a pre-paid commitment for the consumption of SAP
        Cloud Services in a defined time period à unused cloud credits
        expire at the end of the phase and contract year.
    
    -   Cloud credits are subject to discount.
    
    -   Purchasing of top-up cloud credits at any point of time.



-   Cloud credits entitle you to flexible usage of all consumption-based
    services in the portfolio, as well as future (yet to be introduced)
    services.

-   Service usage is "debited" from the cloud credits.

-   Excess usage ("overage") is invoiced.

### Overview - Price List

 ![](.//media/image10.jpeg)
 Under https://cloudplatform.sap.com/price-lists, you will find the currently valid price site, limited to countries.

 In the upper area you can see the previously selected region and the
 date. A little deeper under the Show Historical Prices tab you can see
 the price changes and many more on this side.


 ##  LESSON SUMMARY
---
 You should now be able to:

    -   Explain the Commercial Model of SAP Cloud Platform

 