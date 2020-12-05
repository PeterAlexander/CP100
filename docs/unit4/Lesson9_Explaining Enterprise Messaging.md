# Lesson 9 Explaining Enterprise Messaging
##  LESSON OBJECTIVES
 
  After completing this lesson, you will be able to:

    -   Explain the features of enterprise messaging

## Enterprise Messaging

  In particular, we'll look at the following topics in this lesson:

    -   What can I do with it
    
    -   Features
    
    -   How does it work ?- What do I do for it?

##  What can I do with it

###  Uses cases:

    -   SAP Cloud Platform Enterprise Messaging is a fully-managed cloud
        service that allows applications to communicate through asynchronous
        events and seamlessly extend your digital core.
    
    -   Create responsive applications that work independently and
        participate in event-driven business processes inside your company
        and across your business ecosystem for greater agility and
        scalability.

##  Features
 
###  The service provides the following key features:

    -   Decouple communication between applications, services, and systems
        using asynchronous messaging patterns.
    
    -   Publish business events Publish business events from SAP and non-SAP
        sources across hybrid landscapes from the digital core to extension
        applications.
    
    -   Build event-driven extensions Subscribe to business events from core
        SAP systems like SAP S/4HANA, SAP SuccessFactors, SAP Concur, and
        SAP Cloud for Customer or third- party sources to enable
        cloud-native extensions to respond to the latest business
        developments.
    
    -   Seamless connectivity Implement extension and integration scenarios
        through decoupled communication between applications, services, and
        systems as part of the SAP Cloud Platform Integration Suite.

##  How does it work ?- What do I do for it?
 
###  Development
 
  Enable your application to:

    -   Connect to a queue or a queue subscription in the enterprise
        messaging service.
    
    -   Send messages to a queue or queue subscription
    
    -   Receive messages from a queue or queue subscription.
    
    -   Develop messaging applications using Java and Node.js and deploy
        them to the service.
    
    -   Look up events from an event source such as SAP S/4HANA.
    
    -   Use REST APIs for messaging.

###    Administration

    -   Create and delete queues.
    
    -   Create and delete queue subscriptions.
    
    -   Generate application confiJurDtLons that facilitate the use of
        protocol agnostic libraries.
    
    -   Check your application confiJurDtLons for missing properties.
    
    -   Create, edit, and delete event channel groups.
    
    -   Use REST APIs to manage queues and queue subscriptions.
    
    -   Create message clients with unique credentials.
    
    -   Provide access rules for each message client.
    
    -   Create a message client with an event catalog.
### Events

![Concept of Events](.//media/image99.jpeg)

  An event notifies a receiving application that an object at the event
  source has changed. An event source is the system or application from
  which the event originates. A receiving application needs to create a
  connection to the event source to facilitate the flow of events. The
  service can receive events from an event source, lookup events, and
  discover events. Different event sources can publish events to the
  service.
 
###  Asynchronous Messaging
 
  Asynchronous messaging facilitates communication between a sending and
  receiving application or system. Messages are sent to a queue where
  they're stored until the receiving
 
  application acknowledges them. The service provides capabilities for
  storing and transmitting messages through queues and queue
  subscriptions.
### Queues
 ![Concept of Queues](.//media/image99.jpeg)
 

  The service enables applications to communicate with each other
  through message queues. A sending application sends a message to a
  specific named queue. There's a one on one correspondence between a
  receiving application and its queue. The message queue retains the
  messages until the receiving application consumes them. You can manage
  these queues using the service.
  
### Queue Subscriptions
 
  ![Concept of Queue Subscriptions](.//media/image99.jpeg)
 
 
  The service enables a sending application to publish messages and
  events to a topic. Topics don't retain messages but, it can be used
  when each message needs to be consumed by a number of receiving
  applications. Topics must be managed through queue subscriptions. In
  queue subscriptions, the service enables a sending application to
  publish messages to a topic that directly sends the message to the
  queue to which it's bound. For example, events from an SAP S/4HANA
  system (event source) can only be sent to a topic. A queue
  subscription ensures that the message is retained until it's consumed
  by the receiving application.
 
###  Message Client
 
  A message client allows you to connect to the service through its
  unique credentials to send and receive messages. The message client
  can run within SAP Cloud Platform or outside it. You can create
  multiple message clients that can be distinguished with a set of
  credentials that consist of a namespace and connection rules. The
  credentials must also define the list of queues or topics to which the
  message client can send and receive messages. The credentials are
  stored in the service descriptor that you define while creating a
  service instance.
 
  ![Concept of Message Client](.//media/image102.jpeg)
 
  The namespace is a unique prefix that defines all the queues or topics
  that have been created in the context of a particular message client.
  When you manage queues or topics in the service, providing the
  namespace allows message clients to identify the queues or topics to
  which communication must be made. The connection rules specify the
  queue or topic to which a message client must publish or consume
  messages.
 
  The default service plan facilitates a connection between different
  message clients in a subaccount through its unique credentials.
  Message clients can communicate with each other using the service.
  Each message client has a set of queues and topics associated with it.
  All these queues and topics belonging to one message client are
  exposed to other message clients through the unique credentials in the
  service descriptor.
 
###  Event Catalog
 
  An event source can have a list of events that can be published or
  consumed by the service. This list of events is known as event
  catalog. The catalog can contain events that are to be published or
  consumed. Each event in a catalog has a payload schema. An event
  source can provide an event catalog end point that gives the list of
  events that are published or consumed by the message client.
  
### Webhooks
 
 ![Concept of Webhooks](.//media/image103.jpeg)
  
  Webhooks allow you to set up an integration to send real-time data
  from one application to another when an event occurs. A webhook
  subscription notifies the receiving application when an event is
  triggered. The data is sent through HTTP POST to the receiving
  application that handles the data. The exchange of data is done
  through a webhook URL. A webhook URL is configured by the receiving
  application. When an event is triggered, an HTTP POST payload is sent
  to the webhook URL. The data sent to the webhook URL is known as
  payload.
 
##  LESSON SUMMARY
 
  You should now be able to:

    -   Explain the features of enterprise messaging
