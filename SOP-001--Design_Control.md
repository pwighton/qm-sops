
# __NewCorp__ Quality Manual
## Design Control Procedure
## SOP-001
-----------------------------------------------------------------------

## 1.0 PURPOSE

This Standard Operating Procedure (SOP) provides *minimum*
requirements (requirements are expressed using the word **shall**)
for the design and development of software-only medical devices by
__NewCorp__.

Design controls address the medical device product development
process. The purpose of this SOP is to facilitate the development of
safe and effective medical devices that conform to applicable FDA
regulations, guidance documents and international standards, as well
as meet intended use and the needs of patients and clinicians.

## 2.0 SCOPE

This SOP applies to the design and development of new software-only
medical devices by __NewCorp__ or by third parties working under
the direction of __NewCorp__. This SOP also applies to
modifications made to existing software-only medical devices
previously developed by __NewCorp__.

This SOP does not apply to "off the shelf" products or components
where __NewCorp__ has no influence over the design process. This
SOP does not apply to research activities.

## 3.0 REFERENCES, TERMS AND ACRONYMS

### 3.1 Regulatory References
-------------------------

1.  21 CFR Part 820 FDA Quality System Regulation, 1996

2.  21 CFR Part 11 Electronic Records and Electronic Signatures, 1997

3.  ANSI/AAMI/ISO-13485:2003 Medical Devices-Quality Management Systems
    Requirements for Regulatory Purposes

4.  ANSI/AAMI/ISO-14971:2007 Medical Devices – Application of Risk
    Management for Medical Devices.

5.  ISO/IEC 62366-1:2015 Medical Devices – Part 1: Application of
    Usability Engineering to Medical Devices

6.  Guidance for the Content of Premarket Submissions for Software
    Contained in Medical Devices, May 11, 2005

7.  Guidance for Off-the-Shelf Software Use in Medical Devices,
    September 9, 1999

8.  General Principles of Software Validation, FDA, Final Guidance,
    January 2002

9.  Content of Premarket Submissions for Management of Cybersecurity in
    Medical Devices, October 2, 2014

10. Postmarket Management of Cybersecurity in Medical Devices – DRAFT
    2016

11. Applying Human Factors and Usability Engineering to Medical Devices,
    2016

### 3.2 __NewCorp__ References 
------------------------------

1.  Quality Manual, [QM-001](QualityManual.md)

2.  Design Review Procedure, [SOP-007](SOP-007--Design_Review.md)

3.  Document and Record Control Procedure, [SOP-008](SOP-008--Document_and_Record_Control.md)

4.  Risk Management Procedure, [SOP-006](SOP-006--Risk_Management.md)

5.  Software Development Procedure, [SOP-012](SOP-012--Software_Development.md)

6.  Complaint Handling and Medical Device Reporting, [SOP-004](SOP-004--Complaint_Handling_and_MDR.md)

7.  Installation and Maintenance Controls Procedure, [SOP-010](SOP-010--Installation_and_Service_Controls.md)

8.  Supplier and Purchasing Controls Procedure, [SOP-002](SOP-002--Supplier_and_Purchasing_Controls.md)

### 3.3 Terms
---------

- **Bill of Materials**: The BOM is a list of all parts that constitute the
finished medical device.

- **Defect**: Any condition that deviates from the expected based on
requirements specifications, design documents, standards, etc. or from
someone’s perceptions or experiences. Defects may be found during, but
not limited to, the review, test, analysis, compilation, or use of
software products or applicable documentation. The terms defect,
anomaly, failure and bug are often used interchangeably.

- **Design History**: File The DHF contains or references the documentation
necessary to demonstrate that the design was developed in accordance
with the approved design plan and associated procedures.

- **Design Input**: The design input represents the requirements for the
medical device and reflect intended use and the needs of the user and
patient.

- **Device Master Record**: The DMR is a compilation of records containing the
procedures and specifications for a finished device.

- **Design Output**: The design output represents the result of translating the
system and software requirements of the medical device into a design
that addresses these requirements.

- **Design Review**: The design review provides a systematic assessment of
design results, including the device design and the associated designs
for production and support processes; provides feedback to designers on
existing or potential problems; assesses project technical progress; and
provides confirmation that the project is ready to move on to the next
stage of development.

- **Design Transfer**: Design transfer ensures that the finished medical device
design is properly transferred from the design environment to a released
environment for subsequent distribution and installation for use at
clinical sites.

- **Intended Use**: Use for which a product, process or service is intended
according to the specifications, instructions, and information provided
by the manufacturer. ```[ISO 14971:2007]```

- **Risk**: The combination of the probability of occurrence of harm and the
severity of that harm. ```[ISO 14971:2007]```

- **Traceability**: The ability to identify different types of requirements at
different levels of abstraction and to show that they have been
implemented and tested. Traceability is often expressed as a matrix or
presented in a table format. The most common example of traceability is
a Requirements Traceability Matrix (RTM). An RTM shows relationships
between requirements, implementation and test cases. It may also be used
to show risk mitigations.

- **Validation**: Validation is confirmation by examination and provision of
objective evidence that the particular requirements for a specific
intended use can be consistently fulfilled. ```[GPSV]```

- **Software Validation**: Confirmation by examination and provision of
objective evidence that all software specifications conform to user
needs and intended uses, and that the particular requirements
implemented through software can be consistently fulfilled. ```[GPSV]```

- **Verification**: Verification means confirmation by examination and
provision of objective evidence that specified requirements have been
fulfilled. ```[21 CFR Part 820.3(aa)]```

- **Software Verification**: Provides objective evidence that the design
outputs of a particular phase of the software development lifecycle meet
all of the specified requirements for that phase. ```[GPSV]```

3.3 Acronyms
------------

- **BOM**: Bill of Materials

- **DHF**: Design History File

- **DMR**: Device Master Record

- **IFU**: Indications for Use

- **IRB**: Institutional Review Board

- **NA**: Not applicable

- **OTS**: Off the shelf

- **PRS**: Product Requirements Specification

- **QM**: Quality Manual

- **QMS**: Quality Management System

- **QSR**: Quality System Regulation (21 CFR Part 820)

- **RMF**: Risk Management File

- **RTM**: Requirements Trace Matrix

- **SDD**: Software Design Description

- **SOP**: Standard Operating Procedure

- **SRS**: Software Requirements Specification

- **TBD**: To be determined

- **WI**: Work Instruction

  
## 4.0 PRODUCT DESIGN AND DEVELOPMENT PROCESS 

### 4.1 Overview 
-------------

The product development process results in translating documented
clinical (user) requirements and patient needs into a medical device
that meets the stated intended use. This is accomplished by applying
accepted product design and development practices and providing
adequate supporting documentation for software development,
requirements traceability, project communication, design reviews,
verification, validation, risk management, and applicable regulatory
compliance.

__NewCorp__ develops software-only medical devices. The software
development process is shown in the Software Development Procedure
[SOP-012](SOP-012--Software_Development.md). This Design Control Procedure
includes activities that are in addition to those contained in the Software
Development Procedure [SOP-012](SOP-012--Software_Development.md) and that are
required for compliance with applicable FDA Design Control activities defined
in the QSR (21 CFR Part 820.30).

### 4.2 Project Planning 
---------------------

Project planning is an essential part of the medical device
development process and includes:

-   Initiating new development projects

-   Documenting patient and clinician needs to be met by the medical
    device

-   Creating a statement of intended use for the medical device

-   Determining applicable regulatory requirements based on intended use

-   Creating an initial Project Plan for the design and development work

-   Identifying requirements in applicable guidance documents

-   Planning for deployment, maintenance and support of the medical
    device

Project planning is an on-going activity that continues throughout the
project. As project requirements change, the Project Plan **shall** be
revised accordingly. The Project Manager is responsible for assuring
that product development work complies with this SOP and the Project
Plan.

The **Project Plan** is a mandatory document that **shall** be
prepared for all new medical device development projects as well as
for updates to previously developed medical devices. One purpose of
the Project Plan is to tailor the requirements of this and other SOPs
so that they reflect the needs and constraints of the particular
project. An outline for a typical Project Plan is included in Appendix
A.

Every project **shall** have a **Risk Management Plan** as defined in
the Risk Management [SOP-006](SOP-006--Risk_Management.md). Any additional plans
that are needed **shall** be identified in the Project Plan, as appropriate.

Every project **shall** have a **Software Validation Plan** as defined
in the Software Development Procedure [SOP-012](SOP-012--Software_Development.md).

Any additional plans that are needed are identified in the Project Plan.

#### 4.2.1 Project Initiation

Executive Management is responsible for the decision to develop a new
medical device or to make modifications to an existing medical device
previously developed by __NewCorp__. Once this decision is made, a
Project Manager is identified. Executive Management is responsible for
allocating sufficient resources (appropriately trained people,
equipment and other resources) to complete the project.

Project Manager determines if third party resources are required to
develop the medical device as described in the Product Plan. All third
parties involved in medical device develop **shall** be selected
according to the Supplier and Purchasing Controls Procedure, [SOP-002](SOP-002--Supplier_and_Purchasing_Controls.md).

Regardless of whether outside resources are used, __NewCorp__
**shall** be responsible for complying with all requirements of the
__NewCorp__ QMS.

The Project Manager **shall** create a Project Plan that tailors
requirements required by the QMS to meet the specific needs of the
project. Any requirements required by the QMS that are not included in
the Project Plan **shall** be justified.

#### 4.2.2 Activities

Project planning identifies all activities that need to be performed
based on the requirements of this and other related SOPs and the
nature of the medical device being developed. The following
activities, at a minimum, **shall** be performed:

- **Identify Specific Patient and Clinician (user) Needs**: Specific patient and clinician (user) needs to be met by this medical device are identified and documented in or referenced by the Project Plan.

- **Create Statement of Intended Use **: The statement of Intended Use **shall** be developed and documented in
or referenced by the Project Plan. The intended use of the product and
user requirements are derived from clinician input and studies,
patient needs, feasibility studies, previous similar product design
requirements and feedback and other appropriate sources.

- **Identify Relevant Regulations, Guidance and Standards**: 
Relevant regulations, guidance documents and standards required for
compliance **shall** be identified and included in the Project Plan.
Relevant __NewCorp__ SOPs are also referenced in the Project Plan.

- **Identify Project Stakeholders**: Key project stakeholders are identified. At a minimum, the
stakeholders **shall** include representatives from the following
functional areas:
  -   Development
  -   Regulatory/Quality Assurance (RA/QA)
  -   Executive Management
The roles and responsibilities of the project stakeholders **shall**
be clearly defined in the Project Plan.

- **Create Product Requirements Specification (PRS)**: 
A Product Requirements Specification (PRS) **shall** be created for
new medical devices. The PRS defines intended use, clinical
requirements, patient needs and overall system requirements at a high
level. A review of the PRS **shall** be performed in accordance with
the Design Review Procedure, [SOP-007](SOP-007--Design_Review.md).

    A Product Requirements Specification (PRS) is a mandatory document
    that **shall** be prepared for all new medical device development
    projects. The PRS is optional for updates to previously developed
    medical devices.
    
    The Project Manager oversees development of the PRS based on:
    
    -   Research activities, concept documents, feasibility studies and
        other similar sources
    -   The statement of intended use and indications for use (IFU)
    -   Clinician and patient requirements
    -   Information from the initial risk assessment
    
    The PRS includes functional, performance, cyber-security, safety and
    regulatory requirements and any other requirements needed to fulfill
    the intended use and meet user and patient needs. An outline of a
    typical PRS is included in Appendix B.

- **Create Design History File (DHF) and Risk Management File (RMF)**:
The Project Manager **shall** establish the DHF as the repository for
all project documents and records (see Section 5 for examples of
records to be filed in the DHF). The Project Manager **shall** also establish the RMF as the repository
for all project risk management records and documents. (Refer to Risk
Management [SOP-008](SOP-008--Document_and_Record_Control.md) for details).

- **Determine project communication mechanisms**: Project communication 
mechanisms enable the project team to share technical information.

- **Identify specific work products**: Identify deliverables and work products associated with the software
development activities and tasks. Refer to Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md).

- **Define Project Change Control Process**: The Project Plan **shall** define a basic change control process to be used by the project team. This process defines a mechanism for
controlling changes to the design during the entire product
development life cycle. A typical change control process would require
all documents be placed under revision control and require a minimum
of three signatures for approval – including author, RA/QA Reviewer
and Management Approval.

- **Determine Project Staffing, Requisite Skills, and Training Needs**: Given 
the nature of the development work, the Project Manager identifies the project staffing needs as well as requisite skills needed for anticipated software development work. Based on staffing
requirements and skills, the Project Manager identifies qualified
individuals to work on the project. In addition, any training needs are identified. All members of the
development team (including third parties) **shall** have basic
training in FDA regulations for developing medical devices as well as
training on the specific SOPs and WIs that apply to the project.
Training records **shall** be maintained for each project team member.

- **Create a Functional Organization Chart**: The Project Plan includes a functional organization chart that
identifies the interfaces between different project groups (including
Contract Engineering firms) that provide or result in input to the
design and development process.

- **Prepare Initial Project Plan**: An initial Project Plan is prepared that outlines the required
activities and the documents and records that need to be created. The
Project Plan is based on this SOP and the Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md).  Key resources for the project (including __NewCorp__ staff, third
parties, software development resources, and tools) are identified. An
outline for a typical Project Plan is included in Appendix A.

#### 4.2.3 Activities, Work Products and Records

The activities, work products and records typically required in this
phase are summarized below.

<table>
<thead>
<tr class="header">
<th><strong>Activities</strong></th>
<th><strong>Work Products</strong></th>
<th><strong>Records </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Prepare and review Initial Project Plan</td>
<td><p>Initial Project Plan</p>
<p>(Refer to Appendix A)</p></td>
<td><p>Initial Project Plan</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="even">
<td>Prepare and review Initial Product Requirements Spec (PRS)</td>
<td><p>Initial PRS</p>
<p>(Refer to Appendix B)</p></td>
<td><p>Initial PRS</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Create DHF and RMF</td>
<td>DHF and RMF established</td>
<td></td>
</tr>
<tr class="even">
<td><p>Identify Project Training needs</p>
<p>Provide required training</p></td>
<td>Training Plan</td>
<td>Training Records</td>
</tr>
</tbody>
</table>

###  4.3 Requirements Definition Phase
---------------------------------

The Design Input includes the SRS. The SRS is developed based on
information in the PRS and other relevant documents as described in
the Software Development Procedure, [SOP-012](SOP-012--Software_Development.md).

#### 4.3.1 Activities

In addition to the activities described in the Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md), the following additional activities, at a minimum,
**shall** be performed:

- **Define Computer System Requirements**: Computer system requirements define the minimum system requirements
(including operating system, memory, CPU speed, video capabilities,
etc.) for the general-purpose computing platform the __NewCorp__
software-only medical device is installed on. These requirements are
documented in the Project Plan and filed in the DHF.

- **Create the initial Risk Management Plan (RMP)**: The Project Manager works with the project team to create a Risk
Management Plan that is consistent with the Risk Management Procedure,
[SOP-006](SOP-006--Risk_Management.md). A Design Review of the Risk Management Plan **shall** be held
in accordance with the Design Review Procedure, [SOP-007](SOP-007--Design_Review.md).

- **Perform Initial Risk Assessment**: Perform an initial risk assessment as required by the RMP.

- **Plan Formative Usability Study**: A formative usability study is planned. The objective of this study is
to determine early on if the proposed device and user interface are
safe and effective when used in a clinical setting. A Formative
Usability Protocol is prepared based on FDA Guidance (Applying Human
Factors and Usability Engineering to Medical Devices, February 2016).
A Design Review of the Formative Usability Plan **shall** be held in
accordance with the Design Review Procedure, [SOP-007](SOP-007--Design_Review.md).

- **Plan Requirements Traceability**: Every SRS requirement **shall** be traceable to a source document such
as the PRS, specific risk mitigations or other sources. A Requirement
Traceability Matrix (RTM) is created and maintained by the Project
Manager. The RTM is periodically updated as the project evolves.

- **Update and review previously approved work products, as appropriate**

#### 4.3.2 Activities, Work Products and Records

The Requirements Definition Phase results in the work products and
records as shown in the Software Development Procedure, [SOP-012](SOP-012--Software_Development.md). The
following additional work products and records are also created:

<table>
<thead>
<tr class="header">
<th><strong>Activities</strong></th>
<th><strong>Work Products</strong></th>
<th><strong>Records </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Define Computer System Requirements</td>
<td>Computer System Requirements</td>
<td>Computer System Requirements</td>
</tr>
<tr class="even">
<td>Create and review Initial RMP</td>
<td>Initial RMP</td>
<td><p>Initial RMP</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Perform initial Risk Assessment</td>
<td>Identification of potential harms</td>
<td>Potential harms (filed in RMF)</td>
</tr>
<tr class="even">
<td>Create and review Formative Usability Study Protocol</td>
<td>Formative Usability Study Protocol</td>
<td><p>Formative Usability Study Protocol</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Establish initial RTM</td>
<td>RTM</td>
<td>RTM</td>
</tr>
<tr class="even">
<td>Update and review Risk Assessment based on new information</td>
<td>Risk Assessment</td>
<td><p>Risk Assessment (filed in RMF)</p>
<p>Meeting Minutes (filed in RMF)</p></td>
</tr>
<tr class="odd">
<td>Update and review PRS, if needed</td>
<td>Revised PRS</td>
<td><p>Revised PRS</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="even">
<td>Update and review Project Plan, if needed</td>
<td>Revised Project Plan</td>
<td><p>Revised Project Plan</p>
<p>Meeting Minutes</p></td>
</tr>
</tbody>
</table>

### 4.4 Architecture and Design Phase 
----------------------------------

The Architecture and Design Phase results in creating the Design
Output. The Design Output includes the Software Architecture Document
(SAD), the Software Design Document (SDD), and source code. These work
products are developed as described in the Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md).

#### 4.4.1 Activities

In addition to the activities described in the Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md), the following additional activities, at a minimum,
**shall** be performed:

-   **Create the initial DMR and BOM**: The Project Manager creates the initial DMR and BOM. Typical contents
of the DMR includes:
  -   PRS, SRS, SAD and SDDs
  -   Software Validation Procedure and Report
  -   Media replication and installation procedures
  -   Packaging and Labeling Specifications
  -   Installation and Update Procedures

- **Create prototypes of critical components and assess initial usability**: 
Prototypes of critical components are created for the purpose of performing the required Formative Usability Study

- **Prepare Initial Labeling, Packaging and User Manual**: The initial labeling and User Manual are developed. Labeling includes physical labels that are applied to the medical devices as well as
information presented to users of the medical device through a user
interface. The User Manual provided with the medical device provides
information on proper operation, interpretation of messages, etc.
Applicable regulatory requirements for labeling are referenced in the
Project Plan.

Product packaging is intended to clearly identify the medical device
and all relevant information regarding the medical device.

-   The PRS **shall** contain requirements for packaging and labeling
    that ensure that device packaging and shipping containers are
    designed and constructed to protect the device from alteration or
    damage during normal processing, storage, handling,
    and distribution.

-   Labeling integrity is validated to ensure that labels will remain in
    place and are legible under normal operating and use conditions.

-   Labeling and packaging artwork is validated by having someone not
    familiar with the product operate it exactly according to labels
    and instructions.

-   Labeling and packaging designs are transferred into labeling and
    packaging specific documents and are included in the DMR as part of
    Design Transfer.

-   All labeling requires approval of the __NewCorp__ RA/QA
    Representative, who reviews the labeling to ensure that all
    regulatory and certification issues have been considered and are
    properly addressed.

-   **Update previously approved documents, as needed**

#### 4.4.2 Activities, Work Products and Records

The Software Architecture and Design Phase results in work products
and records shown in the Software Development Procedure, [SOP-012](SOP-012--Software_Development.md). The
following additional work products and records are also created:

<table>
<thead>
<tr class="header">
<th><strong>Activities</strong></th>
<th><strong>Work Products</strong></th>
<th><strong>Records </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Establish initial DMR and BOM</td>
<td>DMR and BOM</td>
<td>DMR and BOM</td>
</tr>
<tr class="even">
<td>Create and review initial product labeling and user manual</td>
<td>Initial labeling and user manual</td>
<td><p>Initial labeling and user manual</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Perform Formative Usability Study and review results</td>
<td>Formative Usability Study Report</td>
<td><p>Formative Usability Study Report</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="even">
<td>Update Risk Assessment based on new information</td>
<td>Risk Assessment</td>
<td>Risk Assessment records filed in RMF</td>
</tr>
<tr class="odd">
<td>Update and review previously approved documents, as needed</td>
<td>Updated documents</td>
<td><p>Updated documents</p>
<p>Meeting Minutes</p></td>
</tr>
</tbody>
</table>

### 4.5 Implementation and Verification Phase 
------------------------------------------

This phase provides objective evidence that the design outputs address
all specified design input requirements. Verification is planned and
performed in accordance with the Software Development Procedure,
[SOP-012](SOP-012--Software_Development.md).

Also during this phase, the Software Validation Team prepares Software
Validation Protocols in preparation for the Validation Phase. Computer
Systems required for the Validation Phase are also configured using a
documented procedure.

#### 4.5.1 Activities

In addition to the activities described in the Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md), the following additional activities, at a minimum,
**shall** be performed:

- **Prepare Software Validation Plan**: The Software Validation Team is primarily responsible for performing
the Software Validation activities. This team is comprised of people
not involved in software development activities and who have received
training in software validation tasks. The Validation Team prepares
the Software Validation Plan that defines the approach, resources, and
other relevant information required for the Validation Activity. The
Software Validation Plan includes:

  -   Identification of the software being validated by reference to
    version number and one or more product documents (such as the PRS
    and SRS, for example).

  -   Defined user needs and intended use as defined in the Project Plan.

  -   Validation approach and sources for acceptance criteria (SRS
    and PRS)

  -   At least one validation test activity that includes testing of the
    system by actual users under actual or simulated use conditions.

  -   At least one review of the project Risk Management File, as per the
    Risk Management Plan. (Refer to Risk Management
    Procedure, [SOP-006](SOP-006--Risk_Management.md))

- **Prepare Validation Protocols**: Validation Protocols are prepared in advance to support the Validation
Phase. The Software Validation Team creates these protocols. Each Validation Protocol defines all of the details associated with
that activity. These details **shall** include, at a minimum:
  -   Identification of the specific requirements that are the focus of
      system validation (e.g., SRS, PRS)

  -   Environment in which validation is to be performed (e.g., actual or
      simulated use conditions)

  -   Resources required – including people, equipment and other supplies
      as appropriate.

  -   Actual test cases, including specific test steps and
      expected results. An example of a test case is shown in
      Appendix C.
Validation protocols shall be reviewed and approved prior to executing
those protocols.

- **Create Software Installation Procedure**: A Software Installation Procedure is prepared that defines the process
for installing the medical device on computer systems that meet the
minimum configuration requirements defined in the Project Plan.

- **Prepare Initial Production Units**: Computer systems that meet the defined minimum specifications as
defined in the Project Plan are configured with the medical device
software in preparation for the validation activity. This
configuration is performed according to documented procedures.

- **Identify required documents and records for regulatory submission**: A 510(k) Checklist is created to identify all required documents and
records needed for the 510(k) submission. Items on the checklist are
collected and reviewed for completeness.

- **Update Risk Assessment based on new information**: Risk Assessment is updated based on new information and reflected in
the Risk Management records, as described in the RMP.

- **Update product labeling and user manual**: The product labeling and User Manual information is updated based on
new information and filed in the DHF.

- **Update previously approved documents, as appropriate**

#### 4.5.2 Activities, Work Products and Records

Deliverables resulting from the Verification Phase are defined in the
Project Plan and/or the Software Development Procedure, [SOP-012](SOP-012--Software_Development.md). These
deliverables typically include records that provide evidence that the
design outputs conform to specified design inputs.

<table>
<thead>
<tr class="header">
<th><strong>Activities</strong></th>
<th><strong>Work Products</strong></th>
<th><strong>Records </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Create and review Software Validation Plan</td>
<td>Software Validation Plan</td>
<td><p>Software Validation Plan</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="even">
<td>Create and review Software Validation Protocols</td>
<td>Software Validation Protocols</td>
<td><p>Software Validation Protocols</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Create and review Software Installation Procedure</td>
<td>Software Installation Procedure</td>
<td><p>Software Installation Procedure</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="even">
<td>Prepare Initial Production Units</td>
<td>Initial Production Units</td>
<td>Meeting Minutes</td>
</tr>
<tr class="odd">
<td>Identify required documents and records for regulatory submission</td>
<td>Regulatory Submission Checklist</td>
<td>Regulatory Submission Items</td>
</tr>
<tr class="even">
<td>Update and review product labeling and user manual</td>
<td>Updated labeling and user manual</td>
<td><p>Updated labeling and user manual</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Update Risk Assessment based on new information</td>
<td>Risk Assessment</td>
<td>Risk Assessment records filed in RMF</td>
</tr>
<tr class="even">
<td>Update and review previously approved documents, as needed</td>
<td>Updated documents</td>
<td><p>Updated documents</p>
<p>Meeting Minutes</p></td>
</tr>
</tbody>
</table>

