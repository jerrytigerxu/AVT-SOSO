
## ~~Designing the Web-to-lead form (content and style) (12/3)~~

- The flow: when a new Prospect record is created through the Web-to-Lead HTML form, a new Opportunity record should be created with some default values (simply convert the Prospect into an Opportunity) 
Conversion functionality (Prospect to Opportunity): converting a Prospect to an Opportunity makes the Prospect disappear
- **12/9/24** - made a decision to hold off on actually creating a Salesforce flow for now -> because it's not always obvious how to actually handle the Prospect information (creating new Contact or Company or Opportunity based upon the new Prospect), it might be best to leave that decision-making component to the SOS people | demonstrate the POC to MM and Mimi first before doing anything else



## (suspended) Building and testing the Salesforce flow (triggered when a new Prospect record is created through the Web-to-Lead HTML form) (12/6, 9)
- The flow: when a new Prospect record is created through the Web-to-Lead HTML form, a new Opportunity record should be created with some default values 

## (suspended) Embedding of form into the website (hidden link) and refinement (data validation, default values, and optimization) (12/10)
- Make sure the fields of the Prospect and Opportunity records are all accurate and mapped properly 
- Add reCAPTCHA verification functionality (to avoid spam)
- Make the form look much nicer
