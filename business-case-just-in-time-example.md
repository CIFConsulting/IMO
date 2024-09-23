# Just In Time (JIT) - Business Case

## Description

These guidelines are intended to provide guidance to the implementation of an electronic and, automated exchange of operational data between a ship and a port. As part of this guidance, the guidelines will also provide definitions of the general port and ship related parties.  These guidelines will make references to the IMO Compendium, IMO Reference Data Model and other specifications where relevant but will not specify any specific protocol or information exchange standard.

To facilitate a uniform way for implementation of, for example, the Just In Time (JIT) from port to port, this document can be used as a port agnostic implementation guide, on which local processes and circumstances can be developed.  These guidelines are port and trade agnostic. Benefits of Just In Time Arrival concepts are not limited to only the shipping industry, in particular to vessel traffic service centres, to ensure safe and efficient traffic flows, but will also assist the port industry to better plan and organize port operations, and eventually the complete logistic chain.

These guidelines encompass international standards 1 that are non-technical only: data element definitions are based on the IMO Compendium and a logical diagram for the port call process. The relevant technical standards (API specifications, technical and business performance requirements) are in process of being developed within ISO TC 8.  With the definition of a logical information exchange diagram, the guidelines can be implemented on a variety of platforms and protocols to support different types and sizes of ships and ports.

The logical parties involved are defined in a way recognizing that any party can be represented by different organizations or persons and that one-person or organization can represent several parties.  These guidelines contain definitions of the different work processes or events related to a ship's port call and its planning. This includes at what times electronic messages need to be exchanged and between which parties.

The definition of information requirements related to the different work processes is decoupled from the electronic messages, as information exchanges may not contain this information, if the information is already available for the relevant party.  These guidelines contain reference to relevant data standards, including sections in the IMO Compendium

These guidelines contain other information processes related to port calls, as well as other requirements related to the implementation of these guidelines.

## IMO Convention or Articles  


## Interactions 

- [X] B2B
- [X] B2G 
  
## Sequence Diagram

A high level sequence diagram for the JIT process is as follows

