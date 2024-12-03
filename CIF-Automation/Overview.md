## Documentation
- 11/13/24 Brought up the idea of using SF Web-to-lead instead of having a PDF for the CIF to MM, and she really liked the idea (especially since the CIF idea had only been brought up in summer 2024 - so really recently)
- 11/20/24 I’m able to get the form to update specific fields when the records are created - but currently I’m unable to create new Opportunity records through the Flow (some part of the Flow isn’t working and I’m not sure what) → maybe it’s because of the required fields for Opportunity records

---

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
