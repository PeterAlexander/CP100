# Lesson 10 Explaining Open Connectors

##  LESSON OBJECTIVES
 
  After completing this lesson, you will be able to:

    -   Explain the use of Open Connectors

## Open Connectors

  In particular, we'll look at the following topics in this lesson:

    -   What can I do with it
    
    -   Use Cases
    
    -   Main Features
    
    -   Connectors
    
    -   How does it work ?- What do I do for it?

##  What can I do with it
 
  Our platform - combined with our unique Connectors ( more then 160) -
  is designed to unify the developer experience across all kinds of
  applications and services. Regardless of the application's backend -
  REST, SOAP, Proprietary SDK, Database, etc - SAP Cloud Platform Open
  Connectors creates a unified API layer and standards-based
  implementation across every environment. This ensures that developers,
  integration users, and their use cases are decoupled from the backend
  services on which they rely.
 
## Use Cases
 ![Use Case 1](.//media/image104.jpeg)

  We are using SAP Cloud Platform Open Connectors to access data from
  non-SAP application using harmonized APIs from CRM Hubs. This
  harmonized APIs would be managed by SAP Cloud Platform API Management
  where all the security best practices and governance policies would be
  applied. Finally we will be building a Fiori application to display
  this harmonized data from any of the non-SAP CRM applications of your
  choice. A high level solution blue-print of this sample application is
  captured in the below figure.

![Use Case 2: Create a New Post in LinkedIn by Sending the Message from POSTMAN](.//media/image105.jpeg)

  Open Connectors is connected to the Linkedin Connector. The provided
  harmonised API is used via Cloud Integration to send a message to
  LinkedIn.
 
##  Main Features are:

    -   Use our prebuild connectors in your integration scenarios.
    
    -   Design and implement complex integration workflow templates.
    
    -   Define your own resource and create mappings to your cloud apps.
    
    -   Extend a connector or build your own.
    
    -   Querying using the Open Connectors Query Language.
    
    -   Use the SAP Cloud Platform Open Connectors bulk services to upload
        and download data in bulk from an endpoint in a normalized way.
    
    -   Configure security settings and set up your users and accounts.
    
    -   Use the SAP Cloud Platform Open Connectors events framework to
          receive notifications about changes to resources.
    
    -   Use OAuth Proxy to have multiple environments, such as development,
          QA, etc, with one endpoint application.

##  Connectors
 
  Connectors are pre-built API integration that enables a connection
  into a specific API Provider endpoint (for example: Salesforce,
  Quickbooks, or Marketo). All connectors start with a normalized set of
  features, including authentication, resources, paging, errors, events
  and search. At the hub level, we also seek to support the richer set
  of APIs that an application provides, even when not all the connectors
  in that category share that resource. For example, Salesforce Sales
  Cloud has APIs that many other CRM services do not support. You can
  find these APIs that are specific to just Salesforce in the
  documentation for that connector.
 
  Further facts:

    -   Connectors share common services including discovery, search query,
        pagination, bulk uploading and downloading, logging, and interactive
        documentation.
    
    -   Methods are normalized and accessible through RESTful APIs.
    
    -   Complete data payloads are returned in JSON and available to
        transform and normalize to a common resource.
    
    -   SAP keeps each connector up-to-date with changes at the endpoint.
    
    -   Each connector is a multi-tenant connector supporting an unlimited
        number of authenticated accounts with no additional code required.

##  How does it work ?- What do I do for it?
 
###  Sample :
 
  Simplify connectivity to third-party document storage application from
  SAP Cloud Platform Open Connectors.

### 1.  Log in to open Connectors

![](.//media/image106.jpeg)

### 1.  Click on the *Connectors* tab to view all the available pre-built,feature rich connectors.

![](.//media/image107.jpeg)

### 1.  Choose Dropbox

![](.//media/image108.jpeg)

###  Step 4

-   Hover over the Dropbox connector and select the option Authenticate
    to connect to your own Dropbox tenant.

-   You would be navigated to the Create Authenticated Connector page,
    enter a name for your authenticated connector say mydropbox and
    click on the *Create Instance* button

![](.//media/image109.jpeg)

###  Step 5
 
  After the authenticated connection to your third-party application has
  been created successfully you would be able to test out the connection
  from SAP Cloud Platform Open Connectors. To try out the RESTFul APIs
  for the specific third-party application, click on the option *Test*
  in the API Docs.
 
  ![](.//media/image110.jpeg)
 
##  LESSON SUMMARY
 
  You should now be able to:

-   Explain the use of Open Connectors
