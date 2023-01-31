# BC Petroleum and Natural Gas Title Credential

## Introduction
This document articulates the title credential for natural gas tenure in British Columbia as per the Petroleum and Natural Gas Act.

B.C. Regulation: Petroleum and Natural Gas Act [https://www.bclaws.gov.bc.ca/civix/document/id/complete/statreg/96361_01]


This governance document has been developed in accordance with the ToIP’s Governance Metamodel Specification created by the Governance Stack Working Group (GSWG) as the template for this framework.

## Terminology and Notation

[Glossary - General Trust Over IP Terms](https://trustoverip.github.io/toip/glossary)

## Localization

1.	The standard language for this governing framework is American English.
 
## Governing Authority

___________ is the governing authority and party legally responsible for developing, maintaining and implementing the Governance Framework.
The contact for petitioners and relying parties of this GF is:
* 	Name ___________
* 	Title ____________
* 	Organization ___________
* 	Email ____________

## Purpose

This Petroleum and Natural Gas Title Credential must be issued by __________________. The structure for the credential contains all information included in a British Columbia Land Title Document. This title and governance will allow a more trustworthy ecosystem. This will be built under this governance framework. The purpose of this governance framework is to outline all rules associated with governance, issuance, verification, and revocation of a Title Credential.  

## Scope

The GF only covers the Title Credential

## Schema Definition

This schema definition follows the AnonCreds specification (https://anoncreds-wg.github.io/anoncreds-spec/)

Attribute | Format | Rules | Notes	
--- | --- | --- | --- |
title_number | String  | not NULL | ---
title_type | String | not NULL | Lease, Permit, Drilling Licence, Underground Storage Lease
date_of_issue | String | not NULL| ---
effective_date | String | not NULL | ---
term | String | not NULL | ---
date_of_expiry | String | not Null | Effective date plus term
containing | String | not Null | ---
lessee (s) | String | not Null | ---
percent_interest | String | not Null | ---
tract | String | not Null | ---
tract_location | String | not Null | ---
tract_rights | String | not Null | ---
tract_notes | String | not Null | ---
caveats | String | not Null | ---



## Credential Implementation