### 4.6 Validation Phase 
---------------------

The Validation Phase is intended to establish thorough objective
evidence that product design specifications conform to defined user
needs and intended uses.

The Software Validation Team is primarily responsible for performing
the Software Validation activities. This team is comprised of people
not involved in software development activities and who have received
training in validation tasks. The Software Development Team provides
support as described in the Software Development Procedure [SOP-012](SOP-012--Software_Development.md).

Validation occurs in stages depending upon the nature of the device
and the risks to patients inherent in the device, as outlined in the
Project Plan and as described in the Validation Plan. For example,

-   **Level 1** – This stage is focused on determining if the device
    software meets requirements defined in the SRS document when the
    device is tested in a development environment. Trained validation
    staff performs the validation testing based using pre-approved
    validation test procedures. This level is always required.

-   **Level 2** – This stage is focused on determining if the device
    meets intended use and defined user needs as defined in the PRS when
    the device is used in a simulated clinical setting. Trained
    clinicians who are representative of actual users perform the
    validation testing based on pre-approved validation protocols. This
    level is optional.

-   **Level 3** – This stage is focused on determining if the device
    meets intended use and defined users needs when used in an actual
    (or simulated) clinical setting. Actual end users perform the
    validation testing using pre-approved validation protocols. This
    stage is referred to as a Clinical Trial and may be required to
    provide clinical and performance date to support a 510(k)
    submission.

If a Clinical Trial will be performed with patient data, the
requirements for informed consent and review by an Institutional
Review Board (IRB) must be met.

While Clinical Trials are not always required, testing in an actual or
simulated use setting is always required.

Any failures that occur during the software validation activity
**shall** be documented and resolved using the defect tracking process
defined in the Project Plan.

Validation activities **shall** be planned and performed:

-   by staff other than development engineers

-   under defined operating conditions

-   on initial production units or their equivalents

-   under actual or simulated use conditions.

Initial production units are defined as general purpose computing
systems that meet the minimum platform requirements defined in the
Project Plan for the device.

#### 4.6.1 Activities

The following activities, at a minimum, **shall** be performed:

-   **Execute Validation Protocols**: The Validation Team executes the approved validation protocols and
records all test results.

-   **Report Failures**: The Validation Team reports any failures, unexpected results or
anomalies using the Defect Tracking tool as described in the Project
Plan.

-   **Resolve Failures and create New Software Builds**: The Software Team reviews defects reported by the Validation Team and
determines the nature of the failure. If the failure is a deficiency
in the code, the problem is resolved and a new software build is
created. If the problem is determined to be in a document (such as
PRS, SRS, or SDD), the document is revised and affected tests are
updated accordingly.

-   **Perform Regression Testing**: Upon receiving a new software build, the Validation Team identifies
what defects have been resolved and what components have been updated.
An appropriate set of regression tests are selected and run to ensure
the defect is properly fixed and new problems have not been created.

-   **Prepare Validation Reports**: When all tests have been executed and all failures have been
dispositioned, the Validation Team prepares the Validation Report that
summarizes the validation activity. The validation report includes the
following information:
  -   Executed copy of each test case (refer to Appendix D)
  -   Copy of each defect or defect report showing its resolution
  -   Status of all defects reported
  -   Identification of defects reported for each software baseline tested
  -   Regression testing done per software baseline
  -   A summary and analysis of results including acceptability of
    validation results relative to the acceptance criteria defined in
    the Validation Plan
  -   Final RTM showing all design input requirements and risk management
    mitigations and the activities used to validate each requirement
    and mitigation.
-   **Perform Summative Usability Assessment**:  The Summative Usability Protocol is executed and results are
documented in a Summative Usability Report. The report is reviewed and
filed in the DHF.
-   **Prepare Design Transfer Work Instruction**: A Design Transfer Work Instruction (WI) **shall** be prepared. This
work instruction is project specific, very detailed and defines the
precise steps required to release software for installation by the
distribution entity.  The Design Transfer WI lists the specific steps that need to be taken
to accomplish Design Transfer. This WI is intended to ensure that the
released software product can be reliably delivered to the point of
use without corruption or unauthorized change. This WI addresses
release of software to the distribution entity, media duplication and
handling of media containing the software product. The following information **shall** be included in this WI at a
minimum:
  -   Media labeling, including reference to part number(s) on the Bill of
      Materials (BOM)
  -   Appropriate handling and packaging (such as, anti-static bags
      if appropriate)
  -   Identification of the software that is being released by
      part number(s) on the BOM and version number for each part
  -   Identification of each individual source code component by name
      and version number to be released
  -   Identification of libraries, SOUP or OTS software by name and
      version number that are to be released
  -   Identification of the build scripts required to compile source
      code and create the binary files that are to be released
  -   Identification of install files required to install software on
      the target environment
  -   Identification of an integrity check, such as checksum or cyclic
      redundancy check (CRC) that is applied to the binary or
      executable file(s) to be released
  -   Identification of the physical media which will contain the
      released binaries and how that media is to be replicated as
      part of the manufacturing process
  -   Detailed procedures to be used by the distribution entity to
      replicate the integrity check and verify the accuracy of the
      binary files
  -   Procedure to archive the development environment including all
      development tools and source files, libraries, OTS, SOUP and
      build scripts
