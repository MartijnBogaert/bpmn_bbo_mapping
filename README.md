# Mapping BPMN to BBO using RML

## Documentation

- BPMN (Business Process Model and Notation): [https://www.omg.org/spec/BPMN/2.0/PDF](https://www.omg.org/spec/BPMN/2.0/PDF)
- BBO (BPMN Based Ontology): [https://www.irit.fr/recherches/MELODI/ontologies/BBO/index-en.html](https://www.irit.fr/recherches/MELODI/ontologies/BBO/index-en.html)
- RML (RDF Mapping Language): [https://rml.io/specs/rml/](https://rml.io/specs/rml/)

## Sources

- `rml-bpmn-to-bbo.ttl`: [https://git.ai.wu.ac.at/teaming-ai/business-process-management-to-knowledge-graph](https://git.ai.wu.ac.at/teaming-ai/business-process-management-to-knowledge-graph)

## Usage

1. Have a BPMN file ready (e.g. you can use [this one](https://github.com/camunda/bpmn-for-research/blob/master/BPMN%20for%20Research/English/01-Dispatch-of-goods/03-Solution/Dispatch-of-goods.bpmn) or any example BPMN available in its repo).
1. Download [RMLMapper](https://github.com/RMLio/rmlmapper-java).
1. Make sure all RML `TriplesMap`s' `logicalSource`s are given the correct `source` (e.g. local file path of bpmn file).
1. Run the following command in the current folder (base URI is set to `https://example.org` + check [RMLMapper documentation](https://github.com/RMLio/rmlmapper-java#cli) for full details):

```bash
java -jar ../rmlmapper-6.2.2-r371-all.jar -m rml-bpmn-to-bbo.ttl -o output.nq -b 'https://example.org/'
```

# Progress

Not all BBO classes are present in the mapping ([`rml-bpmn-to-bbo.ttl`](rml-bpmn-to-bbo.ttl)) yet. The table in [`mapping-progress.md`](mapping-progress.md) gives an overview of the yet to be and already mapped classes, as well as which BPMN element(s) map(s) to which BBO class. When expanding the mapping, please also update the table.

## Issues

- Elements inside subprocesses are not mapped.
- Not all BPMN elements are covered by the mapping yet; [`mapping-progress.md`](mapping-progress.md) gives an overview of which are and which are not.
