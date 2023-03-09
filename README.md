Notice to public contributors:

The contributor understands that any contributions, if accepted by the OGC Membership, shall be incorporated into the relevant OGC standards and best practices documents and that all copyright and intellectual property shall be vested in the OGC.

# OGC CDB Volume 14 Conversion of Shapefiles into OGC Geopackage

## Content

This folder contains the main text for the Draft Best Practices Document

* 19-066_Best_Practices_for_encoding_CDB_vector_data.adoc - the main Best Practice document with references to all sections.  This where all the main content creation and editing work will be done.
* remaining adocs - each section of the Best Practice document is in a separate document: follow directions in each document to populate
* figures - figures go here
* images - Image files for graphics go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)
* requirements - (OPTIONAL) directory for requirements and requirement classes to be referenced in clause_7_normative_text.adoc
* code - (OPTIONAL)sample code to accompany the Best Practice, if desired
* abstract_tests - (OPTIONAL)the Abstract Test Suite comprising one test for every requirement, optional
* UML - UML diagrams, if applicable

## Building

To produce the HTML of the Best Practice run `asciidoctor --safe -a data-uri -o
<Best Practice name>.html bp.adoc`

To produce the PDF of the Best Practice run `asciidoctor-pdf --safe -o
<Best Practice name>.pdf bp.adoc`
