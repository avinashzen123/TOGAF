# 42. Architecture Compliance
> Ensuring the compliance of individual projects with the Enterprise Architecture is an essential aspect of Architecture Governance

Enterprise will normally define two complementary process
- The architecture function : will be required to prepare a series of Project architecture ie. project specific view of EA that will illustrate how EA impacts the major projects within the Organization (ADM Phase A to F)
- The IT Governance : Function will define forma architecture compliance review process for reviewing the compliance of projects to the EA.

**Terminology : The meaning of architecture compliance**
- Irrelevant :  Implementation has not features in common with architecture specification

- Consistent : Implementation has some feature in common with architecture specification, and those common features are implemented in accordance with specification. however some features in architecture specification are not implemented and implementation has other features that are not covered in the specification.

- Compliant : Some features in architecutre specification are not implemented but all features implemented are covered by the specificaion and in accourdance with it.

- Conformant : All features in the architecture specification are implemented in accourdance with specification but some feature are implemented that are not in accordance with it.

- Fully Conformant : There are full correspondence between architecture specification nad implementation. All specified featurs are implemented in accourdance with the specification and there are no featurs implemented that not covered by the specification.

- Non Conformant : Any of the above in which some featuers in teh architecture specification are implemeted not in accordance with the specification.

<img src="https://pubs.opengroup.org/architecture/togaf9-doc/arch/Figures/48_conformance.png"/>

## Architecture compliance reviews :
An Architecture Compliance review is a scrutiny of the compliance of a specific project against established architectural criteria, spirit, and business objectives. 

**Purpose**
- First and foremost, catch errors in the project architecture early, and thereby reduce the cost and risk of changes required later in the lifecycle 
- Ensure the application of best practices to architecture work
- Provide an overview of the compliance of an architecture to mandated enterprise standards
- Identify where the standards themselves may require modification
- Identify services that are currently application-specific but might be provided as part of the enterprise infrastructure
- Document strategies for collaboration, resource sharing, and other synergies across multiple architecture teams
- Take advantage of advances in technology
- Communicate to management the status of technical readiness of the project
- Identify key criteria for procurement activities (e.g., for inclusion in Commercial Off-The-Shelf (COTS) product RFI/RFP documents)
- Identify and communicate significant architectural gaps to product and service providers

Apart from the generic goals related to quality assurance outlined above, there are additional, more politically-oriented motivations for conducting Architecture Compliance reviews, which may be relevant in particular cases:
- The Architecture Compliance review can be a good way of deciding between architectural alternatives, since the business decision-makers typically involved in the review can guide decisions in terms of what is best for the business, as opposed to what is technically more pleasing or elegant
- The output of the Architecture Compliance review is one of the few measurable deliverables to the CIO to assist in decision-making
- Architecture reviews can serve as a way for the architecture organization to engage with development projects that might otherwise proceed without involvement of the architecture function
- Architecture reviews can demonstrate rapid and positive support to the enterprise business community: 
    * The Enterprise Architecture and Architecture Compliance helps ensure the alignment of IT projects with business objectives
    * Architects can sometimes be regarded as being deep into technical infrastructure and far removed from the core business
    * Since an Architecture Compliance review tends to look primarily at the critical risk areas of a system, it often highlights the main risks for system owners


**Timing** : Timing of compliance activities should be considered with regard to the development of the architectures themselves.