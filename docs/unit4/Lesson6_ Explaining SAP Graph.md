# Lesson 6:  Explaining SAP Graph
##  LESSON OBJECTIVES
 
  After completing this lesson, you will be able to:

    -   Explain the use of SAP Graph

## SAP Graph

  In particular, we'll look at the following topics in this lesson

    -   What can I do with it?
    
    -   How does it work?

##  What can I do with it? What is SAP Graph?

    -   SAP Graph is the easy-to-use API for the data of the Intelligent
        Enterprise from SAP.
    
    -   It provides an intuitive programming model that you can use to
        easily build newextensions and applications using SAP data.
    
    -   SAP Graph wraps the APIs of existing products into a single
        harmonized API layer across the existing source systems.
    
    -   This allows you to easily build applications and extensions for the
        SAP Intelligent Enterprise. SAP Graph is based on OData.

  SAP Graph technology is initially used in the four main processes of
  the intelligent enterprise.
 
  SAP Graph focuses on the Lead-to-Cash (specifically on the SAP S/4HANA
  and SAP C/ 4HANA components and their products), Source-to-Pay and
  Recruit to Retire processes. Other processes and corresponding object
  types will be added in the future.

![SAP Graph Overview](.//media/image43.jpeg)

  In this figure you can see that different professional domains, quota,
  product and order are summarized in one API.
 
##  How does it work ?- What do I do for it?
 
  A graph describes a structure of nodes connected by edges, which we
  use to represent any kind of more or less complex networks. Some
  examples of graphs are computer networks with machines as nodes and
  network links as edges, social networks with users as nodes, and
  social relationships as edges. Graphs are helpful to visualise
  relationships as a formal representation of complex networks.
 
###  SAP Graph schema
 
  In the Intelligent Enterprise we consider business entities, such as
  sales quotes, products, materials, workforce persons, skills, or cost
  centers, as nodes.
 
  You can follow the edges between the nodes as links. Edges in the SAP
  Graph schema have a direction which makes them directed edges, other
  types of graphs, like road networks, often have undirected edges.
 
  The directed edges in SAP Graph point from one node to another node,
  creating links (connections) between them. The links between the
  directed edges are labelled. However, the labels are often the same as
  the destination.

![Example Schema: CustomerQuotes → salesOrganization](.//media/image44.jpeg)

  The *CustomerQuotes* is a node connected to *salesOrganization* nodes
  by the link with
 
  the *salesOrganization* label. The SAP Graph API helps you explore
  these types of relationships by exposing the business entities as
  resources in its API.
 
##  LESSON SUMMARY
 
  You should now be able to:

