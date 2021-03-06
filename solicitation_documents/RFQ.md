# 14(c) Web Application Tool
## Agile Delivery Services Blanket Purchase Agreement
# Request for Quotation (“RFQ”)
 
## 1.0 Background
The Department of Labor (“DOL”) Wage and Hour Division (“WHD”) is engaged in an effort to modernize their paper-based system of processing applications for 14(c) certificates by developing an electronic replacement known as the 14(c) Web Application Tool.
 
Section 14(c) of the Fair Labor Standards Act (“FLSA”) permits the payment of subminimum wages -- wages less than the general minimum wage -- to workers with disabilities whose earning or productive capacity is impaired by a disability for the work to be performed, after the employer has applied for and received an authorizing certificate from DOL.
 
Once in production, the 14(c) Web Application Tool allows employers to apply for 14(c) certificates through an online interface. The online interface has [already been created](https://github.com/18F/dol-whd-14c) along with [an API](https://github.com/18F/dol-whd-14c/tree/master/DOL.WHD.Section14c.Api) that will allow for it to be connected to a backend database and/or application.
 
The primary purpose of this project is to modify existing features and to develop new features for the 14(c) Web Application Tool and the associated API.
 
This application must be centered on the needs of its *end users*, including:
- Employers who submit 14(c) certificate applications through the online interface
- DOL WHD personnel who need to track, review, and update submitted applications as they move through the review and approval process
- Administrators who will control authorization to view the 14(c) applications
 
## 2.0 Performance Work Statement (“PWS”)
To fulfill the objectives for performance of this task order, the Vendor must meet the user needs described in the following subsections. Please note that, in subsequent sprints, we may refine these objectives to ensure we’re continually meeting user needs. In agreement with the product owner, we may modify, add, retract, or reprioritize user stories to reflect additional research.
 
This requirement is the development and expansion of an existing front-end application and API that will allow employers to apply for a 14(c) certificate from DOL and will allow DOL WHD personnel to display, view, update, and modify pertinent information regarding 14(c) applications submitted by employers seeking certifications. To satisfy the needs of DOL WHD, the following deliverables must be provided by the conclusion of performance.
 
### 2.1 Tasks
The Vendor will provide the following services:
 
Task 1 - Enhance and develop the existing AngularJS frontend with new features as prioritized in the Sprint backlog
 
Task 2 - Enhance and develop the existing C# (.NET) API with new features as prioritized in the Sprint backlog
 
Depending on the outcome of user research and design, additional data and metrics may be required during the period of performance. In accordance with agile methodologies, the vendor, GSA TTS team, and DOL WHD will work together throughout the period of performance to rapidly develop features to further determine, refine, and prioritize the backlog.
 
- Convert data gathered from front-end into a downloadable document that can be accessed by both employers and DOL employees.
- Allow DOL staff to monitor status and routing of applications through the review and approval process.
- Vendor must implement application activity and error logging into the application.
- Create functions that emphasize the end-user’s needs.
- Following TTS’ API-first strategy, any new data system developed must have the capability to provide output data.
- Vendor must create and execute, in collaboration with GSA TTS and DOL WHD, a research strategy that accounts for periodic interaction with 14(c) Web Application Tool users and stakeholders. Vendor must coordinate with DOL WHD to recruit, for purposes of this research, stakeholders. Stakeholders will include, DOL WHD developers, administrators, and other application processors, and those tasked with the management, analysis, and reporting of WHD data.
- Vendor must conduct research activities including, but not limited to, stakeholder interviews and usability tests.
- Vendor must post all code to a publicly-available code repository, with a Public Domain license.
- Vendor must ensure that the application and API provide the ability to export data by interacting with a file or an API, and that the architecture is extensible to allow for future development.
- Vendor must incorporate analytics, monitoring, continuous integration, and measurement tools into their code base.
- Vendor must use plain language in application design and development whenever possible. In the event that DOL WHD does not provide the Vendor with content-specific guidance or grammatical rules for the 14(c) Web Application Tool, Vendor should adhere to GSA TTS [18F’s content guide](https://pages.18f.gov/content-guide/).
- Vendor must establish, and ensure the 14(c) Web Application Tool’s adherence to, a reasonable [performance budget](https://timkadlec.com/2013/01/setting-a-performance-budget/) for mobile devices.
- Vendor must utilize the [US Web Design Standards](https://standards.usa.gov/) or other development standards as developed by the GSA TTS team or required by DOL.
- Vendor shall work with DOL WHD’s security team to achieve an Authority to Operate (“ATO”) by collaborating with one another in order to verify and confirm all system controls meet the required DOL guidelines.
 
The Vendor is not responsible for performing the following:
- Hosting of the of the system outside of a development and demonstration context.
- Manage the granting of an ATO.
 
### 2.2 Application constraints 
The 14(c) Web Application Tool must be developed using acceptable technology within DOL WHD’s standards, including:
- C# .NET v4.5.2
- AngularJS v2.x and v1.x
- Typescript
- MVC 5
- Entity Framework 6
- ANSI SQL
- Ability to write against DB2 SQL through a DB2 cloud account
- Web API
- xUnit (Web API unit tests)
- Jasmine, Karma, and/or Mocha (JavaScript based UI unit, integration, and feature tests)
- Jenkins CI
- Visual Studio 2015 update 3
   - Be ready to update to Visual Studio 2017 once DOL has approved
 
The authorization system must be integrated with DOL WHD authentication system, via an exposed API. The existing API must work with DB2.
 
### 2.3 Additional requirements
- Work will be conducted in two-week sprints and reviewed at the end of each sprint for acceptability per the Quality Assurance Surveillance Plan (“QASP”) before moving on. The Vendor and Government may mutually agree to alter sprint length as needed.
- Usability testing and other user research methods must be conducted at regular intervals throughout the development process (not just at the beginning or end), with all artifacts from usability testing and/or other research methods with end-users being made available at the end of every applicable sprint.
- All software code delivered under this order shall comply with the [18F open source policy](https://github.com/18F/open-source-policy/) in effect as of the date of award.
- All software code delivered under this order shall comply with the [18F Accessibility Guidelines](https://pages.18f.gov/accessibility/) in effect as of the date of award.
- All dependencies (and licenses for dependencies) must be listed.
- All major functions must be documented inline.
- Code must be stored in a version-controlled, open-source repository, with all code needed to run the front-end of the prototype available in that repository.
- All Contractor Key Personnel, employees, agents, subcontractors, and subcontractor personnel who will have access to documents or data during the performance of their duties under the contract shall execute the attached Non-Disclosure Agreement and return it to the CO within 5 calendar days of award and before being given access to such information or documents.
 
### 2.4 Post Award Orientation Conference
The Government’s team and the Contractor’s team will hold a Post Award Orientation Conference (“Vendor Kickoff”) within 10 calendar days of Award. The Government’s team will include the Contracting Officer (“CO”), the Contracting Officer’s Representative (“COR”), the TTS Product Lead, and the Product Owner (“PO”).
 
Ideally, this will be physically located in Washington, DC, but may be done virtually. The purpose will be to review and clarify the project’s objectives and the Government’s expectations. Additionally, the Government will address any questions the Contractor may have. Discussion topics shall include, but not be limited to:
- Introduction of the Contractor and Government staff
- Understanding of the workflow
- Project management expectations
- Agreement on communication methods
- Discussion of any other relevant specific concerns
- Finalizing Contractor Teaming Arrangements (CTAs)/Subcontractor arrangements
 
### 2.5 Daily Operations
The Contractor’s Project Manager / ScrumMaster shall be responsible for daily operations as well as coordinating and communicating with the TTS Product Lead. Daily operations may include:
- Daily standup via Google Hangouts, Zoom, appear.in, or other web-based video chat software
- Chat operations via Slack
- Manage and update user stories and workflow tasks in a shared project management system, such as Trello
 
### 2.6 Frequency of Invoices
The Contractor must provide invoices on a monthly basis.
 
### 2.7 Transition Plan
- Ensure and agree that all deliverables, products, licenses, designs, data, documentation, tests, user research notes, source code, configuration settings and files, and materials developed throughout this call order will be the property of the U.S. Government and in the public domain.
- Two weeks prior to call order conclusion, provide a brief transition plan for all deliverables, products, and materials in coordination with the TTS Product Owner and COR.
- Coordinate with the TTS Product Owner and COR, and potentially another contractor, and implement the transition plan.
- Provide any other reasonable assistance to the Government to stand-up the application.
 
### 2.8 Transition Activities
During the transition to the Government or a new contractor, the Contractor shall perform all necessary transition activities. Expected transition activities may include, but not be limited to: 
- Continuation of full services to TTS and other customers
- Participation in meetings with the Government or a new contractor to effect a smooth transition and provide detailed information on the operation of all deliverables, at COR and the TTS Product Lead's discretion
- Training of new personnel, either Government or a new contractor, during transition period
- Appropriate close-out of any outstanding technical and related performance elements for this task
 
The final report shall include a list of sprint tasks completed, documentation, and a link to the code repository developed for TTS. Should the Contractor be terminated prior to the end of the period of performance, the Contractor shall transfer all project materials to the COR and the TTS Product Lead within two weeks of the COR and the TTS Product Lead’s request.
 
## 3.0 List of deliverables
| **DELIVERABLES** | **DUE DATES** | **CONTENT DESCRIPTION** |
|:----------:|:-------------:|:------:|
| QASP | 8 calendar days after award | A document that contains performance measurement indicators similar to those in our proposed QASP |
| Code repository of product | Ongoing with every applicable sprint | Version-controlled open source code repository that comprises product that will remain in the public domain |
| Issues in repository from usability testing | Ongoing with applicable sprint | Usability or other issues discovered via usability testing and documented in the project’s source control system |
| Design deliverables | Ongoing with every applicable sprint | Mock-ups and/or design files if applicable, or design changes reflected in the development product |
| Issues from user testing | Ongoing with applicable sprint | Issues raised by user testing |
| Development product | Ongoing with applicable sprint | In-progress development product, accessible on the web via staging server / development server |
 
## 4.0 Personnel
### 4.1 Required skills and knowledge
The Vendor must provide a team of qualified personnel — people whose knowledge and experience allows them to successfully perform the work outlined in this task.
 
Proposed personnel must have a strong technical experience base in the following:
 
- Technology stack as described in Section 2.2.
 
Using human-centered design methods to build and test form-driven, web-based applications. Human-centered design practices include:
- Research, such as (but not limited to) contextual inquiry, stakeholder interviews, and usability testing
- User experience design
- Front-end development
- Sketching, wireframing, and/or prototyping
- Visual design 
- Content design
 
- Mobile-first approaches, performance budgeting, and progressive enhancement
- Building and testing public facing sites and tools
- Open-source software development 
- Cloud deployment - for demonstration hosting
- Open-source login/authentication services
- Agile and Scrum methodologies 
 
### 4.2 Key Personnel
#### 4.2.1 Categories
**For this task the following Key Personnel are necessary (as detailed at [https://agile-labor-categories.18f.gov](https://agile-labor-categories.18f.gov/))**
 
- **Project Manager / Scrum Master**
- **Senior Fullstack Developer**
- **Interaction Designer / User Researcher / Usability Tester**
 
#### 4.2.2 Key Personnel substitution
In the event a Key Personnel member becomes unavailable during the course of the solicitation and evaluation process, the Contractor shall immediately notify the Government and provide a substitute individual with resume that fits within all the guidelines outlined in section 5.0.
 
In the event a Key Personnel member will be substituted, the Contractor shall provide complete resumes for proposed substitutes, and any additional information requested by the Contracting Officer no later than 5 business days after notifying the Government of the need for a substitution. Proposed substitutes should have comparable qualifications to those of the persons being replaced. The Contracting Officer will notify the Contractor within 15 business days after receipt of all required information of the consent on substitutes. No change in fixed unit prices may occur as a result of Key Personnel substitution.
 
## 5.0 Instructions to Offerors
### 5.1 Milestones
The following milestones are provided for this solicitation.
 
| **No.** | **Due Dates** | **Acquisition Event** |
|----------|:-------------:|------:|
| 1 | June 21, 2017 | Solicitation Released |
| 2 | June 28, 2017 by 3:00PM EST | Questions about Solicitation Due |
| 3 | July 10, 2017, 2017 by 1:00PM EST | Written Quote Submissions Due |
 
If you’d like to ask questions or comments about this RFQ, you must submit them as issues in our GitHub repository at https://github.com/18F/bpa-DOL-WHD-14-c no later than **the date above**, to allow the Government sufficient time to respond. All questions and comments will be publicly available. Please subscribe to the repository if your firm would like updates about changes and comments. Questions or comments received after the required deadline will not be answered. Any changes to this RFQ or attachments will be posted as an amendment on GSA eBuy.
 
Quotes must be valid for at least 60 calendar days after the quotation response date. Information provided in the quotation must be concise, specific, and complete.
 
During this process, Offeror(s) shall direct all written or verbal communications to the contract specialist. Communications with other officials may compromise the competitiveness of this acquisition and, for this reason, aren’t allowed.
 
Offerors are required to submit a Potential Organizational Conflict of Interest Statement (COI). If the Offeror has any potential organizational conflicts of interest, they must provide a statement describing the potential or actual COI with their quote. The information in this statement must be accurate and complete so that a CO can assess the nature of the potential conflict of interest.
 
Finally, Offerors must provide their COI responses in the appropriate field of the provided Google Form in order to be considered for award.
 
### 5.2 Written quote submission
#### 5.2.1 Technical quote
To make the process easier for potential Offerors, we have provided a Google Form for the written technical quote portion of submissions. Please note that each Offeror can enter only one submission (no alternate quotes will be allowed). **All offers must be received no later than the due date indicated above.**
 
**Written technical quotes will only be accepted via the provided Google Form.**
 
**The Google Form is available [here](https://goo.gl/forms/KzPv380xjP09VV862).**
 
#### 5.2.2 Written price quote
Offerors must submit a separate price quotation using the provided worksheet template in the eBuy system. **The price quotation must be received no later than the due date indicated above.**
 
All proposed labor rates must be consistent with the terms, conditions, and rates of your aBPA. Proposed labor rates must be fully burdened and include profit, fringe benefits, salary, indirect rates, and the GSA Contract Access Fee (CAF).
 
#### 5.3 Verbal presentations agenda
| **No.** | **AGENDA ITEM** | **MAXIMUM TIME** |
|----------|:-------------:|------:|
| 1 | Introductions | Approximately 5 minutes |
| 2 | Open Technical Session | 40 minutes | 
| 3 | Closing Remarks and Frequently Asked Questions | 5 minutes |

##### Rules
No part of these verbal presentations - for example, discussions and negotiations - constitutes a procedure in FAR Part 15. For this reason, the Government is not obligated to and does not intend to determine a competitive range, conduct discussions, and request quote revisions.

The verbal presentation consists of an unstructured question and answer session on technical factors. The entire verbal presentation will take place remotely via video chat and/or teleconference.

Offerors will not be able to use or present slides, graphs, charts or any other written presentation materials, including handouts.

##### Content
During the Open Technical Session, the Offeror will respond to Government’s questions related to the technical aspects of the Offeror’s proposal.
 
Introductions will be used solely for introducing team member’s names and roles on both the Government and vendor teams. Time for introductions will not be allocated to business development purposes.


Although the technical factors are identified in the RFQ, the core questions are not listed there. Offerors must be prepared to answer questions about the technical aspects of their respective quotes. The goal of these presentations is to assess the technical abilities of the proposed Key Personnel and further elaborate on their proposed technical approach to accomplish the objectives of this task.

This part of the verbal presentations will not exceed 40 minutes. The Contracting Officer will strictly enforce this time limit on all presentations. There will be no follow-up session for further questions after this part of the presentation.
 
The session will conclude with closing remarks and responses to frequently asked questions for Offerors.

##### Presentation location
Verbal Presentations will take place via video chat, though audio may be substituted as needed. The Government will coordinate and set up the meeting space accordingly (providing dial-in information or links using a tool such as Zoom or Appear.in).

##### Presentation date and time
The Government will schedule the date and time of the verbal presentations with each Offeror after the solicitation closing date and receiving each Offeror’s quote submission. The Government reserves the right to reschedule any Offeror’s verbal presentations date at the discretion of the contracting officer.
 
##### Presentation participants
**Proposed Key Personnel must participate in the verbal presentation. Otherwise, the Offeror will be considered non-responsive and excluded from further consideration.**
 
Offerors may include as many participants as are necessary. Offerors should note that the Government will be asking technical questions during the verbal presentation, so non-technical personnel may not need to attend.
 
All proposed Key Personnel currently employed by the Offeror or its teaming partners must attend the session - the Government is most interested in hearing from staff who will have a direct role in completing the task.
 
After the presentations, vendors must email the meeting organizers the names of everyone who attended.
 
## 6.0 Evaluation
### 6.1 Technical Evaluation 
 
The following will be used to evaluate technical quotes:
 
Composition of the team

Key personnel proposed have demonstrated experience in:
- Building software using the technical languages outlined in section 2.2
- Developing software in the open
- Using a strong user-centered product development technical approach
- Their ability to work in using Scrum or another Agile framework
- The ability to empathize and work with different personalities
 
Vendor Experience/Skill

Vendor’s proposal includes:
- At least 2 but no more than 3 projects involving the languages outlined in section 2.2 as well as the Key Personnel being put forward. If one repo has one language and another repo has another language, that’s fine as well. Meaning, each repo does not need to include everything outlined in 2.2, but projects submitted should show mastery in all those things.
 
### 6.2 Price evaluation
A reasonable price that is consistent with industry standards and the vendor’s proposed approach, but not necessarily the lowest. We intend to pick the vendor that has the best technical factors rather than the lowest price. If we have to choose between the two factors, technical factors will significantly outweigh price.
 
### 6.3 Evaluation process
We will review the responses to the questions in the Technical Quote to ensure they demonstrate an understanding of the requirements outlined in the PWS, particularly section 2.2 (the ability to work with the existing tech stack here will be important), and the strength of their proposed user-research and Agile and development practices.
 
We will also review the vendor’s website, company and personnel GitHub profiles, example projects, and resumes for proposed personnel for strength of experience in relevant projects.
 
We will review of Google Form responses for the strength and feasibility of the proposed technical approach, the level of knowledge in the specified technical stack in section 2.2 that is possessed by the personnel put forward by the vendor and within the repositories provided as examples, and the ability of the team to get along with one another and the Government’s team.
 
We will assess the verbal presentation to validate the technical approach put forward in the written presentation and verify how the proposed team will accomplish it. The verbal presentation will also evaluate how effectively the proposed team communicates and whether there are any intangibles (such as corporate culture and individual personality factors) about the team that may not come out in a written document.
 
## 7.0 Basis for award
We intend to select a vendor that puts forward the most sensible (“best”) technical approach, Key Personnel that can fulfill the objectives, a reasonable price (not necessarily the lowest), the ability to not only work the way we want (open source, user-centered design, Scrum, etc.) and work well together, but also the ability to work well with the particular personalities that exist on the Government’s team (based on interactions during the verbal presentation).
 
## 8.0 Awarded task
### 8.1 Task details
#### 8.1.1 Type of contract
**This task order is a Firm Fixed Price for the services offered on the schedule priced at hourly rates.**
 
Note:  The Government intends to use all of the hours proposed by the successful offeror during the period of performance.  If it becomes clear during performance that there is a discrepancy between the hours awarded and those needed to complete the work, the Government may, at its option, require delivery of any remaining hours on additional user stories within the scope of the work described in this PWS.  The Government may also modify the order to extend the period of performance to allow for delivery of the hours awarded, or may end the work and modify the order to reduce the total number of hours to reflect those delivered.  In no event will the vendor be compensated for undelivered hours.
 
### 8.1.2 Period, place, and hours of performance
The period of performance is four months.
 
The primary place of performance will be at the Contractor’s facility.
 
Business core hours shall be 1000 to 1800 EST, Monday through Friday, on Government-scheduled work days. The Contractor may set their own work hours except that the Contractor shall be available for technical contact by the Government between the hours of 1000 and 1800 EST on Government work days.
 
#### 8.1.3 Points of contact
The following Points of Contact (POC) applicable to this order will be identified during the Vendor Kickoff meeting.
 
- Contracting Officer (CO)
- Contract Specialist (CS)
- Contracting Officer Representative (COR)
- Technical Point of Contact (TPOC)
- Product Owner
 
### 8.2 Roles and responsibilities
Please refer to the roles and responsibilities listed on our [BPA Roles and Responsibilities Page](https://ads.18f.gov/roles-and-responsibilities/)
 
## 9.0 Additional Provisions/Clauses Applicable to this Order
 
### 9.1 TTS Transparency Policy
Vendors are advised that TTS will publish documents associated with this requirement on a publicly-available website, including any Requests for Quotation (including amendments), Question and Answer exchanges with vendors (source-identifying information removed), and other relevant information that is not confidential or proprietary in nature or source selection sensitive information that would otherwise implicate procurement integrity concerns.
 
Upon award, TTS will publish the total price of the selected proposal and certain non-source-identifying data (for example, the number of offers, the mean price, median, and standard deviation of price). During the performance of this call order, TTS will similarly publish source code, data related to project management (for example, user stories, milestones, and performance metrics), and top-line spending data.
 
### 9.2 Additional FAR Provisions/Clauses Applicable to this Order
 
FAR 52.203-18 Prohibition on Contracting with Entities that Require Certain Internal Confidentiality Agreements or Statements-Representation (JAN 2017)
 
FAR 52.203-19 Prohibition on Requiring Certain Internal Confidentiality Agreements or Statements (JAN 2017)
 
## Attachments to this Solicitation
 
1.  Pricing Template
2.  Proposed Quality Assurance Surveillance Plan (QASP)
3.  Non-Disclosure Agreement
4.  SF1449
