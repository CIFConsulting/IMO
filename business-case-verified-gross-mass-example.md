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

| Data Number	| Data Element	| Definition |
| --- | --- | --- |
| IMO0498 | Equipment type and size, coded | Code specifying the characteristics, i.e. size and type of transport equipment. |
| IMO0499	| Gross mass verification number | The identification number of verification for the verified gross mass. |
| IMO0500	| Gross mass verified date	| Date and time of determining the verified gross mass of container.|
| IMO0501	| Gross mass verifying country, coded |	The code of the country where the verified gross mass is determined.|
| IMO0502	| Gross mass verifying party identifier	| The identifier of the gross mass verifying party. |
| IMO0503	| Gross mass verifying party name	| The name of the responsible shipper or third party verifying the gross mass.|
| IMO0504	| Gross mass verifying person family name	| The family name of person in charge of verifying the gross mass authorized by the shipper.|
| IMO0505	| VGM measuring method, coded	| A code representing the Gross Mass Verifying Method.|
| IMO0506	| Verified Gross Mass	| The Verified Gross Mass of the container (VGM).|
| IMO0507	| VGM document  issue date and time	| The date and time of issuing the document for verified gross mass.|
| IMO0508	| Booking reference number | Booking reference assigned by carrier.|
| IMO0509	| Seal identification number | The identification number of the seal affixed to the container.|
| IMO0529	| Gross mass verifying party email | The email address for the referenced gross mass verifying party.|
| IMO0530	| Gross mass verifying party landline number	| The landline telephone number for the referenced gross mass verifying party.|
| IMO0531	| Gross mass verifying party mobile number	| The mobile number for the referenced gross mass verifying party.|
| IMO0532	| Gross mass verifying party country code	| A code representing the country address of the referenced gross mass verifying party.|
| IMO0533	| Gross mass verifying party street and number	| The street and number of the referenced gross mass verifying party.|
| IMO0534	| Gross mass verifying party city	| The city of the referenced gross mass verifying party.|
| IMO0535	| Gross mass verifying party postcode	| An alphanumerical code representing the postal area of the referenced verifying party.|
| IMO0579	| Gross mass verifying party P.O. Box	| The post office box of the referenced gross mass verifying party.|
| IMO0585	| Gross mass verifying person given name	| The given name of person in charge of verifying the gross mass authorized by the shipper.|

## IMO Data Structure 
A suggested structure for the VGM dataset would be as follows: 
<img width="1234" alt="Screenshot 2024-09-09 at 21 39 18" src="https://github.com/user-attachments/assets/591304f1-2306-4239-ba24-f529743a3696">

*NOTE: Insert IMO VERMAS UML Submodel Diagram Here*

## Implementable Message Standards 

### UNECE
SMDG developed and published the VERMAS message using UN/EDIFACT which serves the purpose of VGM reporting.  Message implementation guides and further details of the standard can be found at;
* https://service.unece.org/trade/untdid/d23a/trmd/vermas_c.htm
* https://smdg.org/working-groups/vermas-vgm/
