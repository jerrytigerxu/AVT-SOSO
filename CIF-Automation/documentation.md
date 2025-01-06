## PAC phase
- ~~Form refinement (data validation, default values, required fields, and styling)~~
  - Make some fields (like phone number and email) mandatory
- Have an email automatically be sent to CS that also has an attachment of the form results (using Salesforce Flow with Apex)
  - Workflow: When the form is filled out and submitted, an email is automatically sent to the prospect -> Then CS could notify the Sales team of the generated Prospect so they can review it and convert to an Opportunity -> The Flow would trigger when the Prospect is created -> leading to the generation of an email, then the email would be sent
  - Present to the marketing team for feedback (then refine everything in preparation to show to Johnny and Joanna)
  - Testing (refine the email template and include a direct link to the Prospect in Salesforce)
