# BC Petroleum and Natural Gas Title Credential (Tenure)

## 1. Primary Document

### 1.1. Introduction
This document articulates the title credential for natural gas tenure in British Columbia as per the Petroleum and Natural Gas Act.

B.C. Regulation: Petroleum and Natural Gas Act [https://www.bclaws.gov.bc.ca/civix/document/id/complete/statreg/96361_01]


This governance document has been developed in accordance with the ToIP’s Governance Metamodel Specification created by the Governance Stack Working Group (GSWG) as the template for this framework.

### 1.2. Terminology and Notation

[Glossary - General Trust Over IP Terms](https://trustoverip.github.io/toip/glossary)

### 1.3. Localization

The standard language for this governing framework (GF) is English.
 
### 1.4. Governing Authority

Tenure and Resource Stewardship Branch is the governing authority and party legally responsible for developing, maintaining and implementing the Governance Framework. This is the only issuing party. 
The contact for petitioners and relying parties of this GF is:
* 	Name ___________
* 	Title ____________
* 	Organization ___________
* 	Email ____________

### 1.5. Administering Authority

TBD

### 1.6. Purpose

This Petroleum and Natural Gas Title Credential must be issued by __________________. The structure for the credential contains all information included in a British Columbia Land Title Document. This title and governance will allow a more trustworthy ecosystem. This will be built under this governance framework. The purpose of this governance framework is to outline all rules associated with governance, issuance, verification, and revocation of a Title Credential.  

### 1.7. Scope

The GF only covers the Title Credential

### 1.8. Objectives

TBD

### 1.9. Principles

TBD

### 1.10. General Requirements

TBD

### 1.11. Revisions

TBD

### 1.12. Extensions

TBD

### 1.13. Schedule of Controlled Documents



## 2. Controlled Documents

### 2.1. Glossary

TBD

### 2.2. Risk Assessment

TBD

### 2.3. Trust Assurance and Certification

TBD

### 2.4. Governance Requirements

TBD

### 2.5. Business Requirements

TBD

### 2.6. Technical Requirements

#### 2.6.1 Schema Definition

This schema definition follows the AnonCreds specification (https://anoncreds-wg.github.io/anoncreds-spec/)

Attribute | Format | Rules | Notes	
--- | --- | --- | --- |
title_number | String  | not NULL | Petroleum and Natural Gas Act Section 50 Leases and Their Rights
title_type | String | not NULL | Lease, Permit, Drilling Licence, Underground Storage Lease
date-issue | String | not NULL| Petroleum and Natural Gas Act Section 47 Term and Renewal
effective_date | String | not NULL | Petroleum and Natural Gas Act Section 47 Term and Renewal
term | String | not NULL | Petroleum and Natural Gas Act Section 47 Term and Renewal
date_expiry | String | not Null | Effective date plus term Petroleum and Natural Gas Act section 58 (3) outlines Expiration and Continuation of Leases.
containing | String | not Null | Petroleum and Natural Gas Act section 65 outlines Spacing Areas "For the purposes of this act and the Oil and Gas activities Act, British Columbia, except where insufficient area exists adjacent to its boundaries, is divided into normal spacing areas for petroleum and natural gas wells."
lessee| String | not Null | Petroleum and Natural Gas Act Section 50 (1) and (2) outlines Leasee (s) and their rights. Section 1 outlines lessee as "a person in whose name a lease is recorded in the divisions records"
percent_interest | String | not Null | As defined in Petroleum and Natural Gas Act Section 1 outlining the definition of "interest"
tract_id | String | not Null | number ID
tract_location | String | not Null | Petroleum and Natural Gas Act Section 1 defines "location means the land described in a permit, licence or lease"
tract_rights | String | not Null | Petroleum and Natural Gas Act Section 38 describes "Rights Conferred by Permit". this includes "the holder of a permit has the exclusive right to apply under the Oil and Gas Activities Act to do exploratory drilling for petroleum or natural gas or both owned by the government and within the boundaries of the location of the permit"
tract_notes | String | not Null | textbox
caveats | String | not Null | textbox



#### 2.6.2 Credential Implementation

### 2.7. Information Trust Requirements

TBD

### 2.8. Inclusion, Equitability, and Accessibility Requirements

TBD

### 2.9. Legal Agreements

TBD

## End of  



