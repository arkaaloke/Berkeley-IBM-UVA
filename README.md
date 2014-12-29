Berkeley-IBM-UVA
================

Ground Truth for three buildings: 

1. SODA Hall, UC Berkeley: a building built in 1996. Broadwin / Barrington BMS.
2. SDH Hall, UC Berkeley: a building built in 2009. Siemens BMS.
3. IBM Building 3: a building refunished in 2012. Multiple Systems.

Additional meta data:
1. Haystack.json - JSON file containing the tags defined by project-haystack.org with:
1.1. tags - the tags as defined on project-haystack.org including french and chinese translations
1.2. types - tags grouped by type as defined on the web page (most relevant are 'Marker' types as they define semantics, 'Ref' are references between element IDs, all other types are lexical properties)
1.3. sets - the marker sets defined for specific appliances
1.4. msetCnt - the count of markers used in the defined marker sets
2. Haystack.ttl - Ontology model for project-haystack.org. Contains similar information as the JSON file.