-   **Validate Design Transfer Work Instruction**: A process validation protocol is prepared and executed to determine if
the Design Transfer WI is effective and repeatable.
-   **Execute Design Transfer Work Instruction**: Once the Design Transfer WI has been validated, it can be executed.
-   **Update previously approved documents, as appropriate**

#### 4.6.2 Activities, Deliverables and Records

Deliverables resulting from the Validation Phase are defined in the
Project Plan and/or the Software Development Procedure, [SOP-012](SOP-012--Software_Development.md). These
deliverables typically include records that provide evidence that the
medical device conforms to specified product and software requirements
and meets the intended use and defined needs of users and patients.

<table>
<thead>
<tr class="header">
<th><strong>Activities</strong></th>
<th><strong>Work Products</strong></th>
<th><strong>Records </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Execute approved Validation Protocols</td>
<td>Test Results</td>
<td>Test Results</td>
</tr>
<tr class="even">
<td>Report and review defect reports</td>
<td>Defect Reports</td>
<td>Defect Reports</td>
</tr>
<tr class="odd">
<td>Fix defects and create new software baselines</td>
<td><p>Defect Reports</p>
<p>Software Baselines</p></td>
<td>Review software Baselines</td>
</tr>
<tr class="even">
<td>Perform Regression Testing</td>
<td>Test Cases</td>
<td>Test Records</td>
</tr>
<tr class="odd">
<td>Report and review defect reports</td>
<td>Defect Reports</td>
<td>Defect Reports</td>
</tr>
<tr class="even">
<td>Perform Regression Testing</td>
<td>Test Cases</td>
<td>Test Records</td>
</tr>
<tr class="odd">
<td>Prepare and review Validation Report</td>
<td>Validation Report</td>
<td>Validation Report Meeting Minutes</td>
</tr>
<tr class="even">
<td><p>Perform Summative Usability Protocol</p>
<p>Review results</p></td>
<td>Summative Usability Report</td>
<td><p>Summative Usability Report</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Prepare and review Design Transfer Work Instruction</td>
<td>Design Transfer Work Instruction</td>
<td><p>Design Transfer Work Instruction</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="even">
<td>Perform Process Validation of the Design Transfer WI</td>
<td>Process Validation Protocol</td>
<td><p>Report</p>
<p>Meeting Minutes</p></td>
</tr>
<tr class="odd">
<td>Assemble required documents and records for regulatory submission</td>
<td>Regulatory Submission Checklist</td>
<td>Regulatory Submission Items</td>
</tr>
<tr class="even">
<td>Update and review previously approved documents, as appropriate</td>
<td>Updated documents</td>
<td><p>Updated documents</p>
<p>Meeting Minutes</p></td>
</tr>
</tbody>
</table>

### 4.7 Design Transfer Phase 
--------------------------

The Design Transfer Phase results in the transfer of the medical
device design specifications for replication and installation. A
project-specific Design Transfer Plan that addresses all of the
components (i.e., software, labeling, etc.) required for the device
**shall** be prepared.

Design Transfer activities can begin upon successful completion of the
Validation Phase. During Design Transfer, the software is prepared for
release to the distribution entity.

Prior to releasing software, the Project Plan **shall** require that:

-   All development activities have been completed
-   All action items from Design Reviews have been resolved
-   All planned software verification and validation activities have
    been completed and results documented and filed in the DHF
-   All known software defects that were not fixed are documented and a
    justification as to why they do not affect clinical results or
    present unacceptable risk has been prepared and filed in the DHF
-   The released version and the process for creating the released
    version, is documented
-   The source code, software development environment (tools), all
    documentation, and everything needed to re-create the released
    software version have been archived
-   Procedures have been established to address:
    -   Installation instructions
    -   Required user or operator training
    -   Cyber-security requirements and installation needs
    -   On-site acceptance requirements
-   All required records are filed in the DHF and RMF

Responsibility for the activities and deliverables for this phase
**shall** be defined in the Project Plan.

Documented evidence (records) that the design transfer has been
planned and performed is filed in the DHF.

#### 4.7.1 Activities

In addition to the activities described in the Software Development
Procedure, [SOP-012](SOP-012--Software_Development.md), the following additional activities, at a minimum,
**shall** be performed:

#### 4.7.2 Deliverables

Deliverables associated with the Design Transfer Phase are defined in
the Project Plan. (Refer to Installation and Service Procedure,
[SOP-010](SOP-010--Installation_and_Service_Controls.md))

<table>
<thead>
<tr class="header">
<th><strong>Activities</strong></th>
<th><strong>Work Products</strong></th>
<th><strong>Records </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Execute approved Validation Protocols</td>
<td>Test Results</td>
<td>Test Results</td>
</tr>
<tr class="even">
<td>Execute Design Transfer Procedure</td>
<td><p>Software Archive</p>
<p>Released Software Version integrity check</p></td>
<td><p>Software Archive</p>
<p>Released Software Version integrity check</p></td>
</tr>
</tbody>
</table>

### 4.8 Control of Non-conforming Product 
--------------------------------------

