# __NewCorp__ Quality Manual
## Design Review Procedure
## SOP-007

# 1.0 PURPOSE

This Standard Operating Procedure (SOP) provides *minimum*
requirements (requirements are expressed using the word **shall**)
for planning, conducting, and documenting design reviews associated
with software-only medical devices developed by __NewCorp__ and by
third parties working under the direction of __NewCorp__.

# 2.0 SCOPE

This procedure applies to new product development as well as
enhancements and maintenance to previously released software-only
medical devices developed by __NewCorp__.

This SOP does not apply to "off the shelf" products or components
where __NewCorp__ has no influence over the design process. This
SOP does not apply to research activities.

# 3.0 REFERENCES, TERMS AND ACRONYMS

## 3.1 Regulatory References

1.  21 CFR Part 820 FDA Quality System Regulation, 1996

2.  ANSI/AAMI/ISO 13485:2003 Medical Devices-Quality Management Systems
    Requirements for Regulatory Purposes

3.  ANSI/AAMI/ISO 14971:2007 Medical Devices – Application of Risk
    Management for Medical Devices.

4.  FDA Guidance for the Content of Pre-market Submissions for Software
    Contained in Medical Devices, May 11, 2005

5.  FDA Design Control Guidance for Medical Device Manufacturers, 1997

## 3.2 __NewCorp__ References 

1.  Quality Manual, [QM-001](QualityManual.md)

2.  Design Control Procedure, [SOP-001](SOP-001--Design_Control.md)

3.  Document and Record Control Procedure, [SOP-008](SOP-008--Document_and_Record_Control.md)

4.  Software Development Procedure, [SOP-012](SOP-012--Software_Development.md)

## 3.3 Terms

- **Design History File**: The design history file (DHF) contains or references
the documentation necessary to demonstrate that the design was developed
in accordance with the approved design plan and associated procedures.

- **Design Input**: The design input represents the requirements for the
medical device and reflect intended use and the needs of the user and
patient.

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
environment for subsequent distribution and installation for production
use at clinical sites.

- **Device Master Record**: The device master record (DMR) is a compilation of
records containing the procedures and specifications for a finished
device.

- **Validation**: Validation means confirmation by examination and provision of
objective evidence that the particular requirements for a specific
intended use can be consistently fulfilled.

- **Verification**: Verification means confirmation by examination and
provision of objective evidence that specified requirements have been
fulfilled. \[820.3(aa)\]

## 3.4 Acronyms

- **CAPA**: Corrective Action / Preventive Action

- **CFR**: Code of Federal Regulations

- **DHF**: Design History File

- **DMR**: Device Master Record

- **NA**: Not applicable

- **OTS**: Off the shelf

- **QM**: Quality Manual

- **QMS**: Quality Management System

- **QSR**: Quality System Regulation

- **RMF**: Risk Management File

- **SOP**: Standard Operating Procedure

- **SRS**: Software Requirements Specification

- **WI**: Work Instruction

  
# 4.0 DESIGN REVIEW PROCESS 

Design reviews are tools for performing a comprehensive and systematic
assessment of aspects of the medical device design. Design reviews are
typically used to assess product requirements (design inputs) and
design specifications (design outputs), including the product design
and associated design for manufacturing processes. Design reviews can
also be used to assess verification and validation activities.

Design reviews can be formal (meaning they are planned in advance and
the results are documented in a record, as described in section 5.0)
or informal (meaning they are conducted on an as-needed basis and
there is no record produced).

Formal design reviews are planned in advance and included in the
Project Plan. The Project Manager is responsible for ensuring that
required design reviews are included in the Project Plan and that
those design reviews are conducted as planned.

The purpose of any design review is to:

- Assess the adequacy of the product requirements (design inputs) based on intended use and user needs

- Assess whether the design specifications (design outputs) adequately meet product requirements (design inputs)

- Provide feedback to designers on existing or emerging problems

## 4.1 Design Review Planning

Formal design reviews are planned and identified in the Project Plan.
At a minimum, formal design reviews **shall** be conducted for the
Product Requirements Specification (PRS) and Software Requirements
Specification (SRS). Additional design reviews **shall** be planned
and conducted commensurate with risk.

Formal design reviews include:

- **Agenda**: The design review agenda includes identification of: 
  - Source document and author
  - Reference document(s)
  - Review Team Members and roles for each
  - Preparation time period
  - Scheduled date for review meeting
