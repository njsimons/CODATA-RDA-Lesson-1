---
##**Module 1C. Metadata associated with DOIs**##
---
When works are registered with DOI Registration Agencies, the Registrant (publisher, data center, or other information provider) is required to submit metadata about the resource that the DOI links to. Each Registration Agency maintains its own metadata schema and establishes rules for requiring and populating the metadata elements so it is important to check their respective websites for a list of metadata elements used and whether they are mandatory or optional.

Each Registration Agency also has the option of offering metadata look up and harvesting services that researchers may openly query. At a minimum, these services provide a basic citation for each DOI-assigned work: creator, title, publisher, publication year, and URL for the landing page of the resource. Additional metadata may include references cited in the work; funding sources; author ORCiD numbers; usage licenses attached to the work; and more.

Researchers may search for metadata associated with DOIs in various ways.  This module demonstrates how to use the API services of two Registration Agencies -- CrossRef and DataCite -- to query and retrieve valuable metadata about research outputs. The commands demonstrated use the process of DOI Content Negotiation to retrieve different representations of a work from the API service.