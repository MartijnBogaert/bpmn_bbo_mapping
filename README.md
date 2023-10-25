# Mapping BPMN to BBO using RML

## Documentation
- BPMN (Business Process Model and Notation): [https://www.omg.org/spec/BPMN/2.0/PDF](https://www.omg.org/spec/BPMN/2.0/PDF)
- BBO (BPMN Based Ontology): [https://www.irit.fr/recherches/MELODI/ontologies/BBO/index-en.html](https://www.irit.fr/recherches/MELODI/ontologies/BBO/index-en.html)
- RML (RDF Mapping Language): [https://rml.io/specs/rml/](https://rml.io/specs/rml/)

## Sources
- `union_bbo_and_bbo_extension.ttl`: [https://git.ai.wu.ac.at/teaming-ai/business-process-management-to-knowledge-graph](https://git.ai.wu.ac.at/teaming-ai/business-process-management-to-knowledge-graph)

## Usage
1. Download [RMLMapper](https://github.com/RMLio/rmlmapper-java).
2. Make sure all RML `TriplesMap`s' `logicalSource`s are given the correct `source` (e.g. local file path of bpmn file).
3. Run the following command in the current folder (base URI is set to `https://example.org` + check [RMLMapper documentation](https://github.com/RMLio/rmlmapper-java#cli) for full details):
```bash
java -jar ../rmlmapper-6.2.2-r371-all.jar -m union_bbo_and_bbo_extension.ttl -o output.nq -b 'https://example.org/'     
```

## Issues
- Elements inside subprocesses are not mapped.