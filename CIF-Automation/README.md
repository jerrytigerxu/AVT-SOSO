## Overview
- The purpose of this project is to reduce manual labor and to cut down potential errors in CRUD operations for Salesforce - instead of manually copying the information from the CIF form into Salesforce, we can use Salesforce's Web-to-lead functionality to directly create Salesforce Prospects which can then be converted to update Opportunities

## Phases (12/3 - 12/30)
- ~~Convince the sales support team to shift to using an online form and leverage SF Web-to-Lead to save a lot of time and energy (for both parties)~~
- ~~[**Test Phase**](https://github.com/jerrytigerxu/AVT-SOSO/blob/main/CIF-Automation/Test-Phase.md) (12/3-10)~~
  - ~~Designing the Web-to-lead form (content and style)~~
  - ~~(suspended) Building and testing the Salesforce flow (triggered when a new Prospect record is created through the Web-to-Lead HTML form)~~
- ~~**Proof-of-concept phase (to give a demo to MM and Mimi | talk about whether or not we need to directly automate the conversion to Prospect or leave the SOS team to handle that)** (12/10)~~
  - ~~Clarification: we aren't trying to create new Opportunities, but rather we are simply updating existing Opportunities (specifically with the "Sales Fulfillment" information) after automatically generating the prospects from the CIF form and then manually converting them (pass the eye test) to existing Opportunities => to do this, you'll need to add all of the sales fulfillment information into the Prospect object so the fields can be mapped and transferred into the Opportunity objects~~ 
- **Production Phase** (12/10-12/20)
  - ~~Make adjustments based on clarification~~
  - ~~Demonstrate to Morgan and Mimi what the raw version of this looks like (12/19)~~
    - ~~Recorded simple demo for Morgan and Mimi~~
  - ~~Embedding of form into the website (hidden link) (12/19)~~
    - ~~Created private page on AVT site called "CIF Automation Test" with the embedded HTML Form~~
- **PAC Phase** (12/23-30)
  - Form refinement (data validation, default values, required fields, and optimization)
  - Ensure the form is accessible and optimized for various devices
  - Consider incorporating features like conditional logic, progress bars, and a "save and continue later" option
  - Research ways to save the form results as PDFs (so they can be filed away in OneDrive) (maybe after filling them out they get automatically saved somewhere)
    

    


