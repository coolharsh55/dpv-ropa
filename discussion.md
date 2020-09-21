# concepts that need discussion

These concepts are proposed as part of the ROPA extension for DPV, but need further discussion withing the DPVCG regarding their use and integration.

## Provenance of Processing Activities
The Belgian ROPA template mentions the 'status' concept as a catch-all phrase used to refer to a processing activity's start time, end time, involvement with prior processes, etc. These are relevant to the 'provenance' of the activity and therefore can be represented using PROV-O (as one option) or alternatively be redeclared within DPV.

## Technology used in Data Processing
How to specify use of specific technology or technological solution in data processing? For example, specific database or software.

## Specifying categories
What is the recommended way to specify a (sub-)category of something such as Recipients or Data Subjects? Is it `ex:SomeCategory rdfs:subClassOf dpv:Concept` ? For GDPR, categories are required to be specified for data subjects, personal data, recipients, amongst others. How to then refer to these categories in a triple, e.g. `ex:X1 ex:has ex:SomeCategory` without violating OWL2-DL conformity?

## Nature Of Data Transfer
The 'nature' concept mentioned here refers to the use of a legal basis to justify the transfer of personal data. These are already proposed by Georg/Signatu to the DPVCG and should be included.

## Process Owner / Role
The concept of process in ROPA documents is similar to PersonalDataHandling. ROPA documents also contain information regarding 'ownership' of a process, which could be descriptions regarding which department or division or section is responsible, or the specific people or roles in terms of responsibility within the organisation.

## Data Sensitivity Level
The level of 'sensitivity' of data indicates the severity of the data in terms of requiring additional measures or safeguards. These levels can be standardised, such as through ISO/IEC standards or the data security domain, or could be inter-organisational labels. Specifying them is important to convey the approach of an organisation in carrying out processing involving this personal data.