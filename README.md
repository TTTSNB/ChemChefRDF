#ChemChefRDF

*Currently Under Development; Pardon Our Dust*


## WHAT IS ChemChefRDF?

**ChemChefRDF** (CCRDF) is a suite of open-source resources, interconnected workflows, and tutorials, which jointly enable its users to:

+ **DISCOVER REACTION "RECIPES"** using either provided query patterns or prototype recipes that we'll teach you to construct.

+ **IDENTIFY MISSING INGREDIENTS** with query outputs providing an enumeration of all listed recipe components (i.e., input and setup items) and indications of components that may be: (a) missing from YOUR lab, (b) missing but realizable with what YOUR lab has on-hand, or (c) both missing and unrealizable.

+ **SHARE RECIPES and PROTOTYPES** with colleagues and journals, in a number of formats. 


## WHY SHOULD I USE ChemChefRDF?

+ **DESIGNED WITH NON-CODERS IN MIND**: Our workflows offer low-code/no-code solutions and our tutorials are written for a general, scientific audience.

+ **BASIC SEMANTIC WEB TUTORIAL**: CCRDF users will become familiar, almost as if by osmosis, with World Wide Web Consortium (W3C) Semantic Web Protocols (RDF, RDFS, OWL2, SPARQL, SHACL, R2RML), as well as Basic Formal Ontology (BFO) methodology, which opens up a brave new world of semantic representation use cases.

+ **ONE-STOP SOLUTION SHOP**: All CCRDF resources are available here on the ChemChefRDF GitHub page, open-source, organized by solution, and accompanied by step-by-step instructions for realizing each of the outcomes listed above (as well as suggestions for any pre-requisite, or pre-supposed, tutorials).


## RESOURCES:

**THE ChemChefRDF ONTOLOGY (CCRDFO)**
  - A well-defined, **upper-level ontology** designed to be expanded by users in accordance with their desires and needs
  - Offers an expanded, semantic model of the schema used by the **Open Reaction Database** (ORD)
  - Built upon the **Basic Formal Ontology (BFO)**, and compliant with **Open Biological and Biomedical Ontology Foundry** (OBO) principles, which allows users to semantically link to any concept contained within the Name Reaction Ontology (RXNO), the Molecule Process Ontology (MOP), the Chemical Methods Ontology (CHMO), the Allotrope Foundation Ontology (AFO), and more...
  - Intended to maximize **FAIR (Findable. Accessible. Interoperable. Reusable)** data principles

**A MAPPING FILE (CC2ORD)**
  - A file containing bi-directional, machine-readable mappings between CCRDFO entities (i.e., classes and properties) and the concepts comprising the ORD's data schema
  - Allows users to populate a graph database containing a semantic model of their lab (i.e., an augmented instance of the CCRDFO) with the contents of the ORD, in their totality 
  - Provides users not interested in hosting the ORD dataset locally with the option to expose the ORD as a virtual (i.e., queryable) SPARQL endpoint.
  - Available at launch as an OBDA file, with plans to offer the mappings as an expanded R2RML file (if demand useful)

**A COLLECTION OF WORKFLOW TUTORIALS**
  - *Introductory tutorials* with step-by-step instructions for installing, configuring, and operating GraphDB and Protégé, the open-source (READ: free), third-party applications necessary to run the workflows described in the following tutorials
  - A step-by-step *"recipe" discovery guide*, which includes: (a) examples and explanations of basic query patterns, (b) demonstrations for extending these patterns, (c) instructions for building a custom "recipe prototype", and (d) an example where a "recipe prototype" is used in a query
  - A step-by-step *"recipe" validation guide*, which includes: (a) a tutorial for using Protégé to capture meta data concerning relevant aspects of your lab and produce a CCRDFO+ instance, (b) instructions for populating your CCRDFO+ instance with the relevant data, and (3) a detailed example describing the process of importing and validating a "recipe" from the ORD against our populated CCRDFO+ instance  
  - A step-by-step *"recipe" exchange guide*, which includes: (a) instructions for sharing "recipes" and "recipe prototypes" with other CCRDF users, (b) instructions for sharing "recipes" and "recipe prototypes" with non-CCRDF users, and (c) instructions for semantically linking concepts contained in your CCRDFO+ instance to other ontologies   


## HOW DO I USE ChemChefRDF?
New users may choose between pursuing a special or general path through CCRDF's suite of workflow tutorials.
Users who choose a **Special Path** will work through a curated set of tutorials containing all and only the information necessary to implement a particular solution. 
Alternatively, users who choose to follow the **General Path** will work though the total library in a building logical progression as solutions are introduced in roughly the order they were designed.

Users interested in using CCRDF to quickly implement a particular solution are encouraged to pursue the special path corresponding to that solution. If this describes you, then your journey will continue in the file marked, "Special Path Files".
Users interested in using CCRDF to to its fullest potential and discovering new solutions and workflows not covered in any tutorial are encouraged the general path.
If this is a better description of your disposition, then your journey will continue in the file marked, "General Path Files".


However you decide to use CCRDF: we thank you for your patronage and ask only that you share the resources we have provided with your friends and colleagues, if it should be of any help to you. 


*Ad unitatem scientiae*

