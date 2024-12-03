## Documentation
- 11/13/24 Brought up the idea of using SF Web-to-lead instead of having a PDF for the CIF to MM, and she really liked the idea (especially since the CIF idea had only been brought up in summer 2024 - so really recently)
- 11/20/24 I’m able to get the form to update specific fields when the records are created - but currently I’m unable to create new Opportunity records through the Flow (some part of the Flow isn’t working and I’m not sure what) → maybe it’s because of the required fields for Opportunity records

## Concrete steps

- ~~Convince the sales support team to shift to using an online form and leverage SF Web-to-Lead to save a lot of time and energy (for both parties)~~
    
- Test Phase (all four steps)
    
    - ~~Design the form content and style~~
        
    - ~~Test the results of the HTML form (does it update Prospects)~~
        
    - Map the result fields to the corresponding fields in the “Opportunity” object page (**using Flow**) → convert the generated Prospect into an Opportunity directly
        
    - Embed the form into the website (hidden link)
        
    - Refinement (data integrity - default values and validation rules to ensure data accuracy)
        
- Give a demo of the test workflow (“proof of concept) to MM and Mimi
    
- Production Phase
    
- PAC Phase
    
    - Ensure the form is accessible and optimized for various devices
        
    - Consider incorporating features like conditional logic, progress bars, and a “save and continue later” option
        
    - Research ways to save the form results as pdfs (so they can be filed away in OneDrive)

## Background

 **Why SF Web-to-Lead**

- No more manual entry or scattered information!
    
- Simplified workflow: capture essential PO details directly from customers and channel them straight into SF!
    

---

Only four steps for implementation:

1. Creating a user-friendly form (fields and styling)
    
2. Integration into AVT website (embedding of form)
    
3. Mapping of results to SF records (opportunities)
    
4. Refinement (specifically for data integrity)

- CIF (customer information form)
    
    - The sales support team sends a CIF to the companies, and then the companies fill out the information
        
    - Automate updating the Salesforce records based on the CIF
        

---

## Questions to ask

- When the companies fill out the CIF, where does the finished form go (within SF)?
    
    - _Company page > files_
        
- What file type is the finished CIF in usually?
    
    - _PDF_
        
- What does a sample of the completed CIF look like?
    
    - _See attachment_
        
- Is there a standardized template?
    
    - _Yes_
        
- What are the fields? Are all of the fields already in the SF Company object?
    
    - _The fields are already set on the opportunity page_
        
- How often is the process usually carried out?
    
    - _close to the PO stage, or if Sales want to send it as a talking point, there can be many different ways_
