---
layout: page
title: Data Specification for PoC
---



  
  <div class="feature">
   <h3>Proof of Concept (PoC) fields for clinician demographics:</h3> 
   Required Fields for clinician demographics:
   <br/>
 <br/>
   
  The following data elements are core data needs for this proof of concept.
 
<br/>
 <br/>

 
  </div>



| Line | Required | Column | Description |
|----|---------|--------|----------------------------------------|
| 1 | Required | Last Name| Last Name   |   
| 2 | Required | First Name| First Name   |   
| 3 | Required | Middle Name| Middle Name |   
| 4 | Required | Suffix| Suffix         |   
| 5 | Required | TaxIDindividual | Tax ID number associated with the provider (individual practitioner) |
| 6 | Required | TaxIDinstitutionTax ID number associated with the provider (institution) For employers, including state and local government agencies and non-profit organizations, TIN is the IRS issued employer identification number (EIN). EINs are public information per <a href="https://apps.fcc.gov/coresWeb/html/tin.html">FCC</a> |  
| 7 | Required | NPI| NPI |    
| 8 | Required | HCPT Spec Code| Health Care Provider Taxonomy- Industry standard specialty codes (for complete code list   <a href= "http://www.wpc-edi.com/reference/codelists/healthcare/health-care-provider-taxonomy-code-set/"> see </a> ) |   
| 9 | Required | isAcceptingPatients| The provider is accepting the patients for the payer products: only existing patients, family members of existing patients, new patients, other per Provider/Prayer  |    
| 10 | Required | PayerNtwkEffDate| Date - the provider joined this network. (at the group level for POC purposes) |    
| 11 | Required | PayerNtwkExpireDate| Date the provider left this network. (at the group level for POC purposes) |    
| 12 | Required | Site/Location EffectiveDate| Provider's start date at this location |    
| 13 | Required | Site/LocationTerminationDate| Provider's end date at this location  |    
| 14 | Required | PracticeStreet1 | Provider's place of medical service, practice address street line 1     |    
| 15 | Required | PracticeStreet2 | Practice address street line 2   |    
| 16 | Required | PracticeCity| Practice city |    
| 17 | Required | PracticeState| Practice state |    
| 18 | Required | PracticeZip| PracticeZip   |    
| 19 | Required | PracticeTelephone | Practice phone (can he have multiple types by location, i.e. appointment, business line)   |    


<br/>
<div class="feature">
                           
        The following additional data if available, may be collected for this proof of concept: 
      <br/>
      <br/>
</div>

| Line | Data Needed | Column | Description |
|----|---------|--------|----------------------------------------|
| 20| High | PrimaryContactName| Practice contact name   |
| 21| High | PrimaryContactFax  | Fax   |   
| 22| High | ProviderRetireDate| Date of the provider Retired |   
| 23| High | ProviderDecreaseDate| Date of the provider decreased         |   
| 24| High | ProviderProficiencyEnglish| Provider's proficiency in the English language   |   
| 25| High | ProviderOtherLanguages| Languages spoken by the provider (other than English)   |   
| 26| High | SiteProficiencyEnglish| Staff proficiency in the English language. |   


<br/>


