
# Lesson5: Explaining KYMA
## LESSON OBJECTIVES

 After completing this lesson, you will be able to:

    -   Explain, what Kyma is, what components Kyma is made of and what you
        can do with it

## Kyma

 In particular, we'll look at the following topics in this lesson:

    -   Kyma in a Nutshell
    
    -   Main features
    
    -   Key components

## Kyma in a Nutshell:

    -  Kyma is an open-source project designed natively on Kubernetes. It allows you to extend  enterprise applications in a quick and modern way, using serverless computing or microservice architecture.
    -   is avaiaible as a runtime within the SAP Cloud Platform

 Kyma allows you to extend applications with microservices and
 Functions. First, connect your application to a Kubernetes cluster and
 expose the application's API or events securely. Then, implement the
 business logic you require by creating microservices or Functions and
 triggering them to react to particular events or calls to your
 application's API. To limit the time spent on coding, use the built-in
 cloud services from Service Catalog, exposed by open service brokers
 from such cloud providers as GCP, Azure, and AWS.

### Kyma comes equipped with these out-of-the-box functionalities:

    -   Service-to-service communication and proxying (Istio-based Service
        Mesh).
    
    -   Built-in monitoring, tracing, and logging (Grafana, Prometheus,
        Jaeger, Loki, Kiali).
    
    -   Secure authentication and authorization (Dex, Ory, Service Identity,
        TLS, Role Based Access Control).
    
    -   The catalog of services to choose from (Service Catalog, Service
        Brokers.
    
    -   The development platform to run lightweight Functions in a
        cost-efficient and scalable way (Serverless).
    
    -   The endpoint to register Events and APIs of external applications
        (Application Connector).
    
    -   Secure API exposure (API Gateway).
    
    -   The messaging channel to receive Events, enrich them, and trigger
        business flows using Functions or services (Event Mesh, NATS).
    
    -   CLI supported by the intuitive UI (Console).
    
    -   Asset management and storing tool (Rafter, MinIO).
    
    -   Backup of Kyma clusters (Kyma Backup).

## Main features

 Major open-source and cloud-native projects, such as Istio, NATS,
 Serverless, and Prometheus, constitute the cornerstone of Kyma. Its
 uniqueness, however, lies in the "glue" that holds these components
 together. Kyma collects those cutting-edge solutions in one place and
 combines them with the in-house developed features that allow you to
 connect and extend your enterprise applications easily and
 intuitively.

 Kyma allows you to extend and customize the functionality of your
 products in a quick and modern way, using serverless computing or
 microservice architecture.

 The extensions and customizations you create within Kyma are decoupled
 from the core applications, which means that:

    -   Deployments are quick.
    
    -   Scaling is independent from the core applications.
    
    -   The changes you make can be easily reverted without causing downtime
        of the production system.

 Last but not least, Kyma is highly cost-efficient. All Kyma native
 components and the connected open-source tools are written in Go. It
 ensures low memory consumption and reduced maintenance costs compared
 to applications written in other programming languages such as Java.

## Key components

 Kyma is built of numerous components but these three drive it forward:

    -   Application Connector
    
    -   Serverless
    
    -   Service Catalog



### Application Connector:

    -   Simplifies and secures the connection between external systems and
         Kyma
    
    -   Registers external Events and APIs in the Service Catalog and
         simplifies the API usage
    
    -   Provides asynchronous communication with services and Functions
         deployed in Kyma through Events
    
    -   Manages secure access to external systems
    
    -   Provides monitoring and tracing capabilities to facilitate
         operational aspects 
         
### Serverless:

        -   Ensures quick deployments following a Function approach
    
        -   Enables scaling independent of the core applications
    
        -   Gives a possibility to revert changes without causing production
             system downtime
    
        -   Supports the complete asynchronous programming model
    
        -   Offers loose coupling of Event providers and consumers
    
        -   Enables flexible application scalability and availability
            
### Service Catalog

        -   Connects services from external sources
    
        -   Unifies the consumption of internal and external services thanks
             to compliance with the Open Service Broker standard
    
        -   Provides a standardized approach to managing the API consumption
             and access
    
        -   Eases the development effort by providing a catalog of API and
             Event documentation to support automatic client code
             generation

 This basic use case shows how the three components work together in Kyma:

![](.//media/image49.jpeg)

 On the left side is the application, here Wordpress. On the right side
 the available services of the Hyperscaler. In the middle you see the
 principle of the application connector which connects the app to be
 extended with the platform. The serverless runtime which contains the
 code that is extended by various services from the service catalogue.

 ![](.//media/image50.jpeg)

The figure shows how the Kyma runtime is activated at SAP Cloud Platform.

 Within the service catalog in KYMA.

 ![](.//media/image52.jpeg)


## LESSON SUMMARY
---
 You should now be able to:

    -   Explain, what Kyma is, what components Kyma is made of and what you
        can do with it