- **Review Team**: The review team typically consists of at least 3 people who are tasked with preparing for and participating in the design review. The __NewCorp__ **QA representative** is invited to all design reviews. 
- **Independent Reviewer**: One member of the review team is identified as the “Independent Reviewer”. This person is not involved in the design activity being reviewed and is technically capable of understanding and evaluating the document being reviewed. The __NewCorp__ **QA representative** can act as the independent reviewer.
- **Moderator**: The moderator is a member of the review team who leads the discussion during the review meeting. The moderator should not be the author of the document being reviewed.
- **Recorder**: The recorder is a member of the review team. The recorder records all issues that arise during the review meeting. The recorder issues the design review meeting minutes (described below).
- **Author**: The primary author of the source document.
- **Source Document**: This is the document that is being reviewed.
- **Reference Document(s)**: The document the source document is reviewed against. For example, the Software Requirements Spec is reviewed against the Product Requirements Spec.
- **Preparation Phase**: The preparation phase is the time allotted to the review team to prepare for the design review meeting. Typically the source and reference document(s) are distributed to the review team at least five working days ahead of the planned review meeting to allow the review team time to prepare.
- **Design Review Meeting**: The design review meeting is held following the preparation phase. This meeting is planned for not more than 3 hours. If the review is not completed by the end of 3 hours, the meeting is adjourned and reconvened the next working day. 
- **Design Review Minutes**: The design review minutes document what occurred during the design review. See details in section 5 below.
- **Follow-up**: Once the design review is held, the moderator is responsible for ensuring the all of the issues raised during the review are eventually addressed and closed. As issues are closed, the design review minutes are updated to include information describing what actions were taken to address the issue.

## 4.2 Design Review Preparation

Once a design review is planned, the moderator and author work
together to ensure that:

- The source document and all reference documents are made available to the review team in a timely manner at least 5 working days prior to the scheduled review meeting

- The logistics for planning and conducting the meeting have been worked out and communicated in the agenda

Once the source and reference documents are distributed, each member
of the review team reviews the source document against the reference
document(s) and identifies places where they do not agree or where
further clarification is required.

## 4.3 Design Review Meeting

The design review meeting provides a forum for discussion of issues
related to the source document based on the preparation done in
advance by the review team.

The moderator opens the design review meeting by quickly reviewing the
following ground rules:

### Design Review Ground Rules

- **Advance preparation**: This is essential to make reviews effective. If, in the opinion of the
moderator, the review team is not prepared, the design review meeting
is postponed.
- **Consensus**: All issues identified are considered. The author agrees to respond to
all issues that the review team identifies. All of these issues are
recorded in minutes.
- **Professional behavior**: Every member of the review team is expected to behave in a polite and professional manner during the review discussion.
- **Moderator**: The Moderator’s role during the meeting is to ensure that the review is performed in an effective and efficient manner.
- **Author**: The author’s role during the meeting is to provide clarification to questions raised by the review team.
- **Find problems rather than solve them**: The focus of the review meeting is to find problems not solve them. The author will be tasked with solving problems separately. This enables the review team to focus on finding as many problems as possible without being distracted by discussing solutions. The review team will have the opportunity to see how problems were resolved and provide feedback on the resolution separately. The Moderator will review all resolutions and determine if they correctly address the review team’s concerns.
- **Minutes**: The recorder will record all issues identified by the review team.
- **Duration**: Design review meetings should be planned for not more than 3 hours. If the review is not completed at the end of 3 hours and it appears a significant amount of time would be required to complete the review, the Moderator schedules a second 3-hour session.

The moderator conducts the review meeting by going through the source document section by section or page-by-page asking for comments or issues.

The review team reaches consensus on issues that need to be addressed.

The recorder documents each issue – identifying the location in the source document the issue was raised and the reason the issue is being raised (i.e., doesn’t match reference document, unclear as stated, etc.).

After the review is completed, the recorder reviews the list of issues to ensure they have been captured correctly.

# 5.0 Design Review Records

The meeting minutes are the record that documents the design review. Meeting minutes **shall** include the following information, at a minimum:

- Source document reviewed, document number and revision
- Reference document(s)
- Review team members, listing the roles of each member (Moderator, Recorder, Author, Reviewer, and Independent Reviewer)
- Date of design review
- List of issues identified
- How each issue is resolved (completed by the author after the design review)
- Printed name, signature and date of recorder signifying the information is accurate

Meeting minutes from all design reviews **shall** be created and controlled as defined in the Document and Record Control Procedure, [SOP-008](SOP-008--Document_and_Record_Control.md).

Meeting minutes **shall** be filed in the DHF.

A template for documenting design review minutes is included in Appendix A.

# Appendix A Appendix A Design Review Meeting Minutes Template

**Project Name - Design Review Meeting Minutes**

<table>
<thead>
<tr class="header">
<th><strong>Source Document:</strong></th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Reference Document(s): </strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Review Date</strong>:</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Author(s):</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Moderator</strong>:</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Recorder</strong>:</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Reviewers</strong>:</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Independent Reviewer:</strong></td>
<td></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th><strong>Item</strong></th>
<th><strong>Section</strong></th>
<th><strong>Issue requiring investigation</strong></th>
<th><strong>How was issue addressed</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ \_\_\_\_\_\_\_\_\_

printed name of recorder date

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ \_\_\_\_\_\_\_\_\_

signature of recorder date
