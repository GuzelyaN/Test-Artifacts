# Internal Testing Program for the Software Suite: ...
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
The internal testing program represents the recommended approach for testing ...... software suite. The main objectives of the internal testing program are:
- To outline the testing techniques to be employed.
- To define the criteria to determine the completion of testing:
  - Compliance of the updated ..... software with the stated functional requirements.
  - Absence of critical defects in the tested features that would prevent the release of the ....... software for production use (criticality: +1/1).

## 2. Conditions and Limitations
- **Planned testing period**: xx.xx.xxxx to xx.xx.xxxx.
- If a critical defect is identified requiring a new release, the testing period must be extended. 
- Testing is conducted under user permissions for which the tested features of the ..... software should be available during regular operation.
- Testing is performed using synthetic test data.
- **Not conducted**:
  - Integration testing.
  - Automated regression testing.
  - Load testing.
  - Documentation testing.
  - Manual regression testing.

## 3. Types of Testing

### Testing of New Functionality  
**Objective**: Validate the updated ...... software's compliance with functional requirements, specifically:
- Issues identified during previous releases' testing and operation, listed for resolution in the current release:
  - **<ID>**: "<Title>"
  - **<ID>**: "<Title>"
  - 
 ### Manual Regression Testing  
Manual regression testing is not performed.

### Security Protection Verification  
Verification of the installer and archiver against antivirus protection ......:
- ...........

## 4. Testing Environment  
**Software Version**: .......- Release x.xxx.xxx.

### Testing Environment for New Functionality and Manual Regression Testing:
The testing setup for .......... includes the following components:
- ...........
The structural diagram of .......... software testing setup is presented in **Figure 1**.

## 5. Metrics  
To monitor the progress of testing, the following metrics are implemented:
- Number of testing iterations.
- Number of defects registered for the release.
- Presence of critical defects preventing the release for production use (criticality: +1/1).

## 6. Documentation of the Testing Process  
- Daily status reports on testing progress are not provided. When a critical defect is identified, information is sent in working order to the Release Manager and IT Leader.
- Upon completion of testing, a **"Comprehensive Testing Report"** is prepared and sent to the IT Leader and Release Manager.

## 7. Tooling  
- **JIRA**: Bug tracking system.
- **Confluence**: Information space for publishing documentation on the testing process.
- **Adaptavist**: Tool for developing and executing test cases.

