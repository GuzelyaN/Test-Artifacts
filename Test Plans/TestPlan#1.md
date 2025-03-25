# Internal Testing Program for the Software Suite: Editor XBRL
**Release**: x.xxx.xxx from xx.xx.xxxx  

## Document Specification  
- **Current Version**: 1.0  
- **Responsible Person**: Nikolayeva G.R.  
- **Creation Date**: xx.xx.xxxx  
- **Last Modified Date**:  

## Revision History
| Version | Date       | Author        | Comment |  
|---------|------------|---------------|---------|  
| 1.0     | xx.xx.xxxx | Nikolayeva G.R. |         |

## Approvals
| Name     | Organization | Position | Signature | Date       |  
|----------|--------------|----------|-----------|------------|  
| xxxxxxx  | xx           | xx       |           |            |  
| xxxxxxx  | xx           | xx       |           |            |  
| xxxxxxx  | xx           | xx       |           |            |  
| xxxxxxx  | xx           | xx       |           |            |

## Table of Contents  
1. [Introduction](#introduction)  
2. [Conditions and Limitations](#conditions-and-limitations)  
3. [Types of Testing](#types-of-testing)  
4. [Testing Environment](#testing-environment)  
5. [Metrics](#metrics)  
6. [Documentation of the Testing Process](#documentation-of-the-testing-process)  
7. [Tooling](#tooling)

---

## 1. Introduction
The internal testing program represents the recommended approach for testing the Questionnaire Editor XBRL software suite (hereafter referred to as the XBRL Questionnaire software). The main objectives of the internal testing program are:
- To outline the testing techniques to be employed.
- To define the criteria to determine the completion of testing:
  - Compliance of the updated Questionnaire Editor XBRL software with the stated functional requirements.
  - Absence of critical defects in the tested features that would prevent the release of the XBRL Questionnaire software for production use (criticality: +1/1).

## 2. Conditions and Limitations
- **Planned testing period**: xx.xx.xxxx to xx.xx.xxxx.
- If a critical defect is identified requiring a new release, the testing period must be extended. Changes to the comprehensive testing deadlines must be re-approved with the Regional Center for Testing and Quality Control "Saint Petersburg" (hereafter RCTQC) within the Northwestern Main Administration of the Central Bank of the Russian Federation.
- Testing is conducted under user permissions for which the tested features of the XBRL Questionnaire software should be available during regular operation.
- Testing is performed using synthetic test data.
- **Not conducted**:
  - Integration testing.
  - Automated regression testing.
  - Load testing.
  - Documentation testing.
  - Manual regression testing.

## 3. Types of Testing

### Testing of New Functionality  
**Objective**: Validate the updated XBRL Questionnaire software's compliance with functional requirements, specifically:
- Issues identified during previous releases' testing and operation, listed for resolution in the current release:
  - **XBRLRCT-265(242)**: "Incorrect display of the entry period when editing a package."
  - **XBRLRCT-268(245)**: "After loading a report with the measurement unit 'shares' declared, the 'pure' measurement unit is not declared in the exported file."
  - **XBRLRCT-269(246)**: "Template codes for Section 8 are missing in the exported visualization forms for taxonomy 4.2, entry point ep_nso_uk_q_y_30rd."
  - **XBRLRCT-270(247)**: "For percentItemType indicators in XBRL Reports, unit = PURE and attribute unitRef = PURE are not declared."
  - **XBRLRCT-272(239)**: "Errors with the 'pure' measurement unit occur when loading a report."

### Manual Regression Testing  
Manual regression testing is not performed.

### Security Protection Verification  
Verification of the installer and archiver against antivirus protection from the "Kaspersky" family:
- Kaspersky Endpoint Security 11 for Windows.

## 4. Testing Environment  
**Software Version**: XBRL Questionnaire Editor - Release x.xxx.xxx.

### Testing Environment for New Functionality and Manual Regression Testing:
The testing setup for the XBRL Questionnaire software includes the following components:
- Autonomous workstations located at RCTQC, not connected to the local network of the Northwestern Main Administration of the Bank of Russia.
- Workstations in the secure information environment of the internal bank information network within the Northwestern Main Administration of the Bank of Russia.
- Workstations connected to the internet, located in the software testing environment of the internet security network.

The structural diagram of the XBRL Questionnaire software testing setup is presented in **Figure 1**.

## 5. Metrics  
To monitor the progress of testing, the following metrics are implemented:
- Number of testing iterations.
- Number of defects registered for the release.
- Presence of critical defects preventing the release for production use (criticality: +1/1).

## 6. Documentation of the Testing Process  
- Daily status reports on testing progress are not provided. When a critical defect is identified, information is sent in working order to the Release Manager and IT Leader.
- Upon completion of testing, a **"Comprehensive Testing Report"** is prepared and sent to the IT Leader and Release Manager.

## 7. Tooling  
- **JIRA (AS PURR)**: Bug tracking system.
- **Confluence (JIRA)**: Information space for publishing documentation on the testing process.
- **Adaptavist**: Tool for developing and executing test cases.

