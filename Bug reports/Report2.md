## Bug Report #1
## Title: Some Buttons on the Filters Panel Are Inactive

## Environment:
 - OS: MS Windows
 - Release: x.xxx.xxx

## Description:
Several buttons on the Filters panel remain inactive. To activate them, the user must click on the axis indicator. However, adjacent buttons are active without this extra action.

## Steps to Reproduce:
1. Open the application.
2. Load the file: НСО_ССД_2.pkg → XBRL_111111111111111_ep_SSDNEMED_10rd_sr_q_20210630.xml.
3. Select the report.
4. In the Filters panel, expand the axis hierarchy by clicking the triangle next to the axis title.
5. Unmark the axis.
6. Click the "Heart" button.

## Expected Result:
All buttons, including the "Heart" button, should be active and clickable.
## Actual Result:
 - Some buttons, including the "Heart" button, remain inactive.
 - It is impossible to save settings for the entire entry point.
 - Adjacent buttons are active.
 - To activate the inactive buttons, an additional click on the axis indicator is required.


