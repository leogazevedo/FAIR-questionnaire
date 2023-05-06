# Comparison of questionnaire versions

This document presents differences between each version of the questionnaire used to characterize digital objects of Materials Cloud and PubChem.

The first version of the questionnaire was used to characterize digital objects of Materials Cloud using Materials Cloud FIP. Its date is February 23rd 2023, and it is available [here](https://github.com/leogazevedo/FAIR-questionnaire/blob/main/FAIR-characterization-of-materials-cloud.pdf). This practical use brought us insights and improvements on questions' descriptions and helped identify requirements that gave birth to new questions which better fit the principles.

Afterwards, we improved that version and used it to characterize digital objects of PubChem. Its date is March 15th 2023, and it is available [here](https://github.com/leogazevedo/FAIR-questionnaire/blob/main/FAIR-characterization-of-pubchem.pdf). This characterization resulted in additional improvements to the questionnaire which final version is presented [here](https://github.com/leogazevedo/FAIR-questionnaire/blob/main/FAIR-characterization-questionnaire.pdf).

The differences between each version is presented as follows

## Differences between the versions used to assess Materials Cloud x PubChem

New questions added to the questionnaire version used to characterize PubChem:

- Question added to principle F1: *Are there other attributes able to identify the data?*
- Question added to principle F3: *Does the metadata include the identifier of the data it describes?*

Questions of principle A1 were moved to other principles:

- Material's Cloud A1 Q22 (*Which is the standardized mechanism or service used to provision the metadata?*) was moved to principle F4  Q18 PubChem characterization.
- Material's Cloud A1.Q23 (*Which is the standardized mechanism or service used to provision the data?*) was moved to A1.1. Q22 in PubChem characterization.

Questions with descriptions updated or split in new related question in PubChem characterization:

- Principle F4:
  - Materials Cloud Q18 (*Which technology is used to make metadata available (or indexed)?*) evolved to:
    - PubChem Q16: Is metadata registered or indexed in a searchable resource?
    - PubChem Q17: Which searchable resource is used to register or index the metadata?
  - Materials Cloud Q20 (*Which technology is used to your data available (or indexed)?*) evolved to:
    - PubChem Q20: Is data registered or indexed in a searchable resource?
    - PubChem Q21: Which searchable resource is used to register or index the data?
- Principle A1.1:
  - Materials Cloud Q24 (*Which standardized communication protocols are used to access the metadata?*) evolved to:
    - PubChem Q24: Which communication protocols are used to access the metadata?
  - Materials Cloud Q25 (*Is the protocol used to access the metadata open, free, and universally implementable?*) evolved to:
    - PubChem Q25 Is the protocol used to access the metadata standardized, open, free, and universally implementable?
  - Materials Cloud Q26 (*Which standardized communication protocols are used to access the data?*) evolved to:
    - PubChem Q24: Which communication protocols are used to access the data?
  - Materials Cloud Q25 (*Is the protocol used to access the data open, free, and universally implementable?*):
    - PubChem Q25: Is the protocol used to access the data standardized, open, free, and universally implementable?
- Principle I1:
  - Materials Cloud Q36 (*In what format the knowledge representation used for metadata is provided?*)
    - PubChem 36: In what formats the knowledge representation used for metadata is provided?
  - Materials Cloud Q37 (*Is the format used for knowledge representation of metadata formal, accessible, shared, and broadly applicable?*) evolved to:
    - PubChem Q37: Are the formats used for knowledge representation of metadata formal, accessible, shared, and broadly applicable?
  - Materials Cloud Q40 (*In what format the knowledge representation used for data is provided?*)
    - PubChem Q40: In what formats the knowledge representation used for data is provided?
  - Materials Cloud Q41 (*Is the format used for knowledge representation of data formal, accessible, shared, and broadly applicable?*)
    - PubChem Q41: Are the formats used for knowledge representation of data formal, accessible, shared, and broadly applicable?
- Principle I2:
  - Materials Cloud Q42 (*Which structured vocabularies are used to annotate the metadata?*) evolved to:
    - PubChem Q42: Which structured vocabularies are used for metadata?
  - Materials Cloud Q44: (*Which structured vocabularies are used to encode the data?*) evolved to:
    - PubChem Q44: Which structured vocabularies are used for data?
- Principle I3:
  - Materials Cloud Q46 (*Which qualified references the data include to other data?*) evolved to:
    - PubChem Q46: Which qualified references the metadata include to other data or metadata?
  - Materials Cloud Q47 (*Which qualified references the metadata include to other metadata?*) evolved to:
    - PubChem Q47: Which qualified references the data include to other data or metadata?
- Principle R1:
  - Materials Cloud Q50 (*What is the required accuracy of each attribute, if any?*) evolved to:
    - PubChem Q49: What is the required accuracy of each metadata attribute, if any?
    - PubChem Q51: What is the required accuracy of each attribute, if any?

## Differences between the versions used to assess PubChem x final version of the questionnaire

Questions with descriptions updated:

- Q1 (*What is your community?*) was updated to:
  - What is the research community evaluating the digital object?
- Q3 (*What is the main identifier of the data (i.e., data is understood as any digital object)?*) was updated to:
  - What is the main identifier (ID) of the data (i.e., the data of the digital object under evaluation)?
- Q4 (*Are there other attributes able to identify the data? What are them?*) was updated to:
  - Are there other attributes used to identify the data? If so, what are they?
- Q5 (*Is the data identifier (ID) globally unique or is it only unique in the database domain or for a specific context?*) was updated to: 
  - Is the data ID globally unique or unique in the dataset domain or for a specific context?
- Q12 (*Which of these metadata schemas are domain specific and which are domain-agnostic?) was updated to:
  - Which metadata schemas are domain-specific and which are domain-agnostic?
- Q13 (*Does the metadata include the identifier of the data it describes?*) was updated to:
  - Does the metadata include the ID of the data it describes?
- Q14 (*What is the technology that links metadata to the data (and vice-versa)?*) was updated to:
  - What technology does link metadata to the data (and vice-versa)?
- Q18 (*Which is the standardized mechanism or service used to provision the metadata?) was updated to:
  - Which technology is used to make your metadata available (or indexed)?
- Q22 (*Which is the standardized mechanism or service used to provision the data?*) was updated to:
  - Which technology is used to make your data available (or indexed)?
- Q28 (*What are the security mechanisms used for metadata access, such as ones used for authentication and authorization, and access conditions and access levels?*) was updated to:
  - What security mechanisms are used for metadata access, such as those used for authentication and authorization, and access conditions and access levels?
- Q29 (*What are the security mechanisms used for data access, such as ones used for authentication and authorization, and access conditions and access levels?*) was updated to:
  - What security mechanisms are used for data access, such as those used for authentication and authorization, and access conditions and access levels?
- Q36 (*In what formats the knowledge representation used for metadata is provided?*) was updated to:
  - In what format the knowledge representation used for metadata is provided?
- Q37 (*Are the formats used for knowledge representation of metadata formal, accessible, shared, and broadly applicable?*) was updated to:
  - Is the format used for knowledge representation of metadata formal, accessible, shared, and broadly applicable?
- Q40 (*In what formats the knowledge representation used for data is provided?*) was updated to:
  - In what format the knowledge representation used for data is provided?
- Q41 (*Are the formats used for knowledge representation of data formal, accessible, shared, and broadly applicable?*) was updated to:
  - Is the format used for knowledge representation of data formal, accessible, shared, and broadly applicable?
- Q43 (*Are the used vocabularies for metadata FAIR?*) was updated to:
  - Are the used vocabularies for metadata FAIR in their own right?
- Q45 (*Are the used vocabularies for data FAIR?*) was updated to:
  - Are the used vocabularies for data FAIR in their own right?
- Q52 (*Which usage license is used for your metadata?*) was updated to:
  - Which usage license is used for metadata?
- Q55 (*Which usage license is used for your data?*) was updated to:
  - Which usage license is used for data?
- Q58 (*Which metadata schemas do you use for describing provenance of the metadata?*) was updated to:
  - Which metadata schemas are used for describing the provenance of the metadata?
- Q59 (*Which metadata schemas do you use for describing provenance of the data?*):
  - Which metadata schemas are used for describing the provenance of the data?

Questions of principle A1.1 were moved to principle A1:

- A1.1 Q24 (*Which communication protocols are used to access the metadata?*) was moved to:
  - A1 Q28: Which communication protocols are used to access the metadata?
- A1.1 Q26 (*Which communication protocols are used to access the metadata?*) was moved to:
  - A1 Q29: Which communication protocols are used to access the metadata?
