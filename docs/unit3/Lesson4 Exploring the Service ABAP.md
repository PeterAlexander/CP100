# Lesson4: Exploring the Service: ABAP

## LESSON OBJECTIVES
---
 After completing this lesson, you will be able to:

    -   Explore the most important components of the ABAP installation

## ABAP Service
---
 In particular, we'll look at the following topics in this lesson:

    -   Introduction
    
    -   The main building blocks of ABAP in the Cloud.
    
    -   How are the look and feel.
    
    -   Step by step Sample.

### Introduction ABAP in the cloud:

    -   Is a Platform as a Service (PaaS) offering for ABAP.
    
    -   Develop ABAP cloud apps decoupled from the digital core Leverage
        your ABAP know how in the cloud Reuse your existing ABAP assets.
    
    -   Benefit from newest ABAP Programming Model Exploit SAP HANA
        capabilities Consume SAP Cloud Platform services.

 ### Facts about ABAP in the cloud

 The ABAP Platform provides the technology layer for several SaaS
 applications like S/4HANA Cloud and Integrated Business Planning as
 well as for on-premise solutions like S/4HANA.

 Furthermore, the ABAP Platform is also used as the key pillar of SAP's
 Platform as a Service offering for ABAP which has the product name SAP
 Cloud Platform, ABAP environment.

 Using the same code line for these different flavors enables customers
 and partners to use the same powerful toolset (ABAP Development Tools
 in Eclipse) and the same ABAP RESTful Programming Model (RAP) for
 cloud and on-premise development.

 There are two main reasons to develop applications and extensions for
 the cloud with ABAP: Existing assets (custom code developed in
 on-premise systems) and developers, experienced in using ABAP. The
 typical extension scenarios built on top of ABAP are:

    -   Cloud ERP: Extend SAP S/4HANA Cloud or other SAP cloud offerings
        with cloud extensions.

    -   Innovation Platform: Develop and run innovative ABAP apps on a PaaS
        ( SAP Cloud Platform) in the Cloud.
    
    -   Hub-like Usage: Integrate multiple cloud & on-premise systems with
        SAP & non-SAP cloud services.

 The ABAP service runs on the Cloud Foundry Environment and must be
 configured there on the desired subaccount.

 ### The main building blocks of ABAP in the Cloud
 Below is the overview of the main building blocks of ABAP in the Cloud.

 ![](.//media/image23.jpeg)

 #### Explanations:

    1.  An ABAP instance runs on SAP CP Cloud Foundry as a Service.
    
    2.  There is a SaaS Application which connect to the Development tools.
    
    3.  You use only a HANA Database with all the advantages of HANA.
    
    4.  You can use all available services on the SAP CP like connectivity
        or IoT.
    
    5.  You can use the cloud connector to connect to back ends.

### How are the look and feel

![](.//media/image24.jpeg)

 ABAP service as a tile in the SAP Cloud Platform.

 ![](.//media/image25.jpeg)

You will see the Web access for ABAP at *Subscriptions*.

### Step by step sample

![](.//media/image26.jpeg)

#### Single Steps:

1.  Create and configure your Cloud Foundry Subaccount on SAP Cloud Platform.
    
    -   Assign the ABAP Service.
    
    -   Assign the SaaS app Web access for ABAP.
    
2.  Instance your ABAP Service with the instance wizzard
    
3.  Download and open an Eclipse for ABAP.

 ![](.//media/image27.jpeg)

4. Connect against your configured subaccount with the ABAP service.

 ![](.//media/image28.jpeg)

1.  Code and run your app.

 ### LESSON SUMMARY

 You should now be able to:

    -   Explore the most important components of the ABAP installation


