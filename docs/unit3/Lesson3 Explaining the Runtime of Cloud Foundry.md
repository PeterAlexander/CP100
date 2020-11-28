# Lesson3: Explaining the Runtime of Cloud Foundry
 ## LESSON OBJECTIVES
---
 After completing this lesson, you will be able to:

    -   Explain the account model in Cloud Foundry
    
    -   Explain the difference between platform and business users

## Cloud Foundry Account Model
---
 In particular, we'll look at the following topics in this lesson:

    -   SAP Cloud Foundry in a Nutshell
    
    -   Cloud Foundry Account Model
    
    -   Global Account
    
    -   Subaccounts
    
    -   Orgs, and Spaces
    
    -   Directories (Beta) \[Feature Set B\]
    
    -   Custom Properties \[Feature Set B\]
    
    -   User Management
    
    -   Platform Users
    
    -   Business Users

### SAP Cloud Foundry in a Nutshell 
 
#### SAP Cloud Foundry is:

    -   SAP Cloud Foundry should be used if you prefer a Managed Build-on
        approach. Cloud Foundry is fully managed by SAP and you benefit from
        a high level of abstraction from the underlying infrastructure.
    
    -   Cloud Foundry is the industry-standard open source cloud application
         platform for developing and deploying enterprise cloud
         applications.

 You don't have to deal with technical aspects such as virtual
 machines, networking, monitoring, and more. It provides out-ofthe-box
 integration into all mandatory kernel services.

