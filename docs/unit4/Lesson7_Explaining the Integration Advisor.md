# Lesson 7 Explaining the Integration Advisor
##  LESSON OBJECTIVES
 
  After completing this lesson, you will be able to:

    -   Create B2B mappings

## Integration Advisor

  In particular, we'll look at the following topics in this lesson:

    -   Introduction
    
    -   How does it work ?- What do I do for it?
    
    -   Library of Type Systems
    
    -   Sample Scenario
    
    -   Build a MIG (Message implementation guideline) for source and
        target•Mapping Guidelines (MAGs)
    
    -   Mapping Guidelines (MAGs).
    
    -   Use the proposal service.
    
    -   Generate different runtime artefacts.
    
    -   Use the MAG artefacts within your integration Solution.

##  What is Integration Advisor?

    -   SAP Cloud Platform Integration Advisor is a cloud application
    
    -   It uses a crowd-based machine learning approach to help you create
        integration content(Mappings) very easily.
    
    -   This mapping artefacts can be used within the PI or the CPI.

  SAP Cloud Platform Integration Advisor is a cloud application that
  helps you to simplify and streamline the implementation flow of your
  B2B/A2A and B2G integration process. It uses a crowd-based machine
  learning approach to help you create integration content very easily.
  Tests indicate that you can speed up the content creation to
  deployment process by almost 60% using SAP Cloud Platform Integration
  Advisor. You can also manage and share your content, and leverage the
  content shared by other users of the application with similar business
  needs
 
  SAP Cloud Platform Integration Advisor solves the biggest problem that
  you face in B2B/A2A/B2G integration: multiple business partners who
  use different industry standards like UN/EDIFACT, SAP IDoc and ASC
  X12, to name a few. Each new standard will create a need for a new
  interface that facilitates this integration and doing this manually is
  extremely time-consuming.
 
  With IA, you have a library of type systems that you can use a
  starting point, use the messages in this type system library to:

    -   Create a new message implementation guideline (MIG).
    
    -   Create mapping guidelines (MAG) to map the standard you use in your
        business system to that of your business partner's.
    
    -   Generate runtime artifacts (XSLT Mappings) that you can use in
          different integration solutions like SAP Cloud Platform
          Integration and SAP Process Orchestration.

##  How does it work ?- What do I do for it?

![Step by step overview](.//media/image45.jpeg)

  We will examine the individual steps in more detail below.
 
##  Library of Type Systems
 
  The library of type systems is a collection of message templates that
  are provided by agencies that maintain the B2B/A2A/B2G standards. Each
  of the type system is developed and maintained by the agency that owns
  it

![Sample Type System from SAP S/4HANA Cloud OData](.//media/image46.jpeg)

  On the screenshot you can see the Business Partner OData interface.
  Type Systems are:

    -   SAP IDOCS

    -   ASC X12

    -   cXML

    -   ICA Test

    -   ISO

    -   Odette

    -   SAP S/4HANA Cloud OData

    -   SAP S/4HANA Cloud SOAP

    -   SAP S/4HANA On Premise IDoc

    -   UN/CEFACT

    -   UN/EDIFACT

##  Sample Scenario
 A continuous example shows the individual steps
 ![Sample Type System from SAP S/4HANA Cloud OData](.//media/image4/.jpeg)
 
  The source is a Mig OrderRequest based on a SOAP interface. On the
  target side, an ASC x12 Purchase Order interface is created as MIG.
 
  A mapping is then created between the source and the destination. The
  mapping artefacts can then be used e.g. in the CPI.
 
##  Build a MIG (Message implementation guideline) for source and target
 
  Message implementation guideline, also referred to as MIG, is used as
  the source or target in a mapping guideline (MAG) of SAP Cloud
  Platform Integration Advisor. This is created using one of the
  messages in the type system that is relevant to your scenario as the
  template.
 
  The MIG contains all the information for implementing a customized
  message interface. SAP Cloud Platform Integration Advisor uses the
  message in a type system as a starting point to ensure that you do not
  have to refer to any additional documents ti implement the interface.
  By providing a MIG, you ensure that all users who are involved in the
  process of implementing the interface have a clear understanding of
  the guidelines.
 
###  Target MIG ASC X12 MIG - Structure View

![MIG for Target](.//media/image48.jpeg)

  You see the Structure of the target MIG. You can download a
  documentation as .pdf and also .xsd files to use within the cloud
  integration.
 
###  Source MIG OrderRequestOut - Structure view

![MIG for the Source](.//media/image49.jpeg)

  You see the Structure of the source MIG. You can download a
  documentation as p.df and also .xsd files to use within the cloud
  integration
 
##  Mapping Guidelines (MAGs)
 
  A mapping guideline is the runtime artifact that you use in the
  mapping step of an integration application like SAP Cloud Platform
  Integration. This is used as a reference or guidance for implementing
  mapping in the integration application. By providing such an artifact,
  you simplify the mapping task for users who use messages that adhere
  to the A2A/B2B type system standards.
 
  A Mapping Guideline (MAG) is based on a source and a target message
  implementation guideline. It demonstrates how the defined nodes at
  each side are mapped, describing all mapping
  elements in detail with definitions or notes and providing further
  instructions for the transformation, such as functions or code value
  mappings.
  
 ![Mapping Guideline](.//media/image50.jpeg)
  
  In addition to the actual mapping, further steps are carried out in
  the MAG, pre- and post processing, validation and conversion.
 
##  Use the proposal service
 
  All proposals are from a centrally provided and trained knowledge
  graph. The graph is trained by users; once they activate a MAG, their
  updates are anonymously pushed into the graph. A number of diverse
  machine-learning (ML)-based algorithms then calculate the best fit
  proposal according your business context and based on the selected
  source and target structure. The main intention is that all proposals
  are semantically correct, independent of the complexity of the source
  and target structures.
  
### Proposal service in action
  ![Proposal Service](.//media/image50.jpeg)
 
  The result of "Select Best Proposal" is shown in form of mapping lines
  from the source elements to the corresponding target elements
 
  You can now also manually change or delete mapping entities as well as
  create additional ones.
 
  Of course, this only works if the proposal service has been trained
  accordingly beforehand. This works in the background by using manual
  mappings: *Export the runtime artefacts*.
 
##  Generate different runtime artefacts

![Runtime Artefacts](.//media/image52.jpeg)

  Generate different runtime artefacts :

    -   XSLT Mappings for CPI
    
    -   XSLT Mappings for PI
    
    -   Documentation

  In addition to a documentation of the mapping, various runtime
  artefacts ( XSLT) are created. It is even possible to import the XSLT
  mapping directly into an iFlow via Inject. Use the XSLT Mappings
  within your CPI.
 
###  Use the MAG artefacts within your integration Solution
 
 ![IFlow with xslt Mapping Created from Content Advisor](.//media/image53.jpeg)
  
 
##  LESSON SUMMARY
 
  You should now be able to:

    -   Create B2B mappings

 
 