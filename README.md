<h1>Claims Management System</h1>

<h2>Description</h2>
The CMS was developed on behalf of the GDHS. The purpose of the system was to capture and track claims projects within the department. The system was outsourced and privately developed by a third-party vendor. It operated on a Java and Oracle 9i platform, running on a Microsoft operating system.

GDHS subsequently submitted a request for assistance to SITA regarding the upgrade of the CMS. This entailed upgrading the existing Java and Oracle platforms to the latest versions. Upon receipt of the request, SITA assembled a team to assess the GDHS Claims Management System environment, and the following recommendations were made:

  - Upgrade the system – This would have meant that GDHS proceeded with the platform upgrade as intended, leading to the same difficulties being experienced, requiring a significant amount of resource time and 
    incurring exorbitant costs.
  - Acquisition of a commercial off-the-shelf system (COTS) – This option would still have required additional customization to meet the department’s unique requirements.
   -Complete code rewrite – This option would have modernized the application and transformed it to open standards, making it easier to develop, implement, and maintain.

The following business problems were identified within the GDHS Claims Management environment:

  - Inflexible solution – The inability of the system to respond to the latest requirements. The system’s inflexibility led to delays in service delivery, as new requirements had to be accommodated through 
    manual workarounds.
  - Process rigidity – The inability to enhance the code due to extensive configuration requirements. This resulted in a considerable increase in the total cost of ownership, requiring frequent reinvestment.
  - Data fragmentation – The system was incompatible with the latest tools needed to enhance and fix reports. This led to tedious efforts to gather data for decision-making reports, contributing to delays in 
    service delivery.
  - Legacy platform – The technology was outdated, as it ran on an old Microsoft Windows 2000 Server operating system and an incompatible Oracle 9i Application Server on a Windows 2003 Server. Correcting these 
    outdated and incompatible platforms would have led to significant and frequent increases in the cost of technology enhancements.
  - Inefficient system development method – Most development on the CMS was done using RAD, which resulted in:
    - A lack of system documentation; and
    - System errors.
  - Unsupported system – The support contract for the CMS expired and was not renewed.

The complete CMS code rewrite option provided a quicker go-to-market solution for the department and offered the following opportunities:

  - Agile solution – The ability to respond to process enhancements faster.
  - Flexible system – The ability to add new products and categories of claims more easily.

The business objectives included the following:

  - To optimize the existing CMS functionality.
  - To implement a solution that was scalable to accommodate the future growth of the organization’s business.
  - To implement a solution that accurately administered projects, contracts, quality assurance, and the management of claims.
  - To define a solution that was adaptable to accommodate user requirement changes and future enhancements.
  - To identify gaps for possible enhancements.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Old CMS</b>
  - Language: Java
  - Database: Oracle 9i
    
- <b>New CMS</b>
  - Language: Angular CLI
  - Database: PostgreSQL

<h2>Environments Used </h2>

- <b>Old CMS</b>
  - Microsoft Windows
    
- <b>New CMS</b>
  - Linux

<h2>Software Tester Responsibilities</h2>

- <b>Requirement Analysis</b>
  - Understand and analyze software requirements from business analysts, developers, and stakeholders.
  - Identify testable and non-testable requirements.
  - Clarify any ambiguities with the development team.
  - reate a Requirement Traceability Matrix (RTM) to track test cases against requirements.

- <b>Test Planning</b>
  - Develop a Test Plan outlining objectives, scope, resources, schedules, and risks.
  - Select testing techniques (manual vs. automation).
  - Identify testing tools and environments.
  - Define entry and exit criteria for each test phase.
 
- <b>Test Case Design & Preparation</b>
  - Write detailed and structured test cases covering functional, non-functional, regression, and exploratory testing.
  - Develop test data for different test scenarios (valid, invalid, boundary conditions).
  - Prioritize test cases based on risk and impact.
 
- <b>Test Environment Setup</b>
  - Coordinate with DevOps or system admins to configure the test environment.
  - Ensure required software, databases, and dependencies are correctly installed.
  - Verify network and access permissions.

- <b>Test Execution</b>
  - Perform different types of testing (Functional, Regression, Smoke, Sanity, Performance, Security, etc.).
  - Log defects/bugs in a bug-tracking tool (e.g., Jira, Bugzilla).
  - Reproduce and investigate reported defects.
  - Retest fixed bugs to ensure they are resolved.

- <b>Defect Management</b>
  - Track and document defects with detailed steps, screenshots, and logs.
  - Work closely with developers to help them understand and resolve issues.
  - Verify bug fixes and ensure no new defects are introduced. 
    
- <b>Test Reporting & Documentation</b>
  - Prepare Test Summary Reports detailing executed test cases, passed/failed cases, defect statistics, and overall software quality.
  - Provide detailed logs and screenshots for failed test cases.
  - Maintain test artifacts (test cases, plans, reports) for future reference.

- <b>UAT (User Acceptance Testing) Support</b>
  - Assist business users in conducting User Acceptance Testing (UAT).
  - Provide guidance on test case execution.
  - Document and track feedback from UAT.