### Cloud Foundry Account Model

 In the following the account model.

 ![](.//media/image11.jpeg)

##### A global account has:

-   0.n Entitlements

-   0-n Regions ( based on the Subaccounts)

-   1-n Members with the role admins On licence Type

##### A subaccount has:

-   0-n Quotas

-   1-n Business Users within the IDP

-   0-n Business Roles

-   One Region

##### Cloud Foundry enviroment has:

-   0-n Spaces

-   0-n Applications

-   0-n Services

### Global Account
#### Facts about the Global Account:

    -   It is the realization of a contract you made with SAP.

    -   Global accounts are region- and environment-independent.
    
    -   Within a global account, you manage all of your subaccounts, which
        in turn are specific to one region.

 ![](.//media/image12.jpeg)

 A global account is used to manage subaccounts, members, entitlements
 and quotas. You receive entitlements and quotas to use platform
 resources per global account and then distribute the entitlements and
 quotas to the subaccount for actual consumption. There are two types
 of global accounts: enterprise accounts (paid) and trial accounts
 (free). The type determines pricing, conditions of use, resources,
 available services, scope of the functionality that you can use, and
 the level of support you can receive.

#### Sample
 In the following a sample of an global account of an real enterprise
 cloud platform

![](.//media/image13.jpeg)

 Here you can see the cockpit of a global account. At the top you can
 see the breadcrumb navigation with the name of the global account. On
 the left side the navigation with the global members and entitlements
 on global level.

### Subaccounts

#### Facts about Subaccounts:

    -   Subaccounts let you structure a global account according to your organization’s and project’s requirements with regard to members, authorizations, and entitlements.

![](.//media/image14.jpeg)

 A global account can contain one or more subaccounts in which you
 deploy applications, use services, and manage your subscriptions.
 Subaccounts in a global account are independent from each other. This
 is important to consider with respect to security, member, management, data management, data migration, integration, and so on, when you plan your landscape and overall architecture.

#### Sample

 In the following a sample of an sub account of an real enterprise
 cloud platform.

![](.//media/image15.jpeg)

 Subaccount with:

    1.  Name
    
    2.  Runtime - here Cloud foundry
    
    3.  Security Admin environment independent
    
    4.  Org Member Cloud Foundry specifically
    
    5.  Apps as Subscriptions
    
    6.  Entitlements and Quotas
### Orgs, and Spaces

![](.//media/image16.jpeg)

 The subaccount and the org have a 1:1 relationship and the same
 navigation level in the cockpit (even though they may have different
 names). You can create spaces within that Cloud Foundry org. Spaces
 let you further break down your account model and use services and
 functions in the Cloud Foundry environment.

#### Sample

 In the following a sample of an org and spaces of an real enterprise
 cloud platform is shown.

 ![](.//media/image17.jpeg)

#### Subaccount with:

    -   Org Name and ID
    
    -   With 9 spaces with deployed Apps

### Directories (Beta) \[Feature Set B\]

![](.//media/image3.png)

 Directories allow you to organize and manage your subaccounts
 according to your technical and business needs.

 A directory can contain one or more subaccounts. It cannot contain
 other directories. Using directories to group subaccounts is optional
 - you can still create subaccounts directly under your global account.

 #### Custom Properties \[Feature Set B\] Use of Custom Properties:

 Table 1: Use of Custom Properties

<table
<thead
<tr class="header"
<thCustom Property (Name)</th
<thProperty Values</th
</tr
</thead
<tbody
<tr class="odd"
<tdLandscape</td
<tdDev, Test, Production</td
</tr
<tr class="even"
<tdDepartment</td
<tdHr, IT, Finance, Sales</td
</tr
<tr class="odd"
<tdCost Center</td
<td<p000001134789, 000002155534, To be de-</p
<pfined</p</td
</tr
<tr class="even"
<tdFlagged for Deletion</td
<td(no values)</td
</tr
<tr class="odd"
<tdImportant</td
<td(no values)</td
</tr
</tbody
</table

 Custom properties allow you to label or tag your directories and
 subaccounts according to your own business and technical needs. This
 makes organizing and filtering your directories and subaccounts easier
 within your global account.

 You create and assign custom properties when you create or edit a
 directory or subaccount. Using custom properties is optional.


## Users in Cloud Foundry
---
 A user account corresponds to a particular user in an identity
 provider, such as the SAP ID service and consists, for example, of an
 SAP user ID (S-user or P-user) and password.

 User accounts enable users to log on to SAP Cloud Platform and access
 subaccounts and use services according to the permissions given to
 them.

 It's important to understand the difference between the 2 types of
 users we are referring to:

    -   platform users
    
    -   and business users.

![](.//media/image19.jpeg)

 Platform users deploy , adminster and create apps and uses services to
 integrate or extend business functionality. Business User use this
 created apps- Both need to authenticate on a central place, for
 example SAP Identity Provider.

### Platform Users

#### Facts about Users in Cloud Foundry:

-   Platform users are usually developers, administrators or operators
    who deploy, administer, and troubleshoot applications and services
    on SAP Cloud Platform.

 They're the users that you give certain permissions for instance at
 global account or subaccount level, either by adding them as members
 with certain permissions or by assigning role collections to them .

 Platform users who were added as members and who have administrative
 permissions can view and/or manage the list of global accounts,
 subaccounts, and Cloud Foundry orgs and spaces that are available to
 them, and access them using the cockpit or the command line interface.

 For platform users, the default identity provider is SAP ID Service,
 but if you want to have subaccount members from your own user base,
 you can use your own identity authentication tenant with SAP Cloud
 Identity Authentication Service.
 
 ### Sample - Authentication of platform users

![](.//media/image20.jpeg)

 Org Members - Platform Users authenticated within the SAP ID Service.

### Sample- Autorisation of platform users

![](.//media/image21.jpeg)

 Configured Platform users with role collections coming from
 applications. Explanations about the numbers:

    1.  The platform-user name.
    
    2.  The platform-user has to authenticated by the SAP ID Service.
    
    3.  The roles collections coming from the SaaS Applications like BAS,
        Integration Suite , IOT and others.

 ### Business Users

 Business users use the applications that are deployed to SAP Cloud
 Platform:

    -   For example, the end users of your deployed application or users of subscribed apps or services, such as SAP Business Application Studio or SAP Web IDE, are business users.

 In the Cloud Foundry environment, application developers (platform
 users) create and deploy application-based security artifacts for
 business users. Administrators use these artifacts to assign roles,
 build role collections, and assign these role collections to business
 users or user groups. In this way, they control the users' permissions
 in the deployed application.

 For business users, the identity provider can be, for example, SAP
 Cloud Identity Authentication Service or your own, such as Active
 Directory.

## LESSON SUMMARY
---
 You should now be able to:

    -   Explain the account model in Cloud Foundry
    
    -   Explain the difference between platform and business users