![image](https://github.com/user-attachments/assets/ff1aefbf-25f4-419a-b1c9-7e38e114fbda)
![image](https://github.com/user-attachments/assets/67c82bb2-a9dc-4fa3-8f8a-785d37461bd0)

## IMO Dataset

The dataset for the VGM under the IMO Reference Model is as follows:

| Data Number	| Data Element	| Definition |
| --- | --- | --- |
IMO0001|Agent city|The city of the referenced agent at port.
IMO0002|Agent contact family name|The agent's employee contact family name.
IMO0003|Agent country code|A code representing the country address of the referenced agent at port.
IMO0004|Agent country sub-division name|The country sub-division of the referenced agent at port.
IMO0006|Agent email|The email address for the referenced agent at port.
IMO0007|Agent identification number|The recognized identification number used by the ship’s agent at the port of notification.
IMO0008|Agent landline number|The landline telephone number for the referenced agent at port.
IMO0009|Agent mobile number|The mobile number for the referenced agent at port.
IMO0010|Agent name|The name of the agent at the port of arrival.
IMO0011|Agent postcode|An alphanumerical code representing the postal area of the referenced agent at port.
IMO0012|Agent street and number|The street and number of the referenced agent at port.
IMO0014|Authentication date time|The date and time of authentication.
IMO0016|Authenticator family name|The family name of the person attesting to the validity of the transmitted information.
IMO0017|Authenticator party identification number|"An identifying number, such as an agent identifier, of the party attesting to the validity of the transmitted information."
IMO0063|Date and time of arrival - actual|"The date and time the ship arrives at a specified location, ATA."
IMO0064|Date and time of arrival - estimated|"The date and time the ship is estimated to arrive at a specified location, ETA."
IMO0065|Date and time of departure - actual|"The date and time the ship departs from a specified location, ATD."
IMO0066|Date and time of departure - estimated|"The date and time the ship is estimated to depart from a specified location, ETD."
IMO0078|Message date time|The date and time the message is sent.
IMO0082|Message sender identifier|The identifier of the party transmitting the message.
IMO0108|"Port of arrival, coded"|A code representing the port where the ship arrives.
IMO0109|Port of arrival name|The name and country of the port where the ship arrives.
IMO0110|Port of call sequence number|A sequence number indicating the order of a port of call on a list.
IMO0111|"Port of departure, coded"|The code representing the port from which the ship departs.
IMO0112|Port of departure name|A name and country of the port from which the ship departs.
IMO0128|"Authenticator role, coded"|A code providing the role of the person attesting to the validity of the transmitted information.
IMO0136|Ship call sign|The ship’s identification used primarily for radio communications.
IMO0140|Ship IMO number|The ship identification number shown on its IMO ship’s certificate.
IMO0142|Ship name|The ship’s name shown on the IMO ship’s certificates.
IMO0153|Ship stay reference number|Reference number assigned by a port authority to the stay of a ship in the port.
IMO0172|"Primary purpose of call, coded"|A code representing the primary reason for the ship to enter the referenced port.
IMO0184|"Port facility, coded"|A code representing the port facility at the port of call.
IMO0185|Port facility name|The name and country of a port facility at the port of call.
IMO0191|Voyage number|An operator-assigned reference code for the ship's voyage.
IMO0229|Anchorage name|A name used to identify an anchorage. An anchorage is defined as an area in which vessels anchor or may anchor. (IHO Concept Register).
IMO0230|Terminal name|A name used to identify a terminal. A terminal covers that area on shore which provides buildings and constructions for the transfer of cargo or passengers from and to ships. (IHO Concept register).
IMO0231|Pilot Boarding Place name|"The name, number or description used to identify a Pilot boarding place. A Pilot boarding place is the location offshore where a pilot may board a vessel in preparation to piloting it through local waters. (IHO Concept register)."
IMO0232|Berth name|"A name used to identify a berth. A berth is defined as a place, generally named or numbered, where a vessel may moor or anchor. (IHO Concept register)."
IMO0233|Berth position|"A name, number or description used to identify a berth position. A berth position is a specific position within a berth where a vessel may be moored or anchored. (IHO Concept register)."
IMO0234|Date and time of arrival - requested|"The date and time the ship is requested to arrive at a specified location, RTA."
IMO0235|Date and time of arrival - planned|"The date and time the ship plans to arrive at a specific location, PTA."
IMO0236|Date and time of departure - requested|"The date and time the ship is requested to depart from a specified location, RTD."
IMO0237|Date and time of departure - planned|"The date and time the ship plans to depart from a specific location, PTD."
IMO0305|Message function code|Code providing the function of a message.
IMO0326|Ship MMSI number|The unique radio identification number (ship station identity).
IMO0536|Trade service identifier|The carrier internal trade service identifier of the service.
IMO0537|Distance to destination|The remaining distance in nautical miles reported by the vessel to a specific destination.
IMO0540|Date and time to location in port - actual|The actual date and time the ship actually reached the specified location in port.
IMO0541|Date and time to location in port - estimated|The date and time the ship estimates to reach the specified location in port.
IMO0542|Date and time to location in port - requested|The date and time the ship is requested to reach the specified location in port.
IMO0543|Date and time to location in port - planned|The date and time the ship plans to reach the specified location in port.
IMO0544|"Location in port, latitude"|The latitude (geographical coordinate) of an entity.
IMO0545|"Location in port, longitude"|The longitude (geographical coordinate) of an entity.
IMO0546|"Anchorage, coded"|A code used to identify an anchorage. An anchorage is defined as an area in which vessels anchor or may anchor. (IHO Concept register).
IMO0547|"Terminal, coded"|A code used to identify a terminal. A terminal covers that area on shore which provides buildings and constructions for the transfer of cargo or passengers from and to ships. (IHO Concept register).
IMO0548|"Berth, coded"|"A code used to identify a berth. A berth is defined as a place| generally named or numbered, where a vessel may moor or anchor. (IHO Concept register)."
IMO0574|Agent P.O. Box|The post office box of the referenced agent at port.
IMO0581|Agent contact given name|The agent's employee contact given name.
IMO0582|Authenticator given name|The given name of the person attesting to the validity of the transmitted information.
IMO0584|Service provider contact given name|The given name of the contact in the maritime service company.

## IMO Data Structure 
A suggested structure for the JIT dataset would be as follows: 

![Screenshot 2024-09-13 at 12 35 03](https://github.com/user-attachments/assets/a9b959a2-d544-4fc2-afe0-3a9513081f83)


## Implementable Message/API Standards 