__NewCorp__ **shall** establish and maintain a procedure that
minimally provides for identification, review, and disposition of
nonconforming product. This procedure **shall** ensure that
__NewCorp__ and its subcontractors have an effective system to
prevent unintended use or delivery of nonconforming product.

For a software-only medical device, non-conforming product is defined
to mean software that does not conform to either the PRS and/or SRS.
Project procedures **shall** be defined in the Project Plan to ensure
that software versions that have not successfully completed the
Validation Phase are not inadvertently released to users.

## 5.0 RECORDS

At a minimum, the following records **shall** be prepared and filed in
the DHF. All versions of the records listed below **shall** be filed
in the DHF. The Project Manager **shall** be responsible for the
integrity and completeness of the DHF.

All records filed in the DHF **shall** require at least one signature,
including printed name of all persons signing as well as the date the
record was signed.

-   Project Plan, Statement of intended use and IFU

-   Product Requirements Specification (PRS) including clinical
    requirements and user/patient needs

-   Software Requirements Specification (SRS)

-   Software Architecture Document (SAD) and Software Design
    Document (SDD)

-   Meeting minutes from all required Design Reviews

-   SOPs and Work Instructions

-   Engineering and Lab Notebooks

-   Contractor and Consultant qualification information

-   Validation Plan

-   Formative and Summative Usability Protocols and Reports

-   Labeling and User Manual, Packaging and Shipping Information

-   DMR and BOM

-   Verification Test Procedures and Reports

-   Validation Protocols and Reports

-   Defect Reports and their resolution

-   Design Transfer Work Instruction and Process Validation Report

-   Software Archive

-   Released Software version and code signature of released software
    version

-   Software Maintenance Plan

Records required for Risk Management are specified in the Risk
Management Procedure, [SOP-006](SOP-006--Risk_Management.md) and RMP. Risk Management records are
filed in the Risk Management File (RMF).

### 5.1 Record Retention Period
-------------------------------

The record retention period for Project Records **shall** be defined
in the Document and Records Control Procedure, [SOP-008](SOP-008--Document_and_Record_Control.md).

## Appendix A Project Plan Outline 
-----------------------------------------------------------------------

At a minimum, the following topics **shall** be included or referenced
in the Project Plan

-   Product overview

-   Statement of intended use and IFU

-   Assumptions

-   Identification of applicable regulations, guidance documents and
    standards

-   Interfaces with other development groups – such as clinical
    resources and Contract Engineering firms

-   Functional org chart showing all parties involved in the project

-   Software Development tools to be used – and plans for validating
    them

    -   Name and version of tool

    -   Supplier name and contact info

    -   Purpose

-   **Project Phases and Activities, Tasks and Records for each**:  This section contains the information included in Section 4 of this
SOP but tailored for the needs of the project. Any phase, activity, or
task not included must be justified.  For each software development phase:
  -   Description of Phase
  -   Responsibility for Phase Activities
  -   List of Phase Activities
  -   Deliverables and Records resulting from Phase Activities
  -   Include justification for any activity/deliverable identified in
      this SOP section 4 that is NOT included in this Project Plan

-   Traceability Requirements

-   Risk Management Plan

-   Software Validation Plan

-   Problem resolution and Defect tracking processes

-   Software version numbering scheme

-   Source Code Repository

-   Change Control Process

-   Required Design Reviews

-   Product labeling, user documentation user instructions, and on‐line
    help

-   Design Transfer Work Instruction

-   Records: identify all required records that need to be filed in the
    DHF

Appendix B Product Requirements Spec Outline
-----------------------------------------------------------------------

TBD

Appendix C Example Validation Test Case
-----------------------------------------------------------------------

<table>
<thead>
<tr class="header">
<th><strong>Test ID</strong></th>
<th>Identifier- ideally, should be requirement ID test is intended to validate.</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Test Objective</strong></td>
<td>A short statement that summarizes the objective of each test.</td>
</tr>
<tr class="even">
<td><strong>System Configuration</strong></td>
<td>A description of the system configuration required for this test. Specifically, how is the client configured and how is the server configured.</td>
</tr>
<tr class="odd">
<td><strong>Special Equipment </strong></td>
<td>Identify any special equipment required for this test.</td>
</tr>
<tr class="even">
<td><strong>Initial Conditions</strong></td>
<td>Identify initial conditions or state that the system should be in before executing the test.</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><strong>Test ID: 4.1.1-3</strong></td>
</tr>
<tr class="even">
<td><strong>Actions</strong></td>
</tr>
<tr class="odd">
<td>1. Turn on the device.</td>
</tr>
<tr class="even">
<td>2. Click on &quot;Calibrate &quot; button.</td>
</tr>
<tr class="odd">
<td>3. Select Option 1</td>
</tr>
<tr class="even">
<td>4. Etc..</td>
</tr>
<tr class="odd">
<td>5.</td>
</tr>
<tr class="even">
<td>6.</td>
</tr>
<tr class="odd">
<td>Done.</td>
</tr>
<tr class="even">
<td></td>
</tr>
<tr class="odd">
<td>Test Performed by:</td>
</tr>
<tr class="even">
<td>Software version tested:</td>
</tr>
<tr class="odd">
<td>Notes and Observations:</td>
</tr>
</tbody>
</table>
