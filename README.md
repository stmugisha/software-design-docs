# software-design-docs [work in progress...]

**Generic templates** for the different types of Software Design Documents.

The structure for each of the template documents will most definitely vary due to;
* differences in requirements for different software projects.
* varying design practices across companies & industries.

## Types of software design documents:

* [Concept Paper]("./concept_paper.md")
  
  * Briefly introduces and describes a problem, proposes a solution(s) and provides justification for the software solution(s). The concept paper is a deliverable at the end of an ideation (idea conceptualization) phase and is typically 1-2 pages long.
  * This helps provide some context for team leads/managers to escalate further up the hierarchy for approval & resource allocation if they see a value proposition (to the company) in what's described in the concept paper.
    
* [Software Requirements Specification (SRS)]("./software_requirements_specification.md")

  * A software requirements specification document describes in detail the functionality of the proposed software system.i.e It details what the software system will do and how it will do it. 

  * The contents of this document are modeled around the business needs that a system must fulfill and is often a deliverable at the end of a software requirements gathering phase.
  
* [Software Design Document (SDD)]("./software_design_document.md")

  * A software design document provides a detailed description of the system architecture and plan for developing a software system along with justification for the usage or omission of certain elements throughout the design process.
  * Software systems are implemented basing on this document. The design document is a deliverable at the end of an analysis and design phase.


## Notes

* The processes followed to get to the SRS and SDD deliverables can be iterative (can be repeated multiple times) as a better understanding of the requirements for a system are developed by the stakeholders involved. Each iteration yields a refined SRS and/or SDD.

* Whether to have all or some of these documents depends on the design & engineering practices at a particular company and the scope of software to be developed. In some companies a `Software Design Document (SDD)` is sufficient most of the times for work that involves modifying existing software: thus the `SDD` ends up containing details such as functional and non-functional requirements that would have otherwise been put in the `SRS`.
