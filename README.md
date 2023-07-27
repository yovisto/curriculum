# Curriculum Ontology

This ontology is a formal representation that captures the fundamental concepts and their relationships to one another in the field of curriculum design and implementation. It provides a structured framework for organizing and understanding the key elements that make up a general curriculum. 

Current development is managed via GitHub: https://github.com/yovisto/curriculum Feel free to contribute or raise issues.

The model was developed based on the structure of the framework curricula for the states of Berlin and Brandenburg in Germany (https://bildungsserver.berlin-brandenburg.de/rlp-online). It is intended to serve as a starting point for formally opening up the structures of other states' curricula and competency frameworks related to curricula.

This ontology includes concepts that enable a high-level description of a curriculum. Thereby three main components are put in relation to each other: subjects, competencies, learning content.

The model is inspired by the "Datenmodell zur Abbildung von Lehrplänen" https://dini-ag-kim.github.io/modell_lehrplaene/draft/ and re-uses their dini:Curriculum and dini:CurriculumItem. Both extend the SKOS model in that the curriculum itself is to be understood as a skos:ConceptScheme and the individual components are subordinated to the curriculum as skos:Concept. Likewise, the herewith introduced classes have been fitted in as sub-classes, and the newly defined object properties inherit from skos:narrow and skos:broader to maintain compatibility.


This ist development version 1.0.0a. 

Namespace and further docu: [https://w3id.org/curriculum/]
