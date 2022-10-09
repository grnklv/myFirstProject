.. myFirstProject documentation master file, created by
   sphinx-quickstart on Sat Oct  8 18:16:43 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. toctree::
   :maxdepth: 2

==================
Naming conventions
==================

In order to increase the traceability and transparency of the data in Enovia naming conventions shall be used for the different types of objects. Each name of an object shall include a prefix and a name/number. In the next sections the main objects naming conventions will be described.

.. note:: For objects serving specific purpose a product name, project number, milestone a postfix can be added. 
  Example: **"Prefix_Name/Number_Milestone_Postfix"**

Documents, tasks and routes
===========================

There will be no document grouping therefore it is highly recommended a naming conventions to be followed. Since there is relation between documents, tasks and routes the conventions regarding their naming will be described in this chapter. This relation is shown on Figure 1 below.

.. figure:: \images\audi.jpg
   :align: center
   :width: 50%
   :alt: tasks-routes-documents-relation
    
   Figure 1: The relation between documents, tasks and routes

- Documents

  - Project documents - "MLX<product name/project number>_<document subject>"
    
    Example: **MLX12345_Gross Profit Margin**

  - Product/Sub-process (Part) documents - "<development sub-process/process>_<document subject>"
    
    Examples: **ANA_Design Specification, DQA_Reviews Report, EMC_Dashboard, TS_HW Status, PROC_Process Development Checklist, TS_Test Specification, WPP_Technical Requirenments, CHAR_Verification and Integration Plan etc..**

- Tasks

  - Tasks naming - "<development sub-process>-<document name>"
    
    Examples: **MLX-Gross Profit Margin (GPM), TS-Test Specification, SYS-System FMEA etc..** More exampes are shown on Figure 2 below.

 .. figure:: /images/Examplefortasksnaming.jpg
   :align: center
   :width: 50%
   :alt: example-for-tasks-naming

   Figure 2: Example for task naming

- Routes

  - Routes - "<development sub-process/process>_<DocName>_<Milestone>_RT"
    
    Example: **RA_Test request_CD_RT** (For more examples - check Figure 1)

Model Definition
================

- As a title of the Model Version - "MLX<product name>"
- As a revision of the Model Version - "<1 character A->Z>"

 Example for title: **MLX12345**
 Example for revision: **A**

.. note:: In case of exeptions like |MPW| different funcionality is used called "Branching". Naming convention for |MPW| branches is described below.
- Multi-project wafer - "MPW.<number 1->99>"

  Example: **MPW.1**

- Product configurations
 - For Product configurations the order code shall be used.

Physical products (EBOM Items) naming convention
================================================

- Top level Engineering Item - "EI-MLX<product name>"
 Example: **EI-MLX12345**

- Integrated Circuit - "IC-<product number>-<version>"
 Example: **IC-12345_ABC**

- Analog part - "ANA-<product name>_<version (XX - letters)>"
 Example: **ANA-12345_AB**

- Software part - The already defined gitlab naming convention should be used!

- Digital part - The already defined gitlab naming convention should be used!


- Package - "PCK-<Melexis package name>
 Example: **PCK-DFN_WF12/4x4 GR**

- Leadframe - "LF-<leadframe material name>"
 Example: **LF-EFTEC-64T Roughened**

- Mold Compound - "MC-<mold compound material>"
 Example: **MC-EME-G700LTD**

- Die Attach - "DA-<die attach material>"
 Example: **DA-Ablestik C990 333**

- Bond Wire - "BW-<bond wire material>"
 Example: **BW-Pd doped Au**

- Capacitor - "CAP-<capacitor name as in IMDS>"
 Example: **CAP-CGA3E3X7R1H224K080AB"**

- Integrated Magnetic Concentrator - "IMC-<Clover/Disk>"
 Examples: **IMC-Clover**, **IMC-Disk**;

- Micro-electromechanical systems - "MEMS-<device name>-<version>"
 Example: **MEMS-90004-CA**

Libraries and classes
=====================

- Libraries - "<development sub-process (part) abrevisation>-Library"
 Examples: **IC-Library, PCK-Library, WaferProcMod-Library, DA-Library;**

- Classes - the classes naming depends on the Library


Project decisions
=================

In this section will be described the project decisions naming convention.
