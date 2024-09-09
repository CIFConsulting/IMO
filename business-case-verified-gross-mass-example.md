# Verified Gross Mass (VGM) - Business Case

## Description

The consequences of misdeclaring the gross mass of a packed container can be far-reaching.  Should a discrepancy between the declared gross mass and the actual gross mass of a packed container go unnoticed, it could have an adverse impact on the safety of the ship, seafarers and shore-side workers, by leading to incorrect vessel stowage decisions and potentially collapsed container stacks or loss of containers overboard.

The aforementioned SOLAS amendments introduce two main new requirements:

1. The shipper is responsible for providing the verified weight by stating it in the shipping document and submitting it to the master or his representative and to the terminal representative sufficiently in advance to be used in the preparation of the ship stowage plan;
2. the verified gross mass is a condition for loading a packed container onto a ship.

## IMO Convention or Articles  

The SOLAS amendments, Chapter VI, Part A, Regulation 2, concerning Verified Gross Mass of containers (VGM) became effective in July 2016, details can be found at https://www.imo.org/en/OurWork/Safety/Pages/Verification-of-the-gross-mass.aspx

## Interactions 

- [X] B2B
  
## Sequence Diagram

A high level sequence diagram for the VGM process is as follows

<img width="1449" alt="Screenshot 2024-09-09 at 19 51 56" src="https://github.com/user-attachments/assets/cfed158c-5b71-4064-b034-3440f54d4c2e">

*Note: Taken from DCSA Industry Blueprint - for illustration only, IMO sequence diagram would show swimlane for shipper, carrier and maybe terminal*

## IMO Dataset



## Implementable Message Standards 

### UNECE
SMDG developed and published the VERMAS message using UN/EDIFACT which serves the purpose of VGM reporting.  Message implementation guides and further details of the standard can be found at;
* https://service.unece.org/trade/untdid/d23a/trmd/vermas_c.htm
* https://smdg.org/working-groups/vermas-vgm/
